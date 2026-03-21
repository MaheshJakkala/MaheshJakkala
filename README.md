## Hi, I’m Mahesh 👋

I build **CPU-first, memory-efficient LLM inference systems** from first principles.

My work focuses on understanding **why** performance happens — not just making it faster.

### What I work on
- LLM inference and training internals in **pure C**
- Cache-aware and memory-efficient implementations of attention, matmul, and tokenization
- Cross-layer optimization: math → model → memory → CPU microarchitecture

### Why this matters
GPUs are expensive and scarce.  
Most real-world deployments need **cheap, predictable, CPU-based inference**.

I study how LLMs behave at:
- cache-line level
- memory layout level
- instruction and datatype level

### Proof of work
- Contributor to `ggml-org/llama.cpp`
  - Fixed integer type inconsistencies in split helpers (https://github.com/ggml-org/llama.cpp/pull/18894)
- Built an LLM from scratch in C:
  - forward + backward pass
  - explicit memory layout control
  - benchmarks vs baseline implementations

### Current focus
- Attention performance on CPUs
- Quantization tradeoffs (INT8 / INT4)
- Memory locality and cache misses in transformer inference

If you work on ML systems, inference engines, or compilers, I’d love to exchange notes.
