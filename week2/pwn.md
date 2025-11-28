# Pwn - Week 2

## <a href="#-刻在栈里的秘密"><img src="../_assets/pwn.svg" height="20px" /></a> 刻在栈里的秘密

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| L1nk | 简单 | [newstar-2025:week2_stack-secret](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week2_stack-secret) | `7777` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 7777
> docker run -itd --rm --name w2-stack-secret -p 7777:7777 -e ICQ_FLAG=flag{82d6a798-485b-2b4c-bc10-b52b21e7520e} openctf/newstar-2025:week2_stack-secret
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

欢迎来到 x64 位餐厅！服务员 printf 先生有点健忘，他只能记住您菜单上的前 6 道菜（RDI, RSI, RDX...），再多就只能堆在摇摇晃晃的餐盘（栈）上了。更糟糕的是，他会把你写的菜单原封不动地大声念出来。

你能设计一份别有用心的菜单，让他念着念着，就把秘密房间的密码念给你听吗？

## <a href="#-no-shell"><img src="../_assets/pwn.svg" height="20px" /></a> no shell

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| Findkey | 简单 | [w2.pwn.no-shell.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week2/w2.pwn.no-shell.zip) | [newstar-2025:week2_noshell](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week2_noshell) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w2-noshell -p 9999:9999 -e ICQ_FLAG=flag{418bb6f5-e6fc-d4c0-392a-e91413d11002} openctf/newstar-2025:week2_noshell
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

Key 在冒险时误入了一个秘境，这里设有一种名为 sandbox 的阵法，他发现不能再像以前一样夺取秘境控制权，但是他仍然发现了获取 FLAG 的方法。

## <a href="#-syscall"><img src="../_assets/pwn.svg" height="20px" /></a> syscall

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| s1eepy | 简单 | [w2.pwn.syscall.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week2/w2.pwn.syscall.zip) | [newstar-2025:week2_syscall](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week2_syscall) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w2-syscall -p 1337:1337 -e ICQ_FLAG=flag{4e993713-1578-c674-598a-5cf4d420993a} openctf/newstar-2025:week2_syscall
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

远在 Hong Kong 的朋友常说「虽然世界给他关上了门，但同时又开了一扇窗」

## <a href="#-input_small_function"><img src="../_assets/pwn.svg" height="20px" /></a> input_small_function

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| sysNow | 中等 | [w2.pwn.input-small-function.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week2/w2.pwn.input-small-function.zip) | [newstar-2025:week2_small-function](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week2_small-function) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w2-small-function -p 1337:1337 -e ICQ_FLAG=flag{038342e4-a682-5c0a-6c24-b6463188d266} openctf/newstar-2025:week2_small-function
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

为什么能输入的字符这么少？

## <a href="#-calc_beta"><img src="../_assets/pwn.svg" height="20px" /></a> calc_beta

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| daimi | 困难 | [w2.pwn.calc-beta.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week2/w2.pwn.calc-beta.zip) | [newstar-2025:week2_calc-beta](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week2_calc-beta) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w2-calc-beta -p 1337:1337 -e ICQ_FLAG=flag{117cd141-9ae9-6a72-74a1-311b7e215f2b} openctf/newstar-2025:week2_calc-beta
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

一台 Beta 版的计算姬，根本没在市场上流通过……是怎么搞到它的？这个版本的计算姬还没实装计算功能，也没有人格。等等，这里貌似有一个……严重的漏洞？！！
