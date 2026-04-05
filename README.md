## Hi, I’m Mahesh 👋

I build systems to run large language models efficiently on CPUs reducing cost, memory, and latency.

→ 8.6× faster than PyTorch CPU (INT8 + AVX2)
→ 4× lower memory footprint
→ Pure C (no ML frameworks)

Focused on making LLM inference deployable everywhere — not just on GPUs.

### Why this matters
Why this matters

LLM inference runs millions of times per day.

Reducing cost per request even slightly can save companies millions annually.

Example:
If inference cost drops from $0.002 → $0.0003,
a system serving 10M requests/day saves ~$6M/year.

I work on making that possible on CPUs.

### Proof of work
- Contributor to `ggml-org/llama.cpp`
  - Fixed integer type inconsistencies in split helpers (https://github.com/ggml-org/llama.cpp/pull/18894)
- Built an LLM from scratch in C:
  - forward + backward pass
  - explicit memory layout control
  - benchmarks vs baseline implementations

### Current focus
- Attention performance on CPUs
- Quantization tradeoffs (INT8 / INT4 / INT2)
- Memory locality and cache misses in transformer inference

If you work on ML systems, inference engines, or compilers, I’d love to exchange notes.
