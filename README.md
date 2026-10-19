### Falak Shair

**Forward Deployed Engineer · Enterprise AI · ML Infrastructure** — Karachi, Pakistan

I put AI systems into production inside banks, and I study why LLM inference is slow at the hardware level.

**Enterprise delivery.** At wAI Industries I deploy production AI for major Pakistani banks: RAG assistants and WhatsApp AI assistants integrated with core-banking APIs, Kafka-based event pipelines, Redis on GCP, on-prem Docker deployments, infrastructure provisioning, and security hardening — from first workshop to production handover. That client work is private.

**AI performance.** On my own time I profile LLM inference and write Triton kernels, measuring on real hardware before optimizing.

---

#### Selected work

| Project | What it shows | Measured result |
|---|---|---|
| [**mlsys-journey**](https://github.com/falakshair01/mlsys-journey) | GPU profiling of transformer inference, vLLM vs HuggingFace serving, Triton kernels | GPT-2 @ seq 512: MLP 46% of GPU time vs attention 8.8%. vLLM needs ~0.9 GB beyond model weights (OOM on a 4 GB GPU). Fused softmax: 1.49× over naive Triton, on par with PyTorch |
| [**ml-inference-scheduler**](https://github.com/falakshair01/ml-inference-scheduler) | Load-aware routing of inference requests across mixed GPU/CPU workers, Redis state, Prometheus/Grafana, Docker Compose | Prototype with simulated workers |

#### Writing

- [I Profiled LLM Inference from First Principles — Here's What I Found](https://medium.com/@falakshair563/i-profiled-llm-inference-from-first-principles-heres-what-i-found-823083e502dc)
- [I Wrote My First GPU Kernel — Here's What Changed](https://medium.com/@falakshair563/i-wrote-my-first-gpu-kernel-heres-what-changed-3bfdacd6fe57)

#### Tools I use in production

Python (FastAPI, Django) · Node.js / TypeScript · Kafka · Redis · Docker · GCP & Azure · PyTorch · Triton · vLLM

#### Contact

[LinkedIn](https://www.linkedin.com/in/falak-shair-software-engineer) · [Medium](https://medium.com/@falakshair563) · falakshair563@gmail.com
