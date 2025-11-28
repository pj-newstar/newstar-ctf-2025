# Misc - Week 3

## <a href="#-流量分析s7-的秘密"><img src="../_assets/misc.svg" height="20px" /></a> 流量分析：S7 的秘密

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 简单 | [w3.misc.traffic-s7-secret.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.misc.traffic-s7-secret.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{IIOT_important!}</code>
> </details>

人们在虚拟大陆逐渐适应，为了更好的生活，城邦们正在大力发展第二产业。但是一个陈旧的机器突然接收到了信号，值班的工人们紧急捕获了信号发生后的信息，挑战者们可以帮助工业破译接收到的信息吗？请将信息放在 `flag{}` 内提交。

## <a href="#-日志分析盲辨海豚"><img src="../_assets/misc.svg" height="20px" /></a> 日志分析：盲辨海豚

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 简单 | [w3.misc.log-blind-dolphin.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.misc.log-blind-dolphin.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{SQL_injection_logs_are_very_easy}</code>
> </details>

城邦附近的水域突然出现了成群的海豚，导致城邦原本的海豚群被冲散。城邦的海豚会在半夜发出不同的回响，现在需要挑战者们通过声音帮助城邦找回走丢的海豚们。

## <a href="#-内存取证windows-篇"><img src="../_assets/misc.svg" height="20px" /></a> 内存取证：Windows 篇

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| miko | 中等 | [w3.misc.mem-forensics-windows.txt](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.misc.mem-forensics-windows.txt) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{125.216.248.74:11451_temp_admin123_arisamik}</code>
> </details>

本关考验你内存取证本领，请考生携带好文具（kali 虚拟机和 Volatility2），做好准备，迎接挑战。

本题的 FLAG 由多个问题的答案组成，使用下划线 `_` 将答案各部分连接，就能得到 FLAG：

1. 恶意进程的外联 `ip:port`
2. 恶意进程所在的文件夹名称
3. 用户的主机登录密码
4. 电脑主机的名称

涉及字母的部分统一小写，题目附件包含 FLAG 的举例。

## <a href="#-区块链以太坊的约定"><img src="../_assets/misc.svg" height="20px" /></a> 区块链：以太坊的约定

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 中等 | [w3.misc.ethereum-promise.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.misc.ethereum-promise.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{12_1145_20240614_solidity}</code>
> </details>

城邦附近开了一家存储链子的工坊，快来看看吧！

本题由多个小问题组成，得到各个小问题答案后用下划线 `_` 拼接并裹上 `flag{}` 即可：

1. 注册小狐狸钱包，并提交小狐狸钱包助记词个数
2. 1145141919810 Gwei 等于多少 ETH（只保留整数）
3. 查询账号 `0x949F8fc083006CC5fb51Da693a57D63eEc90C675` 第一次交易记录的日期，形式如 `20230820`
4. 使用 remix 编译运行附件中的合约，将输出进行提交

## <a href="#-jail-evil-eval"><img src="../_assets/misc.svg" height="20px" /></a> jail-evil eval

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| KAMIYA | 中等 | [w3.misc.jail-evil-eval.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.misc.jail-evil-eval.zip) | [newstar-2025:week3_jail-evil-eval](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week3_jail-evil-eval) | `9999` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

邪恶的 evil 带来了 eval！

想要拿到 FLAG 就得拿出真本事！

「借助 help 的力量是不道德的！」evil 如是说道。
