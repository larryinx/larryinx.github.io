---
layout: post
date: 2025-10-17 00:00:00-0400
inline: true
related_posts: false
---

📌 New preprint: [TokDrift: When LLM Speaks in Subwords but Code Speaks in Grammar](https://arxiv.org/abs/2510.14972) is now available on arXiv!

1️⃣ LLMs' subword tokenizers don't align well with programming language grammar: tiny whitespace or renaming tweaks -> different tokenization -> flipped outputs.

2️⃣ Our framework TokDrift systematically tests 9 code LLMs on 3 tasks, showing their sensitivity to tokenization changes: up to 60% outputs change under a single semantic-preserving rewrite.

3️⃣ If your win margin is ~1 pp, beware: spacing & naming can swing results.