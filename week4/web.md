# Web - Week 4

## <a href="#-ssti-在哪里"><img src="../_assets/web.svg" height="20px" /></a> SSTI 在哪里？

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| wsh_ | 简单 | [w4.web.ssti-where.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.web.ssti-where.zip) | [newstar-2025:week4_where-ssti](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_where-ssti) | `80` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

难道不是 SSRF 吗？

## <a href="#-武功秘籍"><img src="../_assets/web.svg" height="20px" /></a> 武功秘籍

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| yuhua | 中等 | [newstar-2025:week4_cve-kongfu](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_cve-kongfu) | `80` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小 Z 正在进攻高人留下的 CMS 遗迹，却久久没有进展，突然他戒指里的老爷爷传音给他：「小Z啊，凭你的能力可能没法打破这个遗迹的防护阵法，但是我这里有一本诸多高手共同编辑的武功秘籍，从中记载了大量的阵法漏洞，可助你一臂之力！」

小 Z 从戒指中取出武功秘籍，外观上已经年久泛黄，但是书名仔细辨认还是可以辨认出一个名称——CVE.

> [!TIP]
> 做此题时如出现不符合预期或奇怪的问题，可能是由于校园网环境的网络策略导致，请尝试校园网之外的网络环境。

## <a href="#-小-e-的留言板"><img src="../_assets/web.svg" height="20px" /></a> 小 E 的留言板

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| ENOCH | 中等 | [newstar-2025:week4_e-board](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_e-board) | `5000` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小 E 的「Project X」系统现已经公开，于是专门为它写了一个用户体验反馈留言板。小 E 每天都会亲自登录这个平台，查看用户反馈，而他的所有关键会话凭证都“安全”地保存在浏览器中。但是这个留言板存在一个巨大漏洞，你是否能利用这个被他忽视的漏洞，向平台「注入」一段特殊的指令，从而在小 E 毫无察觉的情况下，窃取到他浏览器的核心会话令牌呢？

## <a href="#-小羊走迷宫"><img src="../_assets/web.svg" height="20px" /></a> 小羊走迷宫

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| xNftrOne | 中等 | [newstar-2025:week4_xiaoyang](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_xiaoyang) | `11451` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小羊在去战斗的路上遇到了迷宫，但是她好像不小心迷路了，据说要走出去需要用到什么反序列化……什么伪协议……小羊不懂，你来帮帮她吧！

## <a href="#-sqlupload"><img src="../_assets/web.svg" height="20px" /></a> sqlupload

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| KAMIYA | 困难 | [w4.web.sqlupload.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.web.sqlupload.zip) | [newstar-2025:week4_sqlupload](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_sqlupload) | `80` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

哈哈，这次我用 SQL 来管理 Upload 的文件就不会出问题了吧！

> [!TIP]
> 本题 FLAG 在根目录下的 `flag` 文件中。
