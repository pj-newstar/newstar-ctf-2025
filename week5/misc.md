# Misc - Week 5

## <a href="#-区块链intbug"><img src="../_assets/misc.svg" height="20px" /></a> 区块链：INTbug

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 简单 | [w5.misc.intbug-chain.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.misc.intbug-chain.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Good_NewStar2025_Byeeeee!}</code>
> </details>

合约地址：`0xB6748b3B308b382E28438cc72872e2D70369D90b`

## <a href="#-应急响应把你-mikumiku-掉1"><img src="../_assets/misc.svg" height="20px" /></a> 应急响应：把你 mikumiku 掉（1）

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 中等 | [w5.misc.mikumiku.txt](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.misc.mikumiku.txt) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{CVE-2025-24813}</code>
> </details>

> [!NOTE]
> 本题为系列题，除序号外与本题名称相同的题共享同一附件和环境。
> - 解压密码：`d93e2cb85b2a51ef40e86e4bd6df0b14`
> - 账号：`newstar`
> - 密码：`newstar`

城邦为世界第一公主殿下搭建了网站，突然受到了 CVE 组织的攻击，你能帮城邦对服务器进行排查吗？

请问攻击者使用的漏洞编号是？

FLAG 格式：`flag{漏洞编号}`

## <a href="#-应急响应把你-mikumiku-掉2"><img src="../_assets/misc.svg" height="20px" /></a> 应急响应：把你 mikumiku 掉（2）

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 中等 | [w5.misc.mikumiku.txt](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.misc.mikumiku.txt) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{miiikuuu_miiiku}</code>
> </details>

FLAG 格式：`flag{木马连接密码_恶意用户密码}`

> [!TIP]
> 用户密码是六位特定范围内的字母构成。

## <a href="#-应急响应把你-mikumiku-掉3"><img src="../_assets/misc.svg" height="20px" /></a> 应急响应：把你 mikumiku 掉（3）

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| willyz | 中等 | [w5.misc.mikumiku.txt](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.misc.mikumiku.txt) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Miku_miku_oo_ee_oo}</code>
> </details>

被加密文件里面的内容是什么？

FLAG 格式：`flag{文件内容}`

## <a href="#-ai-hacker"><img src="../_assets/misc.svg" height="20px" /></a> AI HACKER

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| Mrsh | 困难 | [newstar-2025:week5_ai-hacker](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_ai-hacker) | `5052` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:5052
> docker run -itd --rm --name w5-ai-hacker -p 5052:5052 -e CLEANUP_INTERVAL=3600 -e MAX_UPLOAD_COUNT=2 -e MAX_UPLOAD_BYTES=536870912 openctf/newstar-2025:week5_ai-hacker
> ```
> </details>

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{C00l!_e45y_CVE_WITH_FUNNY_DLG}</code>
> </details>

SafeLLM Hub 一点都不 safe :(

Example GGUF: [Qwen1.5-0.5B-Chat-GGUF](https://huggingface.co/Qwen/Qwen1.5-0.5B-Chat-GGUF)

Paper: [Deep Leakage from Gradients](https://arxiv.org/abs/1906.08935)

> [!TIP]
> 访问靶机的 `/flag` 路径获取题目任务

## <a href="#-time-hacker"><img src="../_assets/misc.svg" height="20px" /></a> TIME HACKER

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| Mrsh | 困难 | [w5.misc.time-hacker.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.misc.time-hacker.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Y0u_4re_tHe_ReaL_TIME_H@cker!!}</code>
> </details>

我所害怕的，只有时间。
