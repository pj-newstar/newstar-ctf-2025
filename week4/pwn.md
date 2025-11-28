# Pwn - Week 4

## <a href="#-fmtgot"><img src="../_assets/pwn.svg" height="20px" /></a> fmt&got

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| L1nk | 简单 | [w4.pwn.fmt-got.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.pwn.fmt-got.zip) | [newstar-2025:week4_fmt-got](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_fmt-got) | `13579` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:13579
> docker run -itd --rm --name w4_fmt_got -p 13579:13579 -e ICQ_FLAG=flag{b6026fc1-a53c-8b15-1353-1e1d8efda001} openctf/newstar-2025:week4_fmt-got
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

GOT means 《冰与火之歌：权力游戏》

## <a href="#-海市蜃楼"><img src="../_assets/pwn.svg" height="20px" /></a> 海市蜃楼

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| daimi | 中等 | [w4.pwn.mirage.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.pwn.mirage.zip) | [newstar-2025:week4_desert](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_desert) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w4_desert -p 9999:9999 -e ICQ_FLAG=flag{e091e92c-410e-b3bc-78ac-e161e32aed76} openctf/newstar-2025:week4_desert
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

天空像瓷蓝的碗倒扣着，太阳是一块滚烫的硫磺粘在碗底。越过三十层高的浮光掠影，那座变化的沙之城正在热浪里摇摆……

## <a href="#-memory"><img src="../_assets/pwn.svg" height="20px" /></a> memory

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| sysNow | 中等 | [w4.pwn.memory.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.pwn.memory.zip) | [newstar-2025:week4_memory](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_memory) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w4_memory -p 1337:1337 -e ICQ_FLAG=flag{9883ec05-8f92-cbb9-5f9d-4696430c7f86} openctf/newstar-2025:week4_memory
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

我忘记了 FLAG，你能帮我找到 FLAG 吗😢

## <a href="#-calc_queen"><img src="../_assets/pwn.svg" height="20px" /></a> calc_queen

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| daimi | 困难 | [w4.pwn.calc-queen.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.pwn.calc-queen.zip) | [newstar-2025:week4_calc-queen](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_calc-queen) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w4_calc_queen -p 9999:9999 -e ICQ_FLAG=flag{6d4fd5aa-d184-df9e-9741-4ae7c7b6fc2a} openctf/newstar-2025:week4_calc-queen
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

产品介绍：

呵呵！本计算姬可不会像上一个计算姬一样随随便便宕机。但是我说，你就没手没脚吗？你就不会自己算吗？……诶？诶诶诶？！！你干什么？我，我警告你！你别乱动！喂！喂喂！

## <a href="#-content"><img src="../_assets/pwn.svg" height="20px" /></a> content

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| ishmael | 困难 | [w4.pwn.content.gz](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week4/w4.pwn.content.gz) | [newstar-2025:week4_content](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week4_content) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w4_content -p 9999:9999 -e ICQ_FLAG=flag{823b7f25-a90d-6336-5af9-ee90bc1ea38f} openctf/newstar-2025:week4_content
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

01010101010……

> [!TIP]
> 打远程靶机的时间可能会比较长
