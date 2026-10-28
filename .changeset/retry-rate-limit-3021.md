---
"workers-ai-provider": patch
"@cloudflare/tanstack-ai": patch
---

Treat the Workers AI rate-limit error `3021` (inference requests per minute) as HTTP 429, so binding errors with that code are retryable.
