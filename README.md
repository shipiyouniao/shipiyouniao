<p align="center">
  <img src="./assets/inference-pipeline.svg" alt="Inference systems banner" width="100%" />
</p>

<h1 align="center">石皮幼鸟 · shipiyouniao</h1>

<p align="center">
  AI infrastructure engineer on Sangfor's Managed Cloud Platform team,<br />
  building predictable LLM serving, elastic GPU memory, and runtime protocols.
</p>

<p align="center">
  <a href="https://github.com/NagareWorks"><img src="https://img.shields.io/badge/NagareWorks-111827?style=flat-square&logo=github&logoColor=white" alt="NagareWorks" /></a>
</p>

I work where inference engines, GPU runtimes, and cloud-native control planes meet.
My current focus is making shared accelerators behave like dependable infrastructure:
correct under pressure, observable in production, and fast on real workloads.

### Current work

- **LLM serving:** vLLM and SGLang integration, long-context inference, PD multiplexing,
  CUDA execution paths, and correctness-first performance analysis.
- **Elastic GPU memory:** KV cache pooling, CUDA VMM, quota and reclamation policy,
  multi-instance isolation, MPS, and shared model weights.
- **Runtime protocols:** building [NNRP](https://github.com/NagareWorks) across Rust,
  Python, and C# with deterministic transports and explicit lifecycle semantics.
- **Cloud native:** Kubernetes-oriented placement, observability, recovery, and
  platform integration for production inference systems.

### Selected work

| Area | Project | What I work on |
| --- | --- | --- |
| Runtime protocol | [NagareWorks/nnrp-rs](https://github.com/NagareWorks/nnrp-rs) | Native transport and lifecycle runtime |
| SDK | [NagareWorks/nnrp-py](https://github.com/NagareWorks/nnrp-py) | Python runtime bindings and release engineering |
| SDK | [NagareWorks/nnrp-cs](https://github.com/NagareWorks/nnrp-cs) | C# protocol SDK and native transport integration |
| Unity tooling | [UnityEasyInject](https://github.com/shipiyouniao/UnityEasyInject) | Lightweight dependency injection for Unity |

### Toolbox

<p>
  <img src="https://img.shields.io/badge/CUDA-111827?style=flat-square&logo=nvidia&logoColor=76B900" alt="CUDA" />
  <img src="https://img.shields.io/badge/C%2B%2B-111827?style=flat-square&logo=cplusplus&logoColor=5C8DBC" alt="C++" />
  <img src="https://img.shields.io/badge/Rust-111827?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
  <img src="https://img.shields.io/badge/Go-111827?style=flat-square&logo=go&logoColor=00ADD8" alt="Go" />
  <img src="https://img.shields.io/badge/Kubernetes-111827?style=flat-square&logo=kubernetes&logoColor=6D91ED" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/PyTorch-111827?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
</p>

> Measure the real path. Preserve the invariants. Optimize what remains.
