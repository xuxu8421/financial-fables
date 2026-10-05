# Financial Fables · 金融寓言

A 15-story financial learning app built with JavaScript, HTML, and CSS. It combines story-based explanations and quizzes with keyboard navigation, persistent reading state, and responsive media.

**[Open the live app](https://xuxu8421.github.io/financial-fables/)** · [Project case study](https://sizhang-xu-portfolio.windy-sun-8382.chatgpt.site/reader.html)

## Engineering highlights

- Hash routes and History API navigation connect the story library and individual reading views.
- Reading status and display preferences persist across visits.
- Semantic quiz controls, keyboard navigation, aria-live feedback, and reduced-motion behavior support accessible interaction; responsive images use mobile AVIF assets.

## Run locally

No package installation or build step is required. From the repository root:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>. The application is served from `index.html`; illustrations are in `assets/`.

## 关于项目

先进入一个故事，再看懂背后的金融机制。

当前收录 15 篇独立寓言，覆盖资产定价、拍卖与信息、市场微观结构、银行与流动性、公司金融。每篇由完整故事、概念拆解和必要的迁移题组成。

学习讨论，不构成投资建议。
