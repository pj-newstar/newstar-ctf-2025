# Crypto - Week 5

## 不给你看喵

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| cathylin | 简单 | [w5.cry.no-peek-meow.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.cry.no-peek-meow.rar) | [newstar-2025:week5_noshowyou-zkp](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_noshowyou-zkp) | `10666` |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Do_u_r3a1ly_n33d_me_2_5h0w_u_2_pr0v3_7h4t_1_h4v3_it?}</code>
> </details>

不告诉你喵

## BLS 多重签名：零的裂变

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| gloriablack | 中等 | [w5.cry.bls-multisig-zero.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.cry.bls-multisig-zero.zip) | [newstar-2025:week5_bls-sign](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_bls-sign) | `9999` |

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

欢迎来到 BLS 多重签名验证系统！我们使用最先进的 BLS12-381 曲线和聚合签名技术，确保签名的安全性和效率。

在这个系统中，用户可以注册自己的 BLS 公钥（需要提供 Proof of Possession），然后使用多重签名功能。系统会验证聚合公钥和聚合签名的有效性。

### 你的任务

你需要构造一个特殊的多重签名，使得：

1. 使用 3 个公钥对消息 `get_flag` 进行签名，其中 2 个公钥由你注册控制
2. 聚合公钥必须等于服务器的固定公钥，聚合签名验证通过

## Poly

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| cathylin | 中等 | [w5.cry.poly.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.cry.poly.rar) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{3bdb2424-591a-4a92-b587-74951c8ad192}</code>
> </details>

What's the gcd of three polynomials?

## Smile 盒

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| cathylin | 困难 | [w5.cry.smile-box.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.cry.smile-box.rar) | [newstar-2025:week5_smile](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_smile) | `10721` |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{Ur_awesome_4_being_able_2_successfully_find_1_high-probability_delta(?)_path!}</code>
> </details>

谁看到这个 S 盒的差分分布表都一定惊得下巴掉下来。
