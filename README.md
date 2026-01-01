前端 (GitHub Pages): 静态页面 (HTML/CSS/JS)，通过 fetch 调用 Workers API。

后端 (Cloudflare Workers): 处理 API 请求（增删改查），与 D1 交互。

数据库 (Cloudflare D1): 存储待办事项数据（SQLite）。
