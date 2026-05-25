
---

# Emmanuel Hilary
Backend engineer moving toward AI infrastructure — inference and serving.

I currently build backend systems in production. The direction I'm moving is the layer underneath AI: how models actually get served — fast, cheap, reliably, at load. That's the work I'm learning toward.

I'm interested in what happens before the first request lands. Where the load goes. What fails first when something fails. Why GPUs sit at 30% utilization while the bill doesn't.

---

### Where I am now

Backend engineering — APIs, schemas, services. The fundamentals that carry over: distributed systems thinking, debugging under pressure, designing things that don't fall over when they meet real traffic.

### Where I'm going

**Inference & serving** — the layer between a trained model and a real user. Batching, scheduling, KV cache, quantization. The trade-offs between throughput and tail latency.

**Serving runtimes** — vLLM, TensorRT-LLM, TGI. Autoscaling that tracks load. Multi-model routing. GPU utilization that isn't quietly wasted.

**Cloud & systems underneath** — provisioning, networking, the architectural choices that quietly decide your bill six months from now.

**Pipelines around the model** — retrieval, caching, the parts that decide whether the model is fast because it's fast or fast because most requests never reach it.

---

### How I move

The interesting problems in inference sit between layers — between the model and the runtime, between the runtime and the scheduler, between the scheduler and the hardware. I'm working toward being properly good across that whole stack, not stuck at one slice of it.

---

### Reach me
[GitHub](https://github.com/emmanuel1-byte) · [LinkedIn](https://www.linkedin.com/in/emmanuel-hilary-7309453a2) · [emmanuelhilary.contact@gmail.com](mailto:emmanuelhilary.contact@gmail.com)

---
