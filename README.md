# Dharmik Bhingradiya

**AI/ML Engineer | Production LLM Systems, Retrieval, Observability**

I build the control layer around LLMs. Routing, gating, guardrails, evaluation, and cost control, instrumented end to end.

Currently at BlackRock, building LLM infrastructure for risk and compliance teams, where a wrong answer is not just wrong, it is a liability.

---

## What I work on

**Production LLM systems.** Enterprise RAG over millions of unstructured financial documents. Query-aware routing that weights dense vs. sparse retrieval based on intent. Retrieval-quality gating that decides whether generation fires at all. Citation-per-claim grounding so every answer is traceable to its source.

**Observability and evaluation.** I instrument everything. Knowing that a model answered is not enough. I need to know why, with what context, and whether the answer was correct. OpenTelemetry and LangSmith tracing across the full retrieve, rank, augment, generate path. Ragas evals wired into CI so quality regressions get caught before deploy.

**Fine-tuning and optimization.** LoRA and QLoRA for domain adaptation. Quantization tradeoff analysis. Token budgeting, context pruning, and prompt compression. Most of the interesting work in LLM systems is figuring out what you can cut without anyone noticing.

**First principles.** I trained a 124M parameter LLaMA-style transformer from scratch. Not for the resume line. Understanding the internals is why I could trace a production accuracy drop to 4-bit quantization degrading rare domain tokens, instead of blaming retrieval.

---

## Selected work

### [LLaMA-inspired SLM from Scratch](https://github.com/dharmik953/LLaMA-inspired-SLM-fromscratch)

A 124M parameter LLaMA-style language model built and trained from first principles.

`RMSNorm` `RoPE` `SwiGLU` `Flash Attention 2` `KV-Cache`

No framework abstractions hiding the architecture. Every component implemented to understand how modern transformers actually work, and why they work.

### Open-source LLM fine-tune

Fine-tuned and published on Hugging Face. 600+ community downloads.

---

## Stack

**Languages**
`Python` `SQL`

**LLM systems**
`RAG` `Hybrid Search` `Vector Databases` `LangChain` `Prompt Engineering` `Guardrails` `Context Management`

**Fine-tuning and models**
`PyTorch` `Hugging Face Transformers` `LoRA` `QLoRA` `PEFT` `Quantization` `Transformer Architectures`

**Observability and evals**
`OpenTelemetry` `LangSmith` `Ragas` `Prometheus` `Grafana` `Splunk`

**MLOps and infra**
`MLflow` `Docker` `CI/CD` `Kubeflow` `FastAPI` `AWS (SageMaker, EC2, S3, Lambda)` `Spark`

---

## What I am building toward

Agentic LLM systems. The hard part of agents is not the model, it is keeping multi-step execution reliable and affordable when it runs a thousand times a day. Most agent demos work once. Very few are instrumented well enough to tell you why they fail the other times.

That is the gap I am working in.

---

## Reach me

[LinkedIn](https://www.linkedin.com/in/dharmik953) | dharmik.b.work@gmail.com | [hugginfface](https://huggingface.co/jhon53) 

Open to hybrid and remote.
