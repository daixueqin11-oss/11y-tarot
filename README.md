# 11y塔罗牌

一个移动端优先、无需注册、永久保留免费抽牌能力的静态塔罗网站原型。

## 本地运行

直接打开 `index.html`，或在目录中运行：

```bash
python3 -m http.server 4173
```

然后访问 `http://localhost:4173`。

## 隐私与随机机制

- 用户问题及占卜记录仅保存在浏览器 `localStorage`。
- 抽牌使用浏览器 `crypto.getRandomValues()`，不暗示通灵或预测能力。
- 无账号、无付费墙、无第三方追踪脚本。
