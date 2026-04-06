## Hi, I’m Mahesh 👋

I build CPU-first systems for running large language models - reducing inference cost, memory usage, and latency.

→ 8.6× faster than PyTorch CPU (INT8 + AVX2)  
→ 4× lower memory footprint  
→ Pure C (no ML frameworks)

I focus on making LLM inference deployable everywhere — not just on GPUs.

---

## 💰 Why this matters

LLM inference runs millions to billions of times.

Even small efficiency gains translate directly into **millions of dollars saved**.

Example:

- GPU inference: $0.002 / request  
- Optimized CPU inference: $0.0003 / request  

At 10M requests/day:

→ ~$17,000 saved per day  
→ ~$6M saved per year  

I work on making this shift possible.

---

⚙️ Systems I build

• Transformer inference engine in C (forward + backward pass)
• Cache-aware attention kernels (tiled, memory-optimized)
• INT8/low-bit quantization pipelines
• AVX2 SIMD optimized matmul & kernels
• Arena-based memory allocator (zero fragmentation)
• KV-cache optimized for long sequence inference

## 🧪 Proof of work

- Contributor to `ggml-org/llama.cpp`
  - Fixed integer type inconsistencies in split helpers  
  - PR: https://github.com/ggml-org/llama.cpp/pull/18894  

- Built a CPU-first LLM engine:
  - Explicit memory layout control  
  - Quantized inference  
  - Benchmarked against baseline implementations  

---

## 🧠 Current focus

- Attention performance on CPUs  
- Memory bandwidth & cache behavior  
- KV-cache optimization  
- INT8 / INT4 / INT2 tradeoffs  

---

## 🎯 What I care about

Making LLM systems:

- Cheaper  
- Faster  
- Deployable on commodity hardware  

---

If you work on ML systems, inference engines, or compilers - let’s connect.
