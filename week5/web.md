# Web - Week 5

## <a href="#-被玩坏的-ai"><img src="../_assets/web.svg" height="20px" /></a> 被玩坏的 AI

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| 归茛 | 中等 | [newstar-2025:week5_broken-ai](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_broken-ai) | `80` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:80
> docker run -itd --rm --name w5-broken-ai -p 80:80 -e ICQ_FLAG=flag{cc7214f2-7c2b-412c-ca22-91466438f884} openctf/newstar-2025:week5_broken-ai
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

技术团队排查后发现，AI 在接收外部输入时，会直接将部分内容融入到 HTTP 响应的处理流程中，却没对可能「拆分响应结构」的特殊字符做过滤。现在需要你模拟攻击者，找到漏洞的关键处理逻辑。

## <a href="#-废弃的网站"><img src="../_assets/web.svg" height="20px" /></a> 废弃的网站

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| sanjio | 困难 | [w5.web.abandoned-site.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.web.abandoned-site.zip) | [newstar-2025:week5_abandoned-site](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_abandoned-site) | `5000` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:5000
> docker run -itd --rm --name w5-abandoned-website -p 5000:5000 -e ICQ_FLAG=flag{d0d0b6c4-1f18-a2ed-b6dd-7d518fc50626} openctf/newstar-2025:week5_abandoned-site
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

废弃的网站就别争了。

## <a href="#-小-w-和小-k-的故事最终章"><img src="../_assets/web.svg" height="20px" /></a> 小 W 和小 K 的故事（最终章）

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| KAMIYA | 困难 | [w5.web.w-k-story-final.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.web.w-k-story-final.zip) | [newstar-2025:week5_wk-story-final](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_wk-story-final) | `3000` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:3000
> docker run -itd --rm --name w5-wk-story-final -p 3000:3000 -e ICQ_FLAG=flag{b49c020a-965a-e485-0904-fe61d323a7c6} openctf/newstar-2025:week5_wk-story-final
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

小 K 和小 W 一起来到了 NewStar 的 Web 最后一关。

此乃旧时代的落幕，亦将见证诸位 NewStar 的崛起。

> [!TIP]
> 本题靶机环境使用 `node:20-alpine` 作为基础镜像构建

## <a href="#-眼熟的计算器"><img src="../_assets/web.svg" height="20px" /></a> 眼熟的计算器

| 出题人 | 难度 | 附件 | 环境镜像 | 端口 |
|-----|-----|-----|-----|-----|
| KAMIYA | 困难 | [w5.web.familiar-calc.zip](https://github.com/pj-newstar/newstar-ctf-2025/releases/download/attachment-week5/w5.web.familiar-calc.zip) | [newstar-2025:week5_familiar-calc](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_familiar-calc) | `9999` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:9999
> docker run -itd --rm --name w5-familiar-calc -p 9999:9999 -e ICQ_FLAG=flag{81d5c7e2-71b0-3cf3-43be-120d919575e1} openctf/newstar-2025:week5_familiar-calc
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

今天又买了个新的计算器，看看又给我整了什么花活。

## <a href="#-binary-blog"><img src="../_assets/web.svg" height="20px" /></a> Binary Blog

| 出题人 | 难度 | 环境镜像 | 端口 |
|-----|-----|-----|-----|
| 归茛 | 困难 | [newstar-2025:week5_binary-blog](https://hub.docker.com/r/openctf/newstar-2025/tags?name=week5_binary-blog) | `80` |

> <details><summary><strong>Docker 启动命令:</strong> <i>点此展开/收起</i></summary>
>
> ```bash
> # http://127.0.0.1:80
> docker run -itd --rm --name w5-binary-blog -p 80:80 -e ICQ_FLAG=flag{aff75a67-e0bc-8f15-40d8-cad62ad74ec6} openctf/newstar-2025:week5_binary-blog
> ```
> </details>

> <details><summary><strong>FLAG:</strong> 动态</summary>
> </details>

欢迎来到的我的二进制博客。
