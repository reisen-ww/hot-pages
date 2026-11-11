# jinx 将 231,777 个 nixpkgs 属性转译为可运行的 TypeScript

> 原标题：Nixpkgs for the frontend impaired

- 来源：Lobsters 热榜
- 发布时间：2026-10-13T10:55:15.022Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kv0e5nkepewrs978gqai337i1
- 原文：https://fzakaria.com/2026/10/12/nixpkgs-for-the-frontend-impaired

## 摘要

作者发布 jinx，将 Nix 文件转译为 TypeScript，并编译了包含 231,777 个属性的完整 nixpkgs 树；在 x86_64-linux、aarch64-linux 和 aarch64-darwin 上，对比结果显示可评估属性的 drvPath 全部一致。

## 推荐理由

jinx 将完整 nixpkgs 转译为 TypeScript，并用 drvPath 对照验证结果，为在浏览器和 TypeScript 工具链中探索 Nix store 模型提供了具体入口。
