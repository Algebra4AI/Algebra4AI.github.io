---
title: Home
---

{% include figure.html img="image.png" alt="tutorial logo" width="80%" %}

# When and where?

TBD

# Outline

This tutorial explores how advanced algebraic structures—such as C*-algebras, Lie groups, category theory, and tensor networks—can enhance machine learning by improving model efficiency, interpretability, and generalization. Moving beyond standard linear algebra, we present operator-algebraic tools for analyzing structured data, symmetry-based methods for learning distributions on manifolds, categorical frameworks for representation learning and reinforcement learning, and tensor networks for efficient computation. Designed for AI researchers and practitioners with a solid foundation in linear algebra and ML, the tutorial combines theoretical insights with practical applications, covering recent developments across kernel methods, neural networks, probabilistic modeling, and quantum AI.

# Agenda

- **Introduction: Why Algebra in AI?** `(Speaker: Chao, 20 min)`
  - Motivation: The role of algebra in modern AI
  - Overview of algebraic structures and their impact on ML

- **C*-Algebraic Machine Learning** `(Speaker: Yuka, 50 min)`
  - Basics of C*-algebra
  - C*-algebra and kernel methods
  - C*-algebra and neural networks

- **Lie Groups and Distributions** `(Speaker: Mehmet, 50 min)`
  - Lie group actions on parameter spaces
  - Families of distributions with group symmetries
  - Learning via group representations

- **Category Theory in Machine Learning** `(Speaker: Yivan, 50 min)`
  - Basic category theory and diagrammatic reasoning
  - F-algebras and homomorphisms in machine learning
  - Universal constructions in representation learning
  - Recursive structures in reinforcement learning

- **Tensor Algebra in Machine Learning** `(Speaker: Chao, 40 min)`
  - Basic tensor algebra and tensor networks  
  - Applications in quantum(-inspired) ML

# Prerequisite knowledge 

This tutorial targets junior AI/ML researchers (particularly students) and practitioners interested in algebraic foundations of AI. Basic background in linear algebra is recommended. No prior knowledge of abstract algebra, topology, or representation theory is required.

# Materials

You can find the slides of the tutorial here.

# Speakers and presentation details

<div id="speakers">
    <div class="speaker">
        <img class="avatar" src="https://www.rd.ntt/_assets/img/organization/researcher/special/s_083.jpg"><br/>
        <div class="speaker-name">
        <b>Yuka Hashimoto</b></div>
        <div class="speaker-uni">
        <i> NTT, RIKEN-AIP</i>
        </div>
    </div>
    <div class="speaker">
        <img class="avatar" src="https://ekiral.github.io/mehmetMoma.jpg"><br/>
        <div class="speaker-name">
        <b>Eren Mehmet Kiral</b></div>
        <div class="speaker-uni">
        <i> Keio University, RIKEN-AIP</i>
        </div>
    </div>
    <div class="speaker">
        <img class="avatar" src="https://chaoliatriken.github.io/images/chaoli.jpg"><br/>
        <div class="speaker-name">
        <b>Chao Li</b></div>
        <div class="speaker-uni">
        <i> RIKEN-AIP</i>
        </div>
    </div>
    <div class="speaker">
        <img class="avatar" src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=Q7S9kh4AAAAJ&citpid=1"><br/>
        <div class="speaker-name">
        <b>Yivan Zhang</b></div>
        <div class="speaker-uni">
        <i> RIKEN-AIP</i>
        </div>
    </div>
</div>

---

## Title: C*-algebra for Machine Learning

**Speaker:** [**Yuka Hashimoto**](https://www.rd.ntt/e/organization/researcher/special/s_083.html) 

**Abstract:** We explore the applicability of C\*-algebra to machine learning methods. We first review fundamental notions regarding C\*-algebra and how it can be related to machine learning methods. We then show that C*-algebraic techniques are useful in analyzing structured data such as functional data and image data by focusing on kernel methods and neural networks. The theory of C\*-algebras enables us to go beyond existing methods by using tools related to functions and operators.

**Biography:** Yuka Hashimoto is a Distinguished Researcher at Nippon Telegraph and Telephone Corporation (NTT), Tokyo, Japan. Additionally, she holds a position as a Visiting Scientist at RIKEN Center for Advanced Intelligence Project (AIP) and Visiting Associate Professor at Kanazawa University. She obtained her Ph.D. in science in March 2022. Her research interests lie in the intersection of mathematical theory, particularly operator and operator algebra theories, with machine learning methods such as kernel methods and neural networks. She recentry published a position paper that explores the applicability of C*-algebra to machine learning.

---

## Title: Lie groups and Distributions in Machine Learning

**Speaker:** [**Eren Mehmet Kıral**](https://ekiral.github.io)

**Abstract:**  We introduce basics of Lie Groups, Statistical Manifolds to introduce how they can be used to learn parameter distributions on manifolds. On top of a specific application of Lie group methods, we will also give the general philosophy and the intuition behind using such mathematical tools so that the participants can use them in their own work. 

**Biography:** Eren Mehmet Kıral received his Ph.D. in mathematics from Brown University, specializing in analytic number theory, particularly the distribution of prime numbers via the Riemann zeta function and related analytic techniques. He has taught university-level courses at Brown and Texas A&M University on subjects including calculus, linear algebra, and cryptography. He also regularly teaches week-long crash courses at the Mathematics Village in İzmir, Turkey. A shorter tutorial on cryptography he gave at RIKEN is available at: https://github.com/ekiral/cryptography. As a RIKEN Special Postdoctoral Researcher (2020--2023), his research expanded into machine learning, with a focus on incorporating Lie group symmetries into learning algorithms. His work “Lie Group Bayesian Learning Rule” (AISTATS 2023) explores learning distributions on parameter spaces via Lie group actions. He is currently a postdoctoral researcher at Keio University.

---

## Title: Algebraic Structures in Representation Learning and Reinforcement Learning

**Speaker:** [**Yivan Zhang**](https://yivan.xyz)

**Abstract:** This tutorial explores how tools from **category theory** provide powerful abstractions for understanding and designing machine learning systems. We begin with an introduction to basic category-theoretic concepts and diagrammatic reasoning, building intuition for how structure and compositionality emerge in machine learning. We then introduce **endofunctor algebras** and their **homomorphisms** as tools for capturing structure in learning tasks. Next, we show how **universal constructions** can formalize goals in _representation learning_, such as disentanglement and invariance. Finally, we use **recursive structures** to model the generation and aggregation of rewards in _reinforcement learning_, enabling more flexible control of agent behavior. The tutorial aims to bridge abstract mathematical tools and concrete machine learning challenges, offering a unified language for modularity, generalization, and interpretability.

**Biography:** Yivan Zhang is an assistant professor at the University of Tokyo and a visiting scientist at the RIKEN Center for Advanced Intelligence Project (AIP). He received his Ph.D. in computer science from the University of Tokyo in 2024. His research applies **algebra, logic, and category theory** to develop theoretical foundations and practical algorithms for complex machine learning problems. His recent work explores applications of algebraic structures such as _monoidal products_, _algebra homomorphisms_, and _recursive coalgebras_ in disentangled representation learning and value-based reinforcement learning.

---

## Title: Tensor Algebra in Machine Learning: Efficient Modeling from Structure to Computation

**Speaker:** [**Chao Li**](https://chaoliatriken.github.io/)

**Abstract:** This session introduces tensor algebra and tensor networks as powerful tools for scalable and structured machine learning. We cover core concepts in tensor decomposition and network architectures (e.g., MPS, TTN), emphasizing low-rank modeling for efficient computation and data representation. Applications span quantum machine learning and foundation models, where tensor methods enable compact, expressive architectures with improved generalization. The tutorial blends theoretical foundations with practical insights, equipping participants to integrate tensor-based approaches into modern AI systems.

**Biography:** Chao Li is a research scientist at the RIKEN Center for Advanced Intelligence Project (AIP), holding an indefinite-term position in the Tensor Learning Team. He received his Ph.D. in Communication Engineering from Harbin Engineering University in 2017. His research focuses on tensor network methods, low-rank modeling, and quantum-inspired machine learning, with applications in efficient representation, structure search, and probabilistic inference. He has published many papers on tensor networks at top venues including ICML, NeurIPS, ICLR, CVPR, AAAI, and AISTATS, and has been invited to give keynote and tutorial talks on tensor methods at several international workshops. Chao currently teaches “Tensor Networks in Machine Learning” as an adjunct lecturer at the University of Tokyo and has led multiple national research projects in Japan. 

# Recommended reading

- Hashimoto, Yuka, Masahiro Ikeda, and Hachem Kadri. "Position: C* -Algebraic Machine Learning - Moving in a New Direction." *Forty-first International Conference on Machine Learning.* 2024.
- Zhang, Yivan, and Masashi Sugiyama. "[A Category-theoretical Meta-analysis of Definitions of Disentanglement](https://proceedings.mlr.press/v202/zhang23ak.html)." *International Conference on Machine Learning.* 2023.
- Zhang, Yivan, and Masashi Sugiyama. "[Enriching Disentanglement: From Logical Definitions to Quantitative Metrics](https://proceedings.neurips.cc/paper/2024/hash/84409c45a0defe347c895b004b1c675b-Abstract.html)." *Neural Information Processing Systems.* 2024.
- Tang, Yuting, et al. "[Recursive Reward Aggregation](https://openreview.net/forum?id=13lUcKpWy8)." *Reinforcement Learning Conference.* 2025.
- Kıral, Eren Mehmet. "Bayesian Learning with Lie Groups." *Statistical Theories and Machine Learning Using Geometric Methods:* 17.
- Kolda, Tamara G., and Brett W. Bader. "Tensor decompositions and applications." *SIAM review* 51.3 (2009): 455-500.

# Further reading

## Category theory

- \[textbook\] Mac Lane, Saunders. _Categories for the working mathematician_. Vol. 5. Springer Science & Business Media, 1998.
- \[textbook\] Awodey, Steve. _Category theory_. Vol. 52. Oxford University Press, 2010.
- \[blog\] Tai-Danae Bradley. Illustrative blog articles in [Math3ma](https://www.math3ma.com/categories/category-theory).

## Applied category theory in machine learning

- \[book\] Fong, Brendan, and David I. Spivak. "[An Invitation to Applied Category Theory: Seven Sketches in Compositionality](https://arxiv.org/abs/1803.05316)". Cambridge University Press, 2019.
- \[review paper\] Shiebler, Dan, Bruno Gavranović, and Paul Wilson. "[Category theory in machine learning](https://arxiv.org/abs/2106.07032)." 2021.
- \[position paper\] Gavranović, Bruno, et al. "[Position: Categorical Deep Learning is an Algebraic Theory of All Architectures](https://proceedings.mlr.press/v235/gavranovic24a.html)." *International Conference on Machine Learning.* 2024.
- \[GitHub repository\] [Category Theory ∩ Machine Learning](https://github.com/bgavran/Category_Theory_Machine_Learning)
- \[lecture series\] [Categories for AI](https://cats.for.ai/)
