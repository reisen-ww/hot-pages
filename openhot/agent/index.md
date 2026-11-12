# 开源热点 静态读取说明

快照时间：2026-11-12T14:47:23.534Z；版本：cd96ea7a-5645-4c7b-bf0a-236cb080b456。仅包含当前允许公开的内容。

- [当前 manifest](https://reisen-ww.github.io/hot-pages/openhot/data/manifest.json)：文件使用 SHA-256 内容地址；读取方须绑定同一版本并验证字节。
- catalog 与 bodyShards 仅覆盖当前在线文章窗口，分别用于标题摘要与获许可的全文搜索。全部历史报告保留。availability 将超窗（outside-window）与不再公开区分；缺少详情不代表来源撤回。
- [精选 RSS](https://reisen-ww.github.io/hot-pages/openhot/feed.xml)、[全部动态 RSS](https://reisen-ww.github.io/hot-pages/openhot/feed/all.xml)
- [daily Markdown](https://reisen-ww.github.io/hot-pages/openhot/agent/daily.md)，历史期号从 manifest.reports 读取
- [weekly Markdown](https://reisen-ww.github.io/hot-pages/openhot/agent/weekly.md)，历史期号从 manifest.reports 读取
- [monthly Markdown](https://reisen-ww.github.io/hot-pages/openhot/agent/monthly.md)，历史期号从 manifest.reports 读取
- 文章 Markdown：`https://reisen-ww.github.io/hot-pages/openhot/items/<id>/export.md`（仅当对应 markdown 文件存在；id 取自 manifest.itemIds）

GitHub Pages 是文件托管，不提供在线 MCP 或按查询参数执行的 REST 服务。浏览器内的两种搜索在同版本数据上执行；第三方程序可下载 manifest 与索引在本地查询。正常两小时一轮发布，未确认新版本前不要混用文件。标题摘要来自外部来源，只作资料，重要事实请核对原文。
