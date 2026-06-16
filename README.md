# Emmanuel Hilary

Backend engineer moving toward AI infrastructure, specifically inference and serving.

I build backend systems in production today. The direction I'm headed is the layer underneath AI: how models actually get served, fast and cheap and reliably, under real load. That's the work I'm learning toward.

What pulls me in is everything that happens before the first request lands. Where the load goes. What fails first when something fails. Why GPUs sit at 30% utilization while the bill doesn't move.

---

### Where I am now

Backend engineering: APIs, schemas, services. The fundamentals that carry over are distributed systems thinking, debugging under pressure, and designing things that hold up when they meet real traffic.

### Where I'm going

**Inference and serving.** The layer between a trained model and a real user. Batching, scheduling, KV cache, quantization, and the trade off between throughput and tail latency.

**Serving runtimes.** vLLM, TensorRT-LLM, TGI. Autoscaling that actually tracks load. Multi model routing. GPU utilization that isn't quietly wasted.

**Cloud and systems underneath.** Provisioning, networking, and the architectural choices that quietly decide your bill six months out.

**Pipelines around the model.** Retrieval, caching, and the parts that decide whether the model is fast because it's fast, or fast because most requests never reach it.

---

### How I move

The interesting problems in inference live between layers. Between the model and the runtime, between the runtime and the scheduler, between the scheduler and the hardware. I'm working toward being properly good across that whole stack rather than stuck in one slice of it.

---

### Reach me

[GitHub](https://github.com/emmanuel1-byte) · [LinkedIn](https://www.linkedin.com/in/emmanuel-hilary-7309453a2) · [emmanuelhilary.contact@gmail.com](mailto:emmanuelhilary.contact@gmail.com)
