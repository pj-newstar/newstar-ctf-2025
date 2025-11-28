# Pwn - Week 5

## <a href="#-复读机堂堂归来复读机堂堂归来"><img src="../_assets/pwn.svg" height="20px" /></a> 复读机堂堂归来！复读机堂堂归来！

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| L1nk | 简单 | [w5.pwn.fuduji-back.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.pwn.fuduji-back.zip) | [newstar-2025:week5_fuduji-back](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_fuduji-back) | `24680` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 24680
> docker run -itd --rm --name w5_fuduji_back -p 24680:24680 -e ICQ_FLAG=flag{756cdf2c-331c-a3fe-7fcb-1b956b574c8f} openctf/newstar-2025:week5_fuduji-back
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小明依旧不信邪，他觉得只要给复读机加上很多保护那就没有问题。小明依旧不信邪，他觉得只要给复读机加上很多保护那就没有问题。

## <a href="#-note"><img src="../_assets/pwn.svg" height="20px" /></a> note

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| sysNow | 中等 | [w5.pwn.note.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.pwn.note.zip) | [newstar-2025:week5_note](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_note) | `1337` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 1337
> docker run -itd --rm --name w5_note -p 1337:1337 -e ICQ_FLAG=flag{364cd82f-5276-62d1-3f12-67a4eac134cc} openctf/newstar-2025:week5_note
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

一个笔记管理系统，从这里开始学习堆利用吧！

## <a href="#-stdout"><img src="../_assets/pwn.svg" height="20px" /></a> stdout

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| L1nk | 中等 | [w5.pwn.stdout.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.pwn.stdout.zip) | [newstar-2025:week5_stdout](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_stdout) | `13579` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 13579
> docker run -itd --rm --name w5_stdout -p 13579:13579 -e ICQ_FLAG=flag{8cec722d-7a18-e936-cca2-2ab1b7836f26} openctf/newstar-2025:week5_stdout
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小 Y 在学习 C 语言时得知 puts 函数会把一个字符串写入到标准输出  stdout.

小Y突发奇想，直接写入 stdout ，那不就能用 read 来实现 puts 了吗？！

## <a href="#-go"><img src="../_assets/pwn.svg" height="20px" /></a> go?

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| ishmael | 困难 | [w5.pwn.go-question.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.pwn.go-question.zip) | [newstar-2025:week5_pwn-go](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_pwn-go) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w5_pwn_go -p 9999:9999 -e ICQ_FLAG=flag{198747ab-6774-fb27-cfd7-b379984ae2bf} openctf/newstar-2025:week5_pwn-go
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

↑→↓↓↓???

## <a href="#-pwn-the-world"><img src="../_assets/pwn.svg" height="20px" /></a> Pwn the world

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| daimi | 困难 | [w5.pwn.hack-the-world.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.pwn.hack-the-world.zip) | [newstar-2025:week5_pwn-world](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_pwn-world) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # nc 127.0.0.1 9999
> docker run -itd --rm --name w5_pwn_world -p 9999:9999 -e ICQ_FLAG=flag{64f8a5f6-0a46-332e-ace5-a77ad314f649} openctf/newstar-2025:week5_pwn-world
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

Pwn 掉一整个世界！
