# Pwn - Week 1

## <a href="#-pwns-door"><img src="../_assets/pwn.svg" height="20px" /></a> Pwn's Door

| 出题人 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| Findkey | [w1.pwn.hacker-door.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week1/w1.pwn.hacker-door.zip) | [newstar-2025:week1_pwndoor](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week1_pwndoor) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w1_pwndoor -p 9999:9999 -e ICQ_FLAG=flag{98f97a20-61fa-bbc1-f977-4743584fa4d9} openctf/newstar-2025:week1_pwndoor
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

Key 已经为进入 Pwn 的世界做好了充分准备。他找到了可靠的伙伴，猫猫 NetCat 和蟒蛇 Python，还为 Python 配备了强大的工具 pwntools

有了这些，他相信自己一定能顺利通过考验

## <a href="#-gnu-debugger"><img src="../_assets/pwn.svg" height="20px" /></a> GNU Debugger

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| L1nk | 简单 | [w1.pwn.gnu-debugger.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week1/w1.pwn.gnu-debugger.zip) | [newstar-2025:week1_gdb-debugger](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week1_gdb-debugger) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w1_gdb_debugger -p 9999:9999 -e ICQ_FLAG=flag{a4d7d94a-4150-99ef-f411-5f36b2a944b3} openctf/newstar-2025:week1_gdb-debugger
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

进入 Pwn 的世界之后的第一关，了解你的好伙伴 GDB

## <a href="#-intbug"><img src="../_assets/pwn.svg" height="20px" /></a> INTbug

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| s1eepy | 简单 | [w1.pwn.intbug.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week1/w1.pwn.intbug.zip) | [newstar-2025:week1_intbug](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week1_intbug) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w1_intbug -p 1337:1337 -e ICQ_FLAG=flag{e3b8b8b3-9b09-ef02-d12a-51341dd930e8} openctf/newstar-2025:week1_intbug
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

整数好像有些奇怪的秘密。

## <a href="#-overflow"><img src="../_assets/pwn.svg" height="20px" /></a> overflow

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| Sally | 中等 | [w1.pwn.overflow.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week1/w1.pwn.overflow.zip) | [newstar-2025:week1_overflow](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week1_overflow) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w1_overflow -p 1337:1337 -e ICQ_FLAG=flag{98918c98-4336-d7b5-16a9-7fbbc82e2b58} openctf/newstar-2025:week1_overflow
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

咦？程序好像有后门，但是执行不到怎么办呢？

## <a href="#-input_function"><img src="../_assets/pwn.svg" height="20px" /></a> input_function

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| sysNow | 困难 | [w1.pwn.input-function.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week1/w1.pwn.input-function.zip) | [newstar-2025:week1_input-function](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week1_input-function) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w1_input_function -p 1337:1337 -e ICQ_FLAG=flag{b50376fc-b5db-e0fc-242f-8fcfa5d25920} openctf/newstar-2025:week1_input-function
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

什么？要输入一个函数？
