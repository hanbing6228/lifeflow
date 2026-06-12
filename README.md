# LifeFlow · ADHD Flow Planner

轻推任务系统 — ADHD 友好计划 App（Capacitor iOS + PWA）

## 在线体验

https://adhd-flow-ios.vercel.app

## 本地开发

```bash
npm install
npm run sync
npm run ios          # 打开 Xcode
```

## 部署

```bash
npm run deploy:api   # Vercel 部署 + 写入 config.local.js
```

在 Vercel 设置 `GEMINI_API_KEY` 后 Redeploy，启用 AI 整理/洞察/日程。

## 文档

- [IOS-BUILD.md](./IOS-BUILD.md) — iOS 构建与 App Store 上架

## 结构

```
web/       Web 源码
api/       Vercel Serverless AI 代理
ios/       Capacitor Xcode 工程
scripts/   sync / deploy 脚本
```
