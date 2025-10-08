---
title: Embedding of numbers
date: 2025-09-30
# type: book

# Show estimated reading time?
reading_time: true

# Show social sharing links?
share: true

# Show author profile (photo and bio) under the content?
# Edit your author profiles in the `content/authors/` folder
# Then reference their folder names with the `authors` front matter option above
profile: true

tags: 
- AI4Math
- conjecture
---

Why LLMs make silly math mistakes? This may be the biggest cause.

<!--more-->

## Introduction

Large Language Models (LLMs) treat numbers as text, not as mathematical values. 
This leads to subtle, sometimes terrible, and at the same time bewildering behavior of LLMs when it comes to prompts involving numbers, e.g. numerical reasoning.
Recall the familiar "3.11 is larger than 3.9" example?

### How Numbers Are Tokenized

LLMs process text in units called tokens — chunks of characters. Tokenization converts raw text into these tokens before feeding them to the model.

e.g.
- "1234" might be one token.
- "123456789" might become multiple tokens like "1234", "56", "789".
- "3.14159" might be tokenized as "3", ".", "141", "59".

### What Happens to Tokens

Each token is mapped to its vector embedding by LLMs. 
These embeddings capture some statistical relationships, but surely not mathematical ones.

e.g.
- "2" + "2" doesn’t “equal” "4" inside the model — it only learns that pattern from examples.
- "1000" and "1,000" have completely different embeddings.
- Large or rare numbers (like "91234875") get broken into multiple tokens and are poorly represented.

### Immediate Consequences

Considering LLMs' pure form (nonlinear token-embedder whose parameters minimize empirical risks), we can guess some immediate shortcomings of LLMs:

- The stochastic "parrot": LLMs don’t do arithmetic — they rely on pattern matching.
- Limited scalability: They can generalize to familiar numbers, but not to rare ones (e.g. large or unseen numbers).
- Weak numeric reasoning: Counting, comparison, and multi-step calculations are error-prone (without external tools).


## Conjecture 1

> It is possible to construct embedding in which the numerical nature of numbers are "preserved", up to some finite precision.

Consider how real numbers are represented approximately in computers; also consider that some numbers require infinitely many digits to write them down directly. 

Defining "preserved" will drive a series of subsequent research. 

### Variant 1a

> There is such an embedding that does not require training (or "learning" per se). 

cf. p-adic numbers (how to truncate this?)

### Variant 1b

> Such embedding allows efficient arithmetics, and if possible, controllable approximations of exact arithmetics.

cf. Hansel's p-adic arithmetics. https://dx.doi.org/10.1137%2F0208011


## Conjecture 2

> With embedding that preserves the nature of numbers, LLMs (or, more fundamentally, stacked transformers) will have better performance in tasks involving numbers.

### Variant 2a

> With such embedding, learning will be faster.

### Variant 2b

> With such embedding, generalization will be more prevalent.




<!-- 글쓰기 관련 참조: https://bootstrap.hugoblox.com/content/writing-markdown-latex/ 

마크다운인데, 뭔가 더 들어가있다.


## Heading 2
### Heading 3
#### Heading 4

Italics with _underscores_.

Bold with **asterisks**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough with ~~two tildes~~. -->
