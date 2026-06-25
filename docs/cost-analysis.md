Context usage: ~63.5K tokens used
Calculated with repomix: total tokens = 8485 tokens
Based on the cursor usage page:
- cache read: 368736 tokens
- cache write: 0
- input: 52955 tokens
- output: 6023 tokens
- total: 427714 tokens
Model: Composer 2.5 Fast

Price: (368_736 + 52_955) / 1_000_000 * 3 + 6023 / 1_000_000 * 15 = 0.25$

Conclusions:
- caveman is a handy skill to reduce LLM's output tokens without sacrafising clarity
- to get a desired result from LLM, you should provide it a valid context (role, examples, requirements, guardrails etc.)
- LLM's output worsens once its context gets filled up