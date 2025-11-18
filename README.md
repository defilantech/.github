# Hi there, I'm Christopher Maher 👋

**Founder & Principal Engineer** at [Defilan Technologies](https://defilan.com) 🚀

Building production-grade infrastructure for local AI deployment.

---

## 🎯 What I'm Working On

### [LLMKube](https://github.com/defilantech/llmkube) - Kubernetes for Local LLMs

Open-source Kubernetes operator that brings production-grade orchestration to local LLM deployments. Perfect for air-gapped, edge, and hybrid environments.

```yaml
apiVersion: inference.llmkube.dev/v1alpha1
kind: Model
metadata:
  name: phi-3-mini
spec:
  source: https://huggingface.co/microsoft/Phi-3-mini-4k-instruct-gguf/...
  hardware:
    accelerator: cuda
```

**Why LLMKube?**
- 🔒 **Air-Gap Ready** - Deploy AI in classified, HIPAA, or disconnected environments
- ☸️ **Kubernetes Native** - Familiar tools, production-grade reliability
- 🎯 **SLO Enforcement** - Automatic scaling and failover to meet latency targets
- 🔌 **OpenAI Compatible** - Drop-in replacement for existing applications
- 📊 **Built-in Observability** - Prometheus metrics, OpenTelemetry tracing

---

## 🏢 About Defilan Technologies

We're building the infrastructure for the next generation of AI deployment. Too many organizations in defense, healthcare, manufacturing, and finance are locked out of the AI revolution because existing solutions require constant cloud connectivity.

**Our Mission:** Make production-grade AI infrastructure accessible to organizations regardless of connectivity constraints or regulatory environment.

**Core Values:**
- 🔓 **Open by Default** - Apache 2.0 licensed, community-driven development
- 🎯 **Production First** - Every feature designed for real-world deployments
- 🛡️ **Security Conscious** - TEE support, audit logging, PII detection built-in
- 🤝 **Community Driven** - Built by the people who use it

---

## 📫 Get In Touch

- 🌐 **Website:** [defilan.com](https://defilan.com)
- 💼 **Company:** [Defilan Technologies LLC](https://defilan.com)
- 📍 **Location:** Gig Harbor, WA
- 💬 **Community:** [GitHub Discussions](https://github.com/defilantech/llmkube/discussions)

---

## 🔧 Tech Stack

**Current Focus:**
- Kubernetes Operators & CRDs
- Go (operator development)
- Local LLM inference (llama.cpp, vLLM, TGI)
- eBPF observability
- GPU acceleration (CUDA, Metal)

**Previous Experience:**
- Cloud-native infrastructure
- Distributed systems
- Security & compliance
- DevOps & SRE

---

<p align="center">
  <i>Building the future of AI infrastructure, one commit at a time.</i>
</p>

<p align="center">
  <a href="https://github.com/defilantech/llmkube">⭐ Star LLMKube</a> •
  <a href="https://defilan.com">🌐 Visit Defilan.com</a> •
  <a href="https://github.com/defilantech/llmkube/discussions">💬 Join Community</a>
</p>
