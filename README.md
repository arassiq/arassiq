# Aaron Rassiq

I’m building toward machine learning engineering roles by developing local AI
systems from the model layer outward: data pipelines, fine-tuning, evaluation,
retrieval, inference, and the applications that sit on top of them.

Right now, I’m focused on a reproducible post-training laboratory for adapting
small code models on Apple Silicon. The goal is to measure what actually
improves functional correctness—not just what lowers training loss.

## Selected work

### [Local Post-Training Lab](https://github.com/arassiq/local-post-training-lab)

A local-first platform for full-parameter AdamW fine-tuning and execution-based
evaluation of code models. It includes a custom supervised fine-tuning loop,
dataset validation, MPS support, mutation-based repair tasks, checkpointing, and
an executable `pass@1` evaluator.

### [LocalDex](https://github.com/arassiq/LocalDex)

Local retrieval infrastructure for private RAG workflows, including pluggable
embedding models, semantic chunking experiments, vector indexing, and
Apple-Silicon-specific inference work.

### [LLMediator](https://github.com/arassiq/LLMediator)

A real-time AI-assisted mediation application with role-aware conversations,
WebSocket communication, and a Python service layer.

## What I’m exploring

- Full-parameter fine-tuning, LoRA, and preference optimization
- Functional evaluation and reinforcement learning with verifiable rewards
- Local inference and memory-aware training on Apple Silicon
- Retrieval systems, embedding pipelines, and context selection
- Reliable AI applications with measurable behavior

## Current direction

The next milestones for the post-training lab are a base-model benchmark, a
verified mutation-generated dataset, a full AdamW fine-tuning run, and a
base-versus-fine-tuned evaluation report.
