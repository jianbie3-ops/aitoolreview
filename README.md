# AI Tool Review

AI工具英文测评站 — 通过Google SEO获得流量，靠联盟佣金赚美金。

## 网站结构

```
aitoolreview/
├── index.html                    # 首页
├── about.html                    # 关于页
├── css/
│   └── style.css                 # 样式
├── articles/
│   ├── best-ai-writing-tools.html    # AI写作工具测评
│   ├── best-ai-image-generators.html # AI绘图工具测评
│   └── best-ai-video-tools.html      # AI视频工具测评
```

## 赚钱模式

- **联盟佣金**: 文章中嵌入AI工具的联盟链接，用户购买赚佣金
- **佣金比例**: 20%-50% recurring（客户续费你就一直拿钱）
- **目标关键词**: "best AI writing tools", "best AI image generators" 等长尾词
- **流量来源**: Google SEO

## 下一步

1. 注册联盟账号：Jasper, Copy.ai, Writesonic 等
2. 替换文章中的占位联盟链接
3. 持续发布更多文章（每周3-5篇）
4. 申请 Google AdSense

## 部署

```bash
# GitHub Pages
git init && git add . && git commit -m "Initial"
gh repo create aitoolreview --public --push
# 然后在GitHub仓库 Settings > Pages 启用
```

## 技术栈

纯静态HTML + CSS，可托管在 GitHub Pages / Netlify / Vercel 等免费平台。
