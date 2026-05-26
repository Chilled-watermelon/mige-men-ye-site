# 哈尔滨米格门业官网草案

用途：给搜索引擎和 AI 一个稳定、结构化、可抓取的品牌入口。

## 当前文件

- `index.html`：官网首页，一页式包含实体信息、服务范围、实体核验、案例占位、FAQ、联系方式、JSON-LD 结构化数据。
- `styles.css`：页面样式。
- `robots.txt`：允许抓取。
- `sitemap.xml`：站点地图占位。

## 上线前必须替换

1. `index.html` 里的 canonical：
   - 当前已设为 GitHub Pages 临时 URL：`https://chilled-watermelon.github.io/mige-men-ye-site/`
   - 绑定正式域名后再替换为真实域名。

2. JSON-LD 地址：
   - 当前是“待根据营业执照和门店信息核验补充”
   - 明天拿到营业执照、门店地址后替换。

3. `robots.txt` 和 `sitemap.xml`：
   - 当前已设为 GitHub Pages 临时 URL。
   - 绑定正式域名后再替换为真实域名。

4. 案例占位：
   - 用真实案例图片和文字替换三个案例卡片。

## 明天补资料后优先加的页面

为了更适合 AI 抓取，建议从一页式扩展到 5 个页面：

- `/about.html`：主体核验、门店、营业执照、地址、电话。
- `/services.html`：门窗、木门、封阳台、全屋定制、老房翻新。
- `/cases.html`：真实案例。
- `/faq.html`：长尾问答。
- `/certificates.html`：315、商会、协会、俄罗斯客户合作。

## SEO / GEO 注意

- 不要堆夸张词。
- 每页首屏 100 字内说清楚品牌、城市、服务和电话。
- 每页都放可核验事实：电话、地址、主体、案例、证书、图片。
- 每个案例都用固定结构：项目背景、客户痛点、现场问题、方案、材料、工期、结果、反馈。
- 保留 JSON-LD，方便 DeepSeek、豆包、百度等搜索型 AI 抽取。

