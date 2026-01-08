---
title: "Schedule"
---

# Schedule (living)

Official announcements/submissions are via **Canvas**.   This page is the “living” schedule with links (e.g., Dropbox) to slides, notes, and readings.

| Date | Topic | Materials |
|---|---|---|
| 2026-01-08 (Thu) | Intro to course. Class expectations. BPE Tokenization. | Slides: [Lecture 1, P1-49](https://www.dropbox.com/scl/fi/mvjeb6kbomjx8t2oa1970/Lecture_1_syllabus.pdf?rlkey=5caej7vjr6m4i6q8mxcw83u7c&dl=0) Reading: [notes](#2026-01-08-reading)  |
| 2026-01-13 (Tue) |  |Slides:[]()  Reading: [notes](#2026-01-13-reading) |
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

## 2026-01-08 reading

<a id="2026-01-08-reading"></a>

### Material covered in the lecture

- Lecture 1, slides 1-49.
- [Jurafsky and Martin, Chapter 2, Sec 2.1, 2.2, 2.4](https://web.stanford.edu/~jurafsky/slp3/)

### Suggested reading and additional resources

- [Machine learning street talk Podcast with Chris Bishop](https://www.youtube.com/watch?v=kuvFoXzTK3E). Some key takeaways:
  
    + **Fundamental importance of probability theory:** Across the podcast, Bishop emphasizes that probability theory is the foundational language of machine learning because the subject is inherently about learning from data under uncertainty. He argues that once you take uncertainty seriously and want a quantitative framework, you are naturally led to probability, and he presents it as the conceptual bedrock for how to think about modeling, prediction, and learning. In that spirit, *he’s direct about advice to students: he recommends they invest seriously in learning probability, and he says you can’t really work in machine learning without understanding it*. He also acknowledges that modern practice often relies on scalable approximations, point estimates and stochastic gradient methods, yet he treats probability theory as the guiding framework that explains what those procedures are trying to do and how to interpret their outputs, including uncertainty and generalization. He highlights probability theory as a unifying lens across seemingly different methods, noting that algorithms like hidden Markov models and Kalman filters can be derived from the same basic probability rules and graphical factorization ideas. Stepping back, Bishop suggests that part of the maturation of the field has been a shift toward a more probabilistic and statistical perspective, with probability theory providing a durable bedrock for clear thinking even as models and compute continue to evolve.
    + **Mysteries of stochastic gradient descent:** Bishop points out that modern deep learning overturns a core statistical intuition: in earlier machine learning and in classical statistics, fitting models with far more parameters than data points seems obviously unreasonable. Bishop notes that, nevertheless, overparameterized neural networks often drive the training error to zero while the test error continues to improve. Bishop argues that this behavior suggests generalization is not explained simply by “minimize a loss and reach a global optimum.” Because there are many global minima with zero training error, some that overfit and others that generalize. Bishop emphasizes that the training dynamics, especially the implicit bias of stochastic gradient descent, appear to play a central role in selecting good solutions. Bishop concludes that explaining why these systems work so well remains an important open research problem.
    + **Magic of information theory:** Bishop also highlights what feels like the “magic of information theory”: when neural networks are trained to compress human language—i.e., to represent and predict it efficiently, they unexpectedly acquire the ability to behave like “reasoning engines.” He frames this as a genuine surprise to the field: a compression-driven objective can produce emergent reasoning capability rather than merely better text prediction.

- [Andrej Karpathy on Dwarkesh podcast](https://www.dwarkesh.com/p/andrej-karpathy): deep thinker and expert in this general area. One thing I am still wrapping my head around are his views on reinforcement learning and its role in training LLMs. I know very little about this general area. His take is as follows: Karpathy argues that reinforcement learning plays only a limited and deeply flawed role in the development of large language models. His core critique is that RL relies on an extremely weak learning signal: a single scalar reward assigned after a long trajectory of actions, which is then indiscriminately propagated backward across every step. This creates noisy credit assignment, where incorrect reasoning steps are reinforced as long as the final outcome happens to be correct. He describes this as “sucking supervision through a straw” and views it as a statistically inefficient and conceptually misguided approach. In contrast to humans, who reflect selectively, revise mistakes, and attribute credit unevenly, RL blindly upweights entire trajectories. As a result, RL does not capture how reasoning or learning actually works and produces brittle improvements rather than genuine gains in intelligence. At the same time, Karpathy emphasizes that imitation learning and pretraining were far more surprising and impactful breakthroughs than reinforcement learning. Fine-tuning pretrained models on human demonstrations quickly transformed autocomplete systems into useful assistants while preserving their knowledge. Reinforcement learning, such as RLHF, provides incremental benefits like preference shaping and modest hill climbing when correct answers exist, but it does not solve reasoning, planning, or continual learning. Attempts to improve RL through process-based supervision run into severe problems because automated judges are gameable and lead to adversarial behavior, where models exploit reward models without improving correctness. Karpathy believes progress will require fundamentally new training paradigms involving reflection, selective credit assignment, memory, and distillation, rather than simply scaling RL, and he does not see reinforcement learning as the main path toward general intelligence. I guess only time will tell where we stand on these debates. While the above podcast goes into lots of other topics, in the specific setting of reinforcement learning, it seems to follow a previous podcast by another great researcher [Richard Sutton](https://www.dwarkesh.com/p/richard-sutton). I have not had the time to dive into this second podcast yet. 


## 2026-01-13 reading

<a id="2026-01-13-reading"></a>

### Material covered in the lecture

### Suggested reading and additional resources


---

## Spring 2026 — Tentative plan at the start of the semester (subject to change)

| Date | Topic | Materials |
|---|---|---|
| 2026-01-08 (Thu) | Intro to course. Class expectations. | Slides: [link](https://www.dropbox.com/scl/fi/53dz0xelclaw1qjih31eg/Lecture_1_syllabus.pdf?rlkey=t1wlln53pur6pfmdx555glg4g&dl=0) · Notes: [link]() |
| 2026-01-13 (Tue) | BPE / N-grams / vector semantics / representation learning | Slides: [link](https://www.dropbox.com/scl/fi/53dz0xelclaw1qjih31eg/Lecture_1_syllabus.pdf?rlkey=t1wlln53pur6pfmdx555glg4g&dl=0) · Reading: [link]() |
| 2026-01-15 (Thu) | Information theory: cross-entropy loss and MLE | Slides: [link](https://www.dropbox.com/scl/fi/16rlm3ww97rq91my5y8eg/Lecture_2.pdf?rlkey=3enqjuzi1wtczyrnqnuu07ga8&dl=0) · Reading: [link]() |
| 2026-01-20 (Tue) | AEP, ergodic theory, Shannon–McMillan–Breiman | Slides: [link](https://www.dropbox.com/scl/fi/16rlm3ww97rq91my5y8eg/Lecture_2.pdf?rlkey=3enqjuzi1wtczyrnqnuu07ga8&dl=0) · Reading: [link]() |
| 2026-01-22 (Thu) | Markov chains for text; stochastic gradient descent | Slides: [link](https://www.dropbox.com/scl/fi/gh7pps0a02aotst33ctsf/Lecture_3.pdf?rlkey=0fz1qwm7zd13ftt5la7g755q9&dl=0) · Reading: [link]() |
| 2026-01-27 (Tue) | SGD in low and high dimensions | Slides: [link](https://www.dropbox.com/scl/fi/j0ax8g5wdft4f7yhkooh4/Lecture_4.pdf?rlkey=nzovwmxqtburkiaunlvp1ougt&dl=0) · Reading: [link]() |
| 2026-01-29 (Thu) | SGD continued: neural networks | Slides: [link](https://www.dropbox.com/scl/fi/j0ax8g5wdft4f7yhkooh4/Lecture_4.pdf?rlkey=nzovwmxqtburkiaunlvp1ougt&dl=0) · Reading: [link]() |
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



