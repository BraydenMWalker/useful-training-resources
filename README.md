# Cloud Native & Agentic AI Resources

A curated collection of training, articles, and community resources for engineers working at the intersection of cloud native infrastructure and agentic AI. Whether you're deploying AI workloads on Kubernetes, building LLM-powered applications, or preparing for CNCF certifications, these resources cover the spectrum from foundational concepts to production-grade implementation.

---

## Large Language Models & Generative AI

### Free Resources

- [fast.ai – Practical Deep Learning for Coders](https://www.fast.ai/) – Free, practitioner-focused deep learning courses built around real-world projects.
- [DeepLearning.AI Specializations](https://www.deeplearning.ai/) – Andrew Ng's foundational and advanced AI/ML specializations; the Generative AI with LLMs course is particularly relevant.
- [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course) – Hands-on NLP and Transformers course using the Hugging Face ecosystem.
- [LangChain Academy](https://academy.langchain.com/) – Free courses on building LLM-powered applications with LangChain and LangGraph.
- [Prompt Engineering Guide](https://www.promptingguide.ai/) – Comprehensive guide to prompt engineering techniques, patterns, and best practices for LLMs.
- [MLAbonne – LLM Course](https://github.com/mlabonne/llm-course) – GitHub-hosted course covering LLM fundamentals, training, fine-tuning, alignment, RAG, and deployment using modern open-source tooling.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) – Covers the full lifecycle of building and deploying ML-powered products, from training to production serving.
- [Kaggle Learn](https://www.kaggle.com/learn) – Free bite-sized micro-courses on ML, deep learning, NLP, and feature engineering.
- [Andrej Karpathy – Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) – YouTube series building neural networks and GPT from scratch in Python; essential for understanding LLM internals.

### Articles & Deep Dives

- [The Reasoning Revolution: Test-Time Scaling for LLMs](https://rx-m.com/the-algorithmic-7-reasoning-revolution-test-time-scaling-for-llms/) – Overview of how test-time compute scaling enables models to "think longer" at inference time, and what that means for agentic workloads.
- [Digital Babel: LLM Agent Protocols](https://rx-m.com/the-algorithmic-8-digital-babel-llm-agent-protocols/) – Technical breakdown of MCP, A2A, and other emerging protocols for inter-agent communication and tool access.
- [Challenges in Agentic AI](https://rx-m.com/agentic-ai-part-3-challenges-in-agentic-ai/) – Candid exploration of LLM reliability problems, infrastructure immaturity, talent gaps, and the gap between agentic AI hype and production reality.

### Commercial Instructor-Led Courses

- [Developing Applications with Generative AI](https://rx-m.com/training/developing-applications-with-generative-ai/) – Three-day comprehensive introduction to generative AI application development for engineers.
- [LLM Fine Tuning Introduction](https://rx-m.com/training/llm-fine-tuning-introduction/) – One-day fast-paced overview of lightweight fine-tuning techniques for large language models.
- [LLM Prompt Engineering (LFS401 – Linux Foundation)](https://training.linuxfoundation.org/training/gen-ai-prompt-engineering-rxm401/) – One-day practical course on prompt engineering techniques.
- [Machine Learning & AI Introduction (LFS402 – Linux Foundation)](https://training.linuxfoundation.org/training/machine-learning-ai-intro-rxm402/) – One-day hands-on introduction to machine learning and AI fundamentals.

---

## Retrieval Augmented Generation (RAG) & Context Engineering

### Free Resources

- [Retrieval Augmented Generation Introduction (LFS403 – Linux Foundation)](https://training.linuxfoundation.org/training/retrieval-augmented-generation-rag-intro-rxm403) – One-day practical introduction to the basics of building a RAG system.

### Commercial Instructor-Led Courses

- [Context Engineering Foundation](https://rx-m.com/training/context-engineering-foundation/) – Two-day hands-on course covering context design as a first-class system: instruction hierarchies, RAG pipelines, memory strategies, and avoiding hallucination and prompt injection failures.
- [Retrieval Augmented Generation (RAG) Foundation](https://rx-m.com/training/retrieval-augmented-generation-rag-foundation/) – Three-day project-based deep dive from RAG fundamentals to production-grade deployment with evaluation, guardrails, caching, and CI/CD.

---

## Agentic AI Systems & Design Patterns

### Free Resources

- [Challenges in Agentic AI](https://rx-m.com/agentic-ai-part-3-challenges-in-agentic-ai/) – Detailed look at real-world obstacles facing agentic AI: LLM unreliability, infrastructure immaturity, and the human talent gap.
- [Digital Babel: LLM Agent Protocols](https://rx-m.com/the-algorithmic-8-digital-babel-llm-agent-protocols/) – Analysis of the emerging need for standardized agent communication protocols to prevent siloed AI ecosystems.

### Commercial Instructor-Led Courses

- [Agentic Design Patterns](https://rx-m.com/training/agentic-design-patterns/) – Three-day immersive workshop covering pipeline, routing, parallelization, reflection, tool use, and multi-agent collaboration patterns using LangChain, LangGraph, Crew AI, OpenAI, and Google ADK.
- [Agentic Development with LangChain](https://rx-m.com/training/agentic-development-with-langchain/) – Hands-on course for building agentic workflows with the LangChain ecosystem.
- [Developing Multi-Agent AI Systems](https://rx-m.com/training/developing-multi-agent-ai-systems/) – Course focused on designing and building systems where multiple AI agents coordinate to accomplish complex goals.
- [Transforming the SDLC with AI](https://rx-m.com/training/transforming-the-sdlc-with-ai/) – Two-day hands-on introduction to AI-augmented software development processes and engineering practices.

---

## Kubernetes Fundamentals

### Free Resources

- [Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/) – Official interactive tutorial: deploy, explore, scale, and perform rolling updates on a Kubernetes cluster.
- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) – Community-driven walkthrough for building a cluster from scratch; invaluable for understanding what Kubernetes is actually doing under the hood.
- [Kubernetes Resources Hub](https://rx-m.com/k8s-resources/) – Curated short tutorials and video explainers covering Pods, Deployments, Services, RBAC, Persistent Volumes, ConfigMaps, and more. Especially useful for CKAD/CKA preparation.
- [Kubebyexample](https://kubebyexample.com/) – Community example repository demonstrating common deployment, service, probe, and configuration patterns.
- [KillrCoda](https://killercoda.com/) – Browser-based interactive scenarios for CKAD, CKA, CKS, Argo, Istio, Cilium, and more — no local setup required.
- [Introduction to Kubernetes (LFS158 – edX)](https://www.edx.org/course/introduction-to-kubernetes) – Free video course from the Linux Foundation covering Kubernetes fundamentals over 16 chapters.
- [CKAD Self-Study Course](https://rx-m.com/ckad-online-self-study-training-certification/) – Free self-study course aligned to CKAD objectives with application-focused labs.
- [CKA Self-Study Course](https://rx-m.com/cka-online-training/) – Free self-study pathway focused on CKA domains and exam readiness.
- [CKS Self-Study Course](https://rx-m.com/cks-self-study-course/) – Free self-study security course covering hardening, runtime controls, and detection.

### Commercial Instructor-Led Courses

- [Kubernetes Advanced for Operators](https://rx-m.com/training/kubernetes-for-ops/) – In-depth coverage of Kubernetes operations, scheduling, networking, security, and observability.
- [Kubernetes Fundamentals (LFS258 – Linux Foundation)](https://training.linuxfoundation.org/training/kubernetes-fundamentals/) – Linux Foundation video course building administrator fundamentals, labs, and troubleshooting skills.
- [Kubernetes for Developers (LFD259 – Linux Foundation)](https://training.linuxfoundation.org/training/kubernetes-for-developers/) – Linux Foundation developer course covering workloads, networking, storage, and debugging.

---

## AI & ML on Kubernetes

### Hobbyist Projects & Tutorials

- [SkyPilot: AI on Kubernetes Without the Pain](https://blog.skypilot.co/ai-on-kubernetes/) – Practical overview of running AI training and inference workloads on Kubernetes.
- [Deploying Local AI Agents in Kubernetes](https://www.cloudnativedeepdive.com/deploying-local-ai-agents-in-kubernetes/) – Guide for running local AI agents inside a Kubernetes environment.
- [Build Your Own Private ChatGPT with Kubernetes and Ollama](https://dev.to/romulofrancas/unlock-the-future-build-your-own-private-chatgpt-in-30-minutes-with-kubernetes-ollama-and-1npp) – Hobbyist-friendly project for building a private LLM setup on K3s using Ollama.
- [Ollama Kubernetes Deployment: Cost-Effective and Secure](https://mykubert.com/blog/ollama-kubernetes-deployment-cost-effective-and-secure/) – Practical guide for deploying Ollama on Kubernetes with attention to security and cost.
- [Your Own AI Cloud: Deploying AI Models in a Kubernetes Homelab](https://www.youtube.com/watch?v=_v0qhWc1qJ0) – Video walkthrough for building an AI-serving homelab on Kubernetes.
- [Building a cheap AI/ML machine to run on a homelab Kubernetes cluster](https://ianbelcher.me/tech-blog/building-a-cheap-ai-ml-machine/) – Hardware-focused guide for affordable local AI/ML infrastructure.

### ML Tooling & Model Serving

- [Kubeflow Quickstart Guide](https://www.kubeflow.org/docs/components/notebooks/quickstart-guide/) – Official quickstart for notebook-based ML workflows on Kubernetes.
- [Deploy ML Model on Kubernetes with KServe](https://devopscube.com/deploy-ml-model-kubernetes-kserve/) – Step-by-step practical guide for serving ML models with KServe on Kubernetes.
- [How to Deploy Ray Clusters on Kubernetes for Distributed ML](https://oneuptime.com/blog/post/2026-02-09-ray-clusters-ml-training-kubernetes/view) – Practical guide to setting up Ray clusters and running distributed ML training on Kubernetes.
- [Kubernetes: How to use it for AI workloads](https://nebius.com/blog/posts/how-to-use-kubernetes-for-ai-workloads) – Explanation of why Kubernetes fits training and inference pipelines and how to approach it architecturally.

### Commercial Instructor-Led Courses

- [Agent Orchestration on Kubernetes](https://rx-m.com/training/agent-orchestration-on-kubernetes/) – Two-day course on deploying and operating AI agents and multi-agent systems on Kubernetes, covering coordination patterns, tool integration, state management, and observability.
- [Managing Kubernetes with AI Agents](https://rx-m.com/training/managing-kubernetes-with-ai-agents/) – One-day hands-on course for ops teams: deploying intelligent agents for cluster maintenance, troubleshooting, security audits, and best-practice enforcement.
- [Machine Learning on Kubernetes](https://rx-m.com/training/machine-learning-on-kubernetes/) – Three-day practical course on deploying and managing ML workflows on Kubernetes.
- [Kubeflow Foundation](https://rx-m.com/training/kubeflow-foundation/) – Three-day course covering Kubeflow pipelines, notebooks, and model serving for ML practitioners.

---

## Books (Free / Open Access)

- [Deep Learning (Goodfellow, Bengio & Courville)](https://www.deeplearningbook.org/) – The definitive deep learning textbook, freely available online.
- [Dive into Deep Learning (d2l.ai)](https://d2l.ai/) – Interactive, code-first deep learning textbook with PyTorch, JAX, and MXNet examples.
- [Pattern Recognition and Machine Learning (Bishop)](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) – Classic probabilistic ML textbook, free PDF from Microsoft Research.
- [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/) – Rigorous statistical foundations of ML, freely available from Stanford.

---

## YouTube Channels

- [RX-M LLC](https://www.youtube.com/@rx-mllc) – Cloud Native Short Takes, Kubernetes tutorials, and AI/ML walkthroughs covering topics from Pod basics to agentic AI.
- [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy) – Lectures and walkthroughs on deep learning fundamentals and LLMs, including the Zero to Hero series.
- [3Blue1Brown – Neural Networks series](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) – Beautifully visualized explanations of neural networks and backpropagation.
- [Yannic Kilcher](https://www.youtube.com/@YannicKilcher) – In-depth paper readings and ML research commentary.
- [Two Minute Papers](https://www.youtube.com/@TwoMinutePapers) – Accessible summaries of the latest AI research papers.

---

## Communities & Newsletters

- [Papers With Code](https://paperswithcode.com/) – Machine learning papers with open-source implementations and state-of-the-art benchmarks.
- [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) – Weekly AI news and tutorials curated by Andrew Ng.
- [The Algorithmic (RX-M)](https://rx-m.com/blog/) – Ongoing newsletter series analyzing LLM trends, agentic AI architectures, and cloud native developments from a practitioner lens.
- [CNCF Blog](https://www.cncf.io/blog/) – Official Cloud Native Computing Foundation blog with project updates, case studies, and technical posts.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) – Active Reddit community for ML research discussion and paper sharing.
- [r/kubernetes](https://www.reddit.com/r/kubernetes/) – Practitioner community for Kubernetes operations, tooling, and cloud native discussions.

---

## CNCF Certifications

For CNCF exam preparation, the self-study courses linked above (CKAD, CKA, CKS) are a good starting point. Additional boot camps and exam prep courses covering KCNA, KCSA, CCA, ICA, CAPA, CGOA, CNPA, and CNPE are available through the [Linux Foundation](https://training.linuxfoundation.org/) and [RX-M](https://rx-m.com/cloud-native-certifications/). Interactive practice environments are available free at [KillrCoda](https://killercoda.com/) and [killer.sh](https://killer.sh) (included with exam registration).
