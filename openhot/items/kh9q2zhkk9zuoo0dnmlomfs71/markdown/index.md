# PyPI 上被篡改的 LiteLLM 1.107.0 携带凭据窃取器与远程执行后门

> 原标题：Compromised LiteLLM 1.107.0 on PyPI Installs a Credential Stealer and Backdoor

- 来源：Hacker News 热榜
- 发布时间：2026-10-21T14:00:26.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/kh9q2zhkk9zuoo0dnmlomfs71
- 原文：https://safedep.io/litellm-pypi-compromise-credential-stealer-backdoor/

## 摘要

SafeDep 披露 PyPI 上的 litellm 1.107.0 携带凭据窃取器和远程代码执行后门，PyPI 已下架该版本，1.106.2、1.107.0rc1、1.107.0rc2 及配套包 litellm-proxy-extras==0.4.110、litellm-enterprise==1.78 均无问题。

## 推荐理由

文章拆解了植入物如何经构建配置进入 wheel 并给出完整 IOC 与哈希，便于排查受影响主机。
