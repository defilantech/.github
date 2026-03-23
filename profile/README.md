# Defilan Technologies

**Open-source AI infrastructure for teams that need to own their stack.**

We're a software company in Washington State building tools that make self-hosted AI practical on Kubernetes. Our work is open source, Apache 2.0 licensed, and designed for production use.

---

## Our Projects

### [LLMKube](https://github.com/defilantech/llmkube) — Kubernetes Operator for LLM Inference

A Kubernetes operator that turns LLM deployment into a two-line YAML problem. Define a Model and an InferenceService, and the operator handles the rest: downloading, caching, GPU scheduling, health checks, and exposing an OpenAI-compatible API.

- **Heterogeneous GPU support**: NVIDIA CUDA and Apple Silicon Metal in the same cluster
- **OpenAI-compatible API**: Drop-in replacement, works with LangChain, LlamaIndex, any OpenAI SDK
- **Full observability**: Prometheus metrics, OpenTelemetry tracing, Grafana dashboards
- **Air-gap ready**: Built for environments where cloud APIs aren't an option

[Website](https://llmkube.com) · [Documentation](https://github.com/defilantech/llmkube#quick-start) · [Install via Homebrew](https://github.com/defilantech/llmkube#install)

---

### [InferCost](https://github.com/defilantech/infercost) — Cost Intelligence for On-Prem AI Inference

A Kubernetes-native platform that computes the true cost of running AI on your own hardware. InferCost combines GPU hardware amortization, real-time electricity costs, and token-level attribution to answer the question no other tool can: *"What does inference actually cost us, and how does that compare to cloud APIs?"*

- **True cost-per-token**: Computed from hardware amortization, DCGM power draw, and electricity rates
- **Cloud comparison**: Verified pricing across OpenAI, Anthropic, and Google, including when cloud is cheaper
- **Per-team attribution**: Costs broken down by Kubernetes namespace with zero configuration
- **Multiple surfaces**: Prometheus metrics, REST API, CLI, and a pre-built Grafana dashboard

[Website](https://infercost.ai) · [Documentation](https://github.com/defilantech/infercost#quick-start) · [Install via Homebrew](https://github.com/defilantech/infercost#install)

---

## How They Work Together

LLMKube and InferCost are independent projects that complement each other. LLMKube deploys and manages your inference workloads. InferCost tracks what those workloads cost. Together, they give platform teams full control over both the deployment and the economics of self-hosted AI.

InferCost works with any Kubernetes inference stack, not just LLMKube.

---

## How We Work

Everything we build is open source first. We believe the best infrastructure software gets built in the open, with input from the people who actually use it.

We welcome contributions at every level, from filing issues and improving docs to adding new features. If you're interested in Kubernetes, GPU orchestration, AI FinOps, or LLM infrastructure, we'd love to work with you.

**LLMKube:** [Issues](https://github.com/defilantech/llmkube/issues) · [Discussions](https://github.com/defilantech/llmkube/discussions) · [Contributing](https://github.com/defilantech/llmkube/blob/main/CONTRIBUTING.md)

**InferCost:** [Issues](https://github.com/defilantech/infercost/issues) · [Contributing](https://github.com/defilantech/infercost/blob/main/CONTRIBUTING.md)

---

## Get in Touch

- **Website:** [defilan.com](https://defilan.com)
- **GitHub:** [github.com/defilantech](https://github.com/defilantech)
- **Location:** Washington State

<p align="center">
  <a href="https://github.com/defilantech/llmkube">Star LLMKube</a> · <a href="https://github.com/defilantech/infercost">Star InferCost</a> · <a href="https://github.com/defilantech/llmkube/discussions">Join the Discussion</a>
</p>
