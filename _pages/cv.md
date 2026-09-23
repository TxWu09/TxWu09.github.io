---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV as PDF]({{ base_path }}/files/Tianxiang_Wu_CV_2026.pdf){: .btn .btn--primary}

Education
======
* M.S. in Computational Science and Engineering, Harvard University, Admitted — Sep 2026 – May 2028
  * Research interests: LLM reasoning, agent & multi-agent systems, applications to real-world decision-making and embodied AI
* B.S. in Mathematics & Computer Science, University of Illinois Urbana-Champaign, Aug 2022 – May 2026
  * GPA: 4.00/4.00, Graduated with Highest Honors, Dean's List
  * Relevant courses: Discrete Mathematics, Differential Equations, Abstract Linear Algebra, Numerical Analysis, Database Systems, Graph Theory, Machine Learning, Algorithms

Research Experience
======
* Feb 2025 – Apr 2026: Undergraduate Research Assistant — Schrödinger Bridge Methods for Diffusion Models
  * University of Illinois Urbana-Champaign | Advisor: Ge Liu
  * Studied Schrödinger Bridge theory and its connection to diffusion models, including entropy-regularized optimal transport and SDE-based path-space formulations
  * Built a PyTorch codebase for training generative models, implementing SDE solvers, score-network architectures, and sampling procedures
  * Ran comparative experiments across prior coupling strategies on CIFAR-10 and MNIST, evaluating sample quality via FID and qualitative inspection

* Aug 2024 – Nov 2025: Undergraduate Research Assistant — C to Rust Code Translation
  * University of Illinois Urbana-Champaign | Advisor: Reyhaneh Jabbarvand
  * Built a multi-stage AST-level preprocessing pipeline extracting CFGs and call dependencies from legacy C repositories
  * Extended pycparser and implemented a tree-sitter rewriting engine converting pointer arithmetic into safe Rust iterator patterns
  * Developed a differential fuzzing harness (cargo-fuzz) to validate translated Rust code against original C binaries for behavioral equivalence and memory safety

* Aug 2024 – Dec 2024: Researcher — Searching for Optimal Symplectic Maps
  * University of Illinois Urbana-Champaign | Advisor: Ely Kerman
  * Formulated the search for optimal symplectic transformations as a constrained optimization problem, embedding symplectic regularization into a TensorFlow loss function
  * Deployed Apache Spark with custom partitioners to distribute Hamiltonian Monte Carlo trajectory computations
  * Built an interactive visualization suite tracking phase-space orbits and Jacobian determinants across iterated maps

Internship Experience
======
* Jun 2026 – Present: AI Algorithm Engineer Intern, Envision Digital International Pte. Ltd., Shanghai, China
  * Built a ReAct-style LLM orchestration agent constructing adaptive DAG pipelines from natural-language alerts
  * Implemented a hybrid operator retriever (BM25 + dense embeddings) with a critical-path scheduler for adaptive parallelization
  * Integrated a confidence-aware fuzzy resolver and containerized the FastAPI service with Kubernetes HPA for horizontal scaling

* Nov 2025 – Feb 2026: Software Engineer Intern, Technical Consulting & Research, Inc., Champaign, IL
  * Built a Flask-based compliance assessment platform for SSP and POA&M workflows
  * Designed a provider-agnostic LLM integration layer for generating POA&M evidence artifacts
  * Modeled control and remediation data in MySQL and containerized services with Docker, adding CI checks for safer releases

* Jun 2023 – Aug 2023: Software Engineer Intern, Jiangsu Hoperun Software Co., Ltd., Nanjing, China
  * Built a data-driven automation framework using parametrized PyTest fixtures for OTA firmware hardware configurations
  * Integrated Jenkins multi-branch pipelines with Git pre-commit hooks, using Redis-backed caching and MongoDB versioned collections to cut retrieval times from 600ms to under 200ms
  * Constructed a containerized RESTful API regression suite with ephemeral per-run databases and structured JSON failure diagnostics

Skills
======
* Mathematical & Theoretical Foundations
  * Optimal Transport, Schrödinger Bridge, SDE/ODE, Stochastic Processes, Probability Theory, Functional Analysis, Linear Algebra
* Generative Modeling & Deep Learning
  * Diffusion Models, Flow Matching, Score-based Models, Energy-Based Models (EBM), Representation Learning, PyTorch, JAX, TensorFlow, Distributed Training
* Large Language Models & Agent Systems
  * LLM Alignment (RLHF/DPO), Instruction Tuning, Reasoning (CoT/ToT/Test-Time Search), RAG, Tool Use/Function Calling, Multi-Agent Collaboration, LangChain, Hugging Face Transformers
* Systems & Experimentation
  * Python, C++, Rust, Docker, Kubernetes, Distributed Computing (Spark), Experiment Tracking, pytest, Git
* Research & Analysis
  * Benchmarking & Comparative Analysis, Scientific Visualization (Matplotlib/NumPy), Automated Testing for Research Validation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Course Assistant, CS 225: Data Structures, University of Illinois Urbana-Champaign, Feb 2024 – May 2024
  * Created review notes and problem summaries to help students consolidate C++ and data structure concepts
  * Led exam review sessions covering algorithm design and code implementation
