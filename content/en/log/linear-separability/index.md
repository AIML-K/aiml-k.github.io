---
title: Linear Separability of NN-induced Embeddings
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
# - AI4Math
- Math4AI
# - LanguageModel
# - AI4Science
- conjecture
# - diary
---

<!-- How does deep neural network do wonders on hard problems?  -->
A particular case of implicit margin maximization by cross-entropy loss in supervised learning.

<!--more-->

> For connection of this to OOD (out-of-distribution) data and NNs, see [Cha and Lee 2025](https://aiml-k.github.io/publication/2025icml-hildworkshop-linsep/).

## Cross-Entropy Loss and Gradient Direction

In supervised learning for classification, we typically minimize the cross-entropy loss over model parameters {{< math >}}$\theta${{< /math >}}:

{{< math >}}$$
L = -\frac{1}{N} \sum_i \log p_\theta(y_i | x_i)
$${{< /math >}}

For a linear classifier {{< math >}}$f(x) = W^\top x${{< /math >}} with softmax outputs:

{{< math >}}$$
p_\theta(y|x) = \frac{e^{w_y^\top x}}{\sum_k e^{w_k^\top x}}
$${{< /math >}}

the loss for a single example becomes:

{{< math >}}$$
L_i = -\log \frac{e^{w_{y_i}^\top x_i}}{\sum_k e^{w_k^\top x_i}} = -w_{y_i}^\top x_i + \log\sum_k e^{w_k^\top x_i}
$${{< /math >}}

Taking the gradient with respect to the feature {{< math >}}$x_i${{< /math >}}:

{{< math >}}$$
\nabla_{x_i} L_i = -w_{y_i} + \sum_k p_\theta(k|x_i) w_k
$${{< /math >}}

This means:
- {{< math >}}$x_i${{< /math >}} is pushed toward its correct class weight vector {{< math >}}$w_{y_i}${{< /math >}}.
- {{< math >}}$x_i${{< /math >}} is pushed away from competing class weight vectors {{< math >}}$w_k${{< /math >}} proportionally to their predicted probability.

Hence, the gradient dynamics explicitly increase the projection of features onto the correct class vector and decrease projections onto incorrect ones.

## Connection to Margin Maximization

As training continues and the model approaches perfect classification (low loss regime):
- The predicted probabilities {{< math >}}$p_\theta(y_i | x_i)${{< /math >}} become highly peaked at the correct class.
- The norm of the weights {{< math >}}$||W||${{< /math >}} tends to grow (in linear models without explicit regularization).

For linearly separable data, it can be shown (Soudry et al., *Implicit Bias of Gradient Descent on Separable Data*, 2018) that:

{{< math >}}$$
w(t) / ||w(t)|| \to w^*,
$${{< /math >}}

where {{< math >}}$w^*${{< /math >}} is the maximum-margin separator — the same direction as the hard-margin SVM solution.

This happens without any explicit margin term: gradient descent on cross-entropy loss implicitly drives the weights toward a direction that maximizes the margin between classes.

## Intuitive Interpretation via Feature Geometry

Because the loss penalizes small logit differences between the true class and the most competitive false class, minimizing it encourages:

{{< math >}}$$
(w_{y_i}^\top x_i) - \max_{k \ne y_i} (w_k^\top x_i)
$${{< /math >}}

to be as large as possible — i.e., to maximize the margin between classes in logit space.

In deep networks, the same intuition extends to learned feature representations:
- Early layers adjust so that the features {{< math >}}$x_i${{< /math >}} become more linearly separable.
- Later layers (or the final linear classifier) align these features with distinct class weight vectors.

Hence, the cross-entropy gradient naturally shapes the feature space toward configurations that maximize separation between classes — even without explicit regularization enforcing it.

## Summary

| Concept | Description |
|----------|--------------|
| Mechanism | Gradient descent on cross-entropy aligns features with class vectors and repels them from others. |
| Result | Implicitly increases inter-class margins (logit separation). |
| Theoretical Support | Proven for linear models (Soudry et al., 2018) — convergence direction equals the max-margin separator. |
| Deep Learning Analogy | Network layers learn representations where classes become linearly separable in feature space. |


Take-home message is this:

> In supervised learning with cross-entropy loss, the gradient dynamics implicitly bias the model toward feature configurations that maximize class margins — analogous to seeking linear separability.


### Nice-to-read

Soudry, D., Hoffer, E., Nacson, M. S., Gunasekar, S., & Srebro, N. (2018). *The Implicit Bias of Gradient Descent on Separable Data.* Journal of Machine Learning Research, 19(70), 1–57.  

- [arXiv version](https://arxiv.org/abs/1710.10345)  
- [JMLR published version](https://jmlr.org/papers/v19/18-188.html)  
- [OpenReview](https://openreview.net/pdf?id=r1q7n9gAb)