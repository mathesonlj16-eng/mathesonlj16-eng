# Lucas Matheson

**Software Engineer | AI Systems, Performance & Security**

BSc in Computer Science at Wilfrid Laurier University (expected December 2026). I build full-stack applications and investigate lower-level engineering problems involving compilers, GPU inference, and software security.

Ontario, Canada

## Current interests

- **Systems and performance engineering** — LLVM/Clang, native-code behavior, benchmarking, reproducible performance investigations, CUDA and GPU profiling.
- **AI systems** — local LLMs, inference behavior, model evaluation, performance tradeoffs, and AI governance traceability.
- **Security engineering** — identity verification, authorization boundaries, GitHub Actions OIDC, and negative-case testing.
- **Full-stack software** — Python, TypeScript, React, APIs, databases, dashboards, and practical automation.

## Selected work

- **[GovTrace — AI Governance Research Prototype](https://github.com/mathesonlj16-eng/GovTrace-Research)** — Independent research prototype that traces how a policy amendment affects registered AI systems, obligations and prior assessments, and turns those changes into human-reviewed reassessment work. Full-stack TypeScript (React, Express/Node.js, PostgreSQL, Docker Compose, Playwright) with a deterministic, versioned policy-control engine. Historical replays of Directive on Automated Decision-Making amendments matched 386/386 and 218/218 expected per-system changes across fictional systems; the expected changes were developer-defined, with no independent answer key. Public repo holds documentation, methodology and screenshots; source code is private.
- **[llama.cpp Speculative Rollback Study](https://github.com/mathesonlj16-eng/llama-speculative-rollback-study)** — Reproducible GPU inference investigation on a GTX 1650. Profiled speculative decoding, prototyped recurrent-state rollback optimizations, and validated greedy correctness on CPU reference kernels with mutation tests. Target checkpoint-free rollback reduced two-slot median wall time by 15.3% in the original experiment and 20.4% in a clean rerun under a different restore-count mode; plain decoding remained fastest for the tested model pair. [Verified release v1.0.0](https://github.com/mathesonlj16-eng/llama-speculative-rollback-study/releases/tag/v1.0.0).
- **[LLVM Performance Investigator](https://github.com/mathesonlj16-eng/llvm-performance-investigator)** — Compiler investigations covering loop vectorization, aliasing, machine code, and measured runtime behavior, plus a small verified LLVM pass. Reports include reproducibility instructions and limitations.
- **[llama.cpp CUDA SET_ROWS contribution proposal](https://github.com/ggml-org/llama.cpp/pull/32832)** — Submitted upstream PR addressing F16-to-F32 SET_ROWS support and a RoPE fusion issue. **Proposed contribution; not presented as merged.**
- **[Approval Autopsy — OIDC Lab](https://github.com/mathesonlj16-eng/approval-autopsy-oidc-lab)** — Experimental security lab that verifies GitHub Actions job identity and exercises incorrect-audience, cross-role, replay, and other negative cases.
- **[AgencyFlow AI](https://github.com/mathesonlj16-eng/AgencyFlow-AI)** — Local-first AI workflow application using FastAPI, Ollama, n8n, and SQLite, with evaluation and human-controlled execution.
- **[Athlete Performance Intelligence](https://github.com/mathesonlj16-eng/athlete-performance-intelligence)** — Time-ordered ML evaluation against simple baselines, using synthetic athlete data and stress tests.
- **[Notice Atlas](https://github.com/mathesonlj16-eng/notice-atlas-demo)** — Procurement intelligence demo that handles conflicting evidence and excludes unverified deadlines from reporting.
- **[Community Resource Workflow](https://github.com/mathesonlj16-eng/community-resource-workflow-demo)** — WordPress plugin for moderated community resource submissions and publication.

## How I work

I prefer small reproducible experiments, measurable results, and explicit limitations. In research-oriented work, I distinguish an observed effect from a proven cause; in product work, I focus on delivering a functional end-to-end system.

## Currently

- Completing my BSc in Computer Science (expected December 2026)
- Exploring compiler and GPU performance, AI infrastructure, and security while continuing full-stack development
- Open to software engineering roles across full-stack, systems, developer tooling, AI infrastructure, and security-related teams

## Contact

- [LinkedIn](https://www.linkedin.com/in/lucas-matheson-251521349/)
- mathesonlj16@gmail.com
