# DeepSeek
_Last updated: 2026-09-16_

Corporate: Reuters reported (Sep 15) DeepSeek plans to hire GL Ventures (Hillhouse) partner Yan Wentao as its first CFO ahead of a possible Shanghai STAR Market IPO, with CITIC Securities among underwriters — a step from research lab toward conventional corporate structure.

On Sep 10, 2026 DeepSeek released DeepSeek-V4.1-Flash, the smallest model in a new architecture family with native multimodal visual understanding — reportedly cutting agent KV-cache memory ~4x (via CED split, CSA2, FP4 KV cache, SWA elimination; ~890 bytes/token) with 1M context. Multiple third-party tests put it ahead of V4-Pro on performance, cost, speed and runtime, so DeepSeek is phasing V4-Pro out: from 04:00 UTC Sep 14, 2026 all deepseek-v4-pro requests route to V4.1-Flash at V4.1-Flash rates; V4-Flash and V4-Flash-Vision-Exp are retired with temporary compatibility aliases. Model name on API: deepseek-flash. Geopolitical backdrop: the Sep 8 NSA/FBI/CISA joint advisory named DeepSeek among six Chinese firms accused of industrial-scale distillation of Claude, GPT, Gemini and Grok.

## Timeline
- 2026-09-15 — Reuters: hiring GL Ventures partner Yan Wentao as first CFO ahead of possible Shanghai STAR IPO; CITIC Securities tapped as underwriter (reuters.com)
- 2026-09-14 — Reversed V4-Pro API retirement citing user demand; billing unchanged, further notice promised (api-docs.deepseek.com)
- 2026-09-10 — Released DeepSeek-V4.1-Flash: new architecture family's smallest model, native multimodal, 1M context, ~4x lower KV-cache memory; V4-Pro phased out Sep 14 with requests rerouted at V4.1-Flash rates; V4-Flash/V4-Flash-Vision-Exp retired (deepseek.com / api-docs.deepseek.com)
- 2026-09-08 — NSA/FBI/CISA joint advisory accused DeepSeek and five other Chinese AI firms (Alibaba, Moonshot AI, MiniMax, StepFun, Z.AI) of industrial-scale distillation of U.S. frontier models (cyberscoop.com / defenseone.com)
- 2026-08-21 — Released DeepSeek-V4-Flash-Vision-Exp, an experimental multimodal API model with V4-Flash-level text capabilities, image input billed up to 384 tokens each, Chat Completions/Messages/Responses support, and Files API support (api-docs.deepseek.com)
- 2026-08-14 — Launched DeepSeek Harness developer preview: source-included modular agent harness with plugins for models, tools, skills, sessions, sandboxes, storage, loops, scheduling, and UI (deepseek.com)
- 2026-08-13 — DeepSeek-V4-Pro GA rolled out on app, web, and API; added low/high/max thinking effort, native OpenAI Responses API support, and peak/off-peak pricing from 2026-08-16 (api-docs.deepseek.com)
- 2026-08-13 — Docs listed DeepSeek-V4-Pro-0813: 1M context, 384k max output, OpenAI/Anthropic-compatible APIs, $0.435/M input and $0.87/M output (api-docs.deepseek.com)
