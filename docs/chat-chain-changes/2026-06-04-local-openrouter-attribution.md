---
date: 2026-06-04
commit: local
feature: OpenRouter attribution title
impact: 只影响 OpenRouter dashboard attribution，不改变 `/chat-run` 协议、消息落库、模型调用或 run 生命周期。
---

`manager.ts` 的 bridge 默认 OpenRouter attribution title 从 `Hermes-own` 改为 `Hermes-own`，与 `https://github.com/zhemed/Hermes-own` referer 品牌保持一致。
