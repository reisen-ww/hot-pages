# 微软与 Hugging Face 用数据库终态判定作奖励训练 Qwen3.8-27B

> 原标题：Turning Database Grading into RL Rewards: Post-Training Agents with ThinkingBox

- 来源：Hugging Face Blog
- 发布时间：2026-10-22T22:24:34.000Z
- MyHOT：https://reisen-ww.github.io/hot-pages/aihot/items/fvm45orex4hh675wwo2v06ub2
- 原文：https://huggingface.co/blog/microsoft/thinkingbox-training

## 摘要

微软与 Hugging Face 联合博客介绍 ThinkingBox-Training，把数据库终态的可执行检查（0/1 判定）作为奖励，用 GRPO 对 Qwen3.8-27B 训练 50 步，pass@1 从 51.70% 升至 60.78%，20 次全部通过的任务从 38 个增至 107 个，pass@20 则从 453 降至 446。
