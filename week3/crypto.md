# Crypto - Week 3

## CBC 之舞

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| gloriablack | 简单 | [w3.cry.cbc-dance.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.cry.cbc-dance.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{cbc_dancing_1s_the_best_XD_miaowu~_wangang~}</code>
> </details>

我们截获了一个名为「影子信使」的间谍组织的两段通信。该组织使用一种定制的 AES-CBC 加密方案，据称其「混淆层」能有效地将明文「打乱」，使得即使获得额外一对明密文对，也无法推断出其他信息。

然而，我们的分析师在研究这两段通信时，发现了一个惊人的规律。第一段通信的密文 $c_1$ 和第二段通信的密文 $c_2$ 之间，存在着一种奇特的「排列」关系。

## 被泄露的素数

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| gloriablack | 中等 | [w3.cry.leaked-primes.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.cry.leaked-primes.zip) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{wh3n_th3_m0dul3_i3_bi9_en0ugh_U_c@n_c0ns1der_u3ing_coppersmith}</code>
> </details>

Alice 使用 RSA 加密了一个重要消息，但攻击者通过侧信道攻击得到了素数 $p$ 的高位部分（大约前 2/3 比特，可能有泄露和错误）。

你能利用 Copper Smith 方法恢复完整的 $p$，并解密出消息吗？

## 欧皇的生日

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| cathylin | 中等 | [w3.cry.lucky-birthday.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.cry.lucky-birthday.rar) | [newstar-2025:week3_birthday](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week3_birthday) | `10666` |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{-----you---are----so++++lucky+++++}</code>
> </details>

诶，骗人的吧，我难道不是欧皇吗？

## 随机数之旅 3

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| cathylin | 中等 | [w3.cry.random-journey-3.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.cry.random-journey-3.rar) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{1f59622f-ccbc-45c0-b9f5-731a51343027}</code>
> </details>

关键在你拥有的信息。

## GCL

| 出题人 | 难度 | 附件 |
|-----|-----|-----|
| cathylin | 困难 | [w3.cry.gcl.rar](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week3/w3.cry.gcl.rar) |

> <details><summary><strong>FLAG:</strong> <i>点此展开/收起</i></summary>
> <code>flag{2eac1c79-8abd-465e-82f4-96beffed69e4}</code>
> </details>

居然反过来了。
