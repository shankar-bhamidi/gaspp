---
title: "Schedule"
---

# Schedule (living)

Official announcements/submissions are via **Canvas**.   This page is the “living” schedule with links (e.g., Dropbox) to slides, notes, and readings.

| Date | Topic | Materials |
|---|---|---|
| 2026-01-08 (Thu) | Intro to course. Class expectations.  | Slides: [Lecture 1](https://www.dropbox.com/scl/fi/53dz0xelclaw1qjih31eg/Lecture_1_syllabus.pdf?rlkey=t1wlln53pur6pfmdx555glg4g&dl=0) Reading: [notes](#2026-01-08-reading)  |
| 2026-01-13 (Tue) |  |  |
| 2026-01-15 (Thu) |  |  |
| 2026-01-20 (Tue) |  |  |
| 2026-01-22 (Thu) |  |  |
| 2026-01-27 (Tue) |  |  |
| 2026-01-29 (Thu) |  |  |
| 2026-02-03 (Tue) |  |  |
| 2026-02-05 (Thu) |  |  |
| 2026-02-10 (Tue) |  |  |
| 2026-02-12 (Thu) |  |  |
| 2026-02-17 (Tue) |  |  |
| 2026-02-19 (Thu) |  |  |
| 2026-02-24 (Tue) |  |  |
| 2026-02-26 (Thu) |  |  |
| 2026-03-03 (Tue) |  |  |
| 2026-03-05 (Thu) |  |  |
| 2026-03-10 (Tue) |  |  |
| 2026-03-12 (Thu) |  |  |


# Detailed reading

### 2026-01-08 reading

<a id="2026-01-08-reading"></a>

**Suggested reading and additional resources:**

- [Machine learning street talk Podcast with Chris Bishop](https://www.youtube.com/watch?v=kuvFoXzTK3E). Some key takeaways:
  
    + **Fundamental importance of probability theory:** Across the podcast, Bishop emphasizes that probability theory is the foundational language of machine learning because the subject is inherently about learning from data under uncertainty. He argues that once you take uncertainty seriously and want a quantitative framework, you are naturally led to probability, and he presents it as the conceptual bedrock for how to think about modeling, prediction, and learning. In that spirit, *he’s direct about advice to students: he recommends they invest seriously in learning probability, and he says you can’t really work in machine learning without understanding it*. He also acknowledges that modern practice often relies on scalable approximations, point estimates and stochastic gradient methods, yet he treats probability theory as the guiding framework that explains what those procedures are trying to do and how to interpret their outputs, including uncertainty and generalization. He highlights probability theory as a unifying lens across seemingly different methods, noting that algorithms like hidden Markov models and Kalman filters can be derived from the same basic probability rules and graphical factorization ideas. Stepping back, Bishop suggests that part of the maturation of the field has been a shift toward a more probabilistic and statistical perspective, with probability theory providing a durable bedrock for clear thinking even as models and compute continue to evolve.
    + **Mysteries of stochastic gradient descent:** Bishop points out that modern deep learning overturns a core statistical intuition: in earlier machine learning and in classical statistics, fitting models with far more parameters than data points seems obviously unreasonable. Bishop notes that, nevertheless, overparameterized neural networks often drive the training error to zero while the test error continues to improve. Bishop argues that this behavior suggests generalization is not explained simply by “minimize a loss and reach a global optimum.” Because there are many global minima with zero training error, some that overfit and others that generalize. Bishop emphasizes that the training dynamics, especially the implicit bias of stochastic gradient descent, appear to play a central role in selecting good solutions. Bishop concludes that explaining why these systems work so well remains an important open research problem.
    + **Magic of information theory:** Bishop also highlights what feels like the “magic of information theory”: when neural networks are trained to compress human language—i.e., to represent and predict it efficiently, they unexpectedly acquire the ability to behave like “reasoning engines.” He frames this as a genuine surprise to the field: a compression-driven objective can produce emergent reasoning capability rather than merely better text prediction.

---

## Spring 2026 — Tentative plan at the start of the semester (subject to change)

| Date | Topic | Materials |
|---|---|---|
| 2026-01-08 (Thu) | Intro to course. Class expectations. | Slides: [link](https://www.dropbox.com/scl/fi/53dz0xelclaw1qjih31eg/Lecture_1_syllabus.pdf?rlkey=t1wlln53pur6pfmdx555glg4g&dl=0) · Notes: [link]() |
| 2026-01-13 (Tue) | BPE / N-grams / vector semantics / representation learning | Slides: [link](https://www.dropbox.com/scl/fi/53dz0xelclaw1qjih31eg/Lecture_1_syllabus.pdf?rlkey=t1wlln53pur6pfmdx555glg4g&dl=0) · Reading: [link]() |
| 2026-01-15 (Thu) | Information theory: cross-entropy loss and MLE | Slides: [link](https://www.dropbox.com/scl/fi/k6ghcjau38xcjyn016hv0/Lecture_2.pdf?rlkey=11gpvejc1n8y00pte722gyqu8&dl=0) · Reading: [link]() |
| 2026-01-20 (Tue) | AEP, ergodic theory, Shannon–McMillan–Breiman | Slides: [link](https://www.dropbox.com/scl/fi/k6ghcjau38xcjyn016hv0/Lecture_2.pdf?rlkey=11gpvejc1n8y00pte722gyqu8&dl=0) · Reading: [link]() |
| 2026-01-22 (Thu) | Markov chains for text; stochastic gradient descent | Slides: [link](https://www.dropbox.com/scl/fi/khrq3bhos4giilv43lgzn/Lecture_3.pdf?rlkey=w0eipwrh57l71ew5kd3hgv9x0&dl=0) · Reading: [link]() |
| 2026-01-27 (Tue) | SGD in low and high dimensions | Slides: [link](https://www.dropbox.com/scl/fi/zmr4qeqxdxlezp8tlgchc/Lecture_4.pdf?rlkey=09um96ibg3z6pmpqigd43h751&dl=0) · Reading: [link]() |
| 2026-01-29 (Thu) | SGD continued: neural networks | Slides: [link](https://www.dropbox.com/scl/fi/zmr4qeqxdxlezp8tlgchc/Lecture_4.pdf?rlkey=09um96ibg3z6pmpqigd43h751&dl=0) · Reading: [link]() |
| 2026-02-03 (Tue) | Transformers, attention | Slides: [link]() · Reading: [link]() |
| 2026-02-05 (Thu) | Transformers, attention (cont.) | Slides: [link]() · Reading: [link]() |
| 2026-02-10 (Tue) | Transformers and interacting particle systems | Slides: [link]() · Reading: [link]() |
| 2026-02-12 (Thu) | Prompting as conditioning; RLHF | Slides: [link]() · Reading: [link]() |
| 2026-02-17 (Tue) | Influence functions; superconcentration; propagation of chaos | Slides: [link]() · Reading: [link]() |
| 2026-02-19 (Thu) | Interlude: graph rep learning; spectral clustering | Slides: [link]() · Reading: [link]() |
| 2026-02-24 (Tue) | Interlude: graph neural networks | Slides: [link]() · Reading: [link]() |
| 2026-02-26 (Thu) | Latent variables I: K-means and EM | Slides: [link]() · Reading: [link]() |
| 2026-03-03 (Tue) | Latent variables II: VI & ELBO; score matching | Slides: [link]() · Reading: [link]() |
| 2026-03-05 (Thu) | GANs and autoencoders | Slides: [link]() · Reading: [link]() |
| 2026-03-10 (Tue) | GANs and autoencoders II | Slides: [link]() · Reading: [link]() |
| 2026-03-12 (Thu) | Diffusion models I | Slides: [link]() · Reading: [link]() |

---



