# Defilan Technologies

**Open-source AI infrastructure for teams that need to own their stack.**

We're a software company in Washington State building tools that make self-hosted LLM deployment practical on Kubernetes. Our work is open source, Apache 2.0 licensed, and designed for production use.

---

## Our Projects

### [LLMKube](https://github.com/defilantech/llmkube) — Kubernetes Operator for LLM Inference

A Kubernetes operator that turns LLM deployment into a two-line YAML problem. Define a Model and an InferenceService, and the operator handles the rest — downloading, caching, GPU scheduling, health checks, and exposing an OpenAI-compatible API.

```bash
llmkube deploy llama-3.1-8b --gpu
```

**What makes it different:**

- **Heterogeneous GPU support** — NVIDIA CUDA and Apple Silicon Metal in the same cluster, managed by the same CRDs. The [Metal Agent](https://github.com/defilantech/llmkube/tree/main/deployment/macos) runs inference natively on macOS while Kubernetes handles orchestration.
- **OpenAI-compatible API** — Drop-in replacement for OpenAI endpoints. Works with LangChain, LlamaIndex, and any OpenAI SDK.
- **Full observability** — Prometheus metrics, OpenTelemetry tracing, and Grafana dashboards included.
- **Air-gap ready** — Built for environments where cloud APIs aren't an option.

---

## How We Work

Everything we build is open source first. We believe the best infrastructure software gets built in the open, with input from the people who actually use it.

We welcome contributions at every level — from filing issues and improving docs to adding new features. If you're interested in Kubernetes, GPU orchestration, or LLM infrastructure, we'd love to work with you.

- **Issues & features:** [GitHub Issues](https://github.com/defilantech/llmkube/issues)
- **Questions & ideas:** [GitHub Discussions](https://github.com/defilantech/llmkube/discussions)
- **Contributing:** [CONTRIBUTING.md](https://github.com/defilantech/llmkube/blob/main/CONTRIBUTING.md)

---

## Get in Touch

- **Website:** [defilan.com](https://defilan.com)
- **GitHub:** [github.com/defilantech](https://github.com/defilantech)
- **Location:** Washington State

<p align="center">
  <a href="https://github.com/defilantech/llmkube">Star LLMKube on GitHub</a> · <a href="https://github.com/defilantech/llmkube/discussions">Join the Discussion</a>
</p>
