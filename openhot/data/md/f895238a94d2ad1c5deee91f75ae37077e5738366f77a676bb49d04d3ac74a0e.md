# Spring petclinic 项目采用 JDBI 替代 Spring Data

> 原标题：Dissecting Spring petclinic (Part 2 – Bending the persistence)

- 来源：Hacker News 热榜
- 发布时间：2026-11-15T00:34:12.000Z
- 开源热点：https://reisen-ww.github.io/hot-pages/openhot/items/irxn5t6oabpbqol44fi4u3n67
- 原文：https://hannomalie.github.io/posts/dissecting-spring-petclinic-persistence.html

## 摘要

作者在 Spring petclinic 项目中用 JDBI 替换了 Spring Data，以实现更纯粹的数据持久化。尽管这增加了代码复杂性，但作者认为这是实现理想测试方案的必要步骤。Spring Data 默认创建的测试数据隐含且难以探索，而 JDBI 则提供了更透明的替代方案。
