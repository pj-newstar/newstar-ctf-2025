# NewStar CTF 2025

This repository is the archive of [NewStar CTF 2025](https://newstar.wiki/guide/2025/). Attachments and images of challenges are also part of the repository.

You can view the challenge details in each `week?` or `extras` directory:

- [Week 1](./week1)
- [Week 2](./week2)
- [Week 3](./week3)
- [Week 4](./week4)
- [Week 5](./week5)
- [Extras (挑战题)](./extras)

You can download challenge images at [openctf/newstar-2025](https://hub.docker.com/r/openctf/newstar-2025) on Docker Hub.

You can download challenge attachments at [Github Release](https://github.com/project-newstar/newstar-ctf-2025/releases/tag/attachment) page of this repository.

## Metapack

All the metadata, images, attachments of challenges, are presented at [metapack.json](./metapack.json).

It has the following structure:

```typescript
interface Metadata {
  id: number | string;       // must be unique
  name: string;
  description: string;
  category: string[];        // sorted based on hierarchical relationship
  tags: string[];
  author: string | string[]; // empty string means unknown or anonymous
  attachments: string[] | { name: string; url: string }[];
  services: {
    // service name id, must be unique
    name: string;
    // remote image url, can use `docker pull` to download
    image: string;
    // ports to be exposed in the container
    exposes?: {
      port: number;                 // port number
      type: "tcp" | "udp" | "http"  // protocol type, `http` means taking tcp proxy (e.g. frp)
    }[];
    // environment variables
    environment?: {
      [key: string]: string | null; // `null` means use non-static or refs value (e.g. `answer`)
    };
    // resource limits
    limits?: {
      cpu?: string;          // CPU limit, e.g. "0.5"
      memory?: string;       // memory limit, e.g. "256Mi"
      storage?: string;      // storage limit, e.g. "1Gi"
    };
    // resource requests
    requests?: {
      cpu?: string;          // CPU request, e.g. "0.1"
      memory?: string;       // memory request, e.g. "64Mi"
      storage?: string;      // storage request, e.g. "128Mi"
    };
    // the hostnames of this service, other services can access it by these hostnames
    hosts?: string[];
    // names of services that this service depends on
    depends_on?: string[];
    // entrypoint of the service
    entrypoint?: string[];
    // command to run the service
    command?: string[];
    // VLAN ID, default means default VLAN
    vlan?: string;
    // whether the service can access the internet, default means any
    internet?: boolean;
  }[];
  answer: string | null;     // `null` means dynamic generated answer

  /* optional fields */

  difficulty?: number;
  hints?: string[];          // hints for the challenge
  hidden?: boolean;          // whether the challenge is hidden
  score?: number;            // static score

  /**
   * Plugin ids, each plugin has its own schema (or add fields on the global metadata schema).
   * This field is only reserved to avoid conflicts between fields, or categorize extra data.
   */
  plugins?: {
    id: string; // plugin id
    data?: {
      [key: string]: any;
    };
  }[];

  /**
   * Extra fields, can be customized according to specific needs, mostly for human-readable data.
   */
  extra?: {
    [key: string]: any;
  };
}[];

type Metapack = Metadata[];
```

> [!IMPORTANT]
> Dynamic flag requires you to pass environment variables `ICQ_FLAG` to the container when starting it.

The *metapack* file may help you to deploy the whole CTF game on your system.

## Credits and License

All authors of challenges can be found at [AUTHORS](./AUTHORS).

Copyright (c) Authors of NewStar CTF 2025, Beijing integrity technology co., Ltd. (a.k.a. ichunqiu). All rights reserved, independently for each author.

Distribution of text document follows [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Challenge related codes, attachments, images, etc. are licensed under [LGPL 3.0](./LICENSE). Unless otherwise specified.

You can directly use them for non-profit purposes without any modification. Charged distribution of them is not allowed if not permitted.

For distribution and deployment on various platforms, please add a link to this repository.

## Additional Notes

So-called *image(s)* in this document refers to things like virtual machine images, docker images, etc. It does not refer to images in the sense of pictures.

The correspondence between the author's ID and real-name information will not be made public. The copyright subject has the right of interpretation of it.
