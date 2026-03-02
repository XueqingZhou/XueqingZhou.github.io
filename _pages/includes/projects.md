<span class='anchor' id='projects'></span>

## Projects / Engineering Evidence

### Continuous-Time Attention (CTA): algorithm → kernel → serving

I maintain **Continuous-Time Attention** as an **end-to-end systems portfolio**: take a mathematically grounded token-mixing operator (PDE/stencil), implement it as a **fused Triton kernel**, and integrate it into a **serving-style benchmark stack**.

- **Core idea**: view CTA as a local, kernel-friendly stencil token mixing step for long-context pipelines.
- **Evidence-first artifacts**: microbenchmarks + profiler traces + reproducible scripts (prefill latency / peak memory).
- **Links**: [[Project page](https://xueqingzhou.github.io/Continuous-Time-Attention/)] · [[Code](https://github.com/XueqingZhou/Continuous-Time-Attention)]

### Research-to-systems themes (what I optimize for)

- **Long-context efficiency**: stable scaling, memory behavior, and controllable compute policies.
- **Mechanistic diagnostics**: quantify “where information goes” and use causal interventions as debugging tools.
- **System-aware evaluation**: measurements that help decide architecture trade-offs in real serving constraints.
