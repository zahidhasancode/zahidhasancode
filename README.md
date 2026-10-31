# MD Zahid Hasan

AI and machine learning engineer based in Barcelona. I build LLM applications end to end: retrieval,
agents, fine-tuning, real-time inference, and the data pipelines and APIs around them.

- Co-founder and AI engineer at Scaling Protos (ESADE eWorks, Barcelona)
- Earlier: Devolved AI (machine learning engineer) and Secure Intelligent (Hura, privacy-preserving AI;
  [listed by the Paris Peace Forum](https://parispeaceforum.org/projects/hura-decentralized-train-llm/)
  for the AI Action Summit, Paris 2025)
- Spanish work permit; English and Spanish

## Projects

**[llm-engine](https://github.com/zahidhasancode/llm-engine)** — LLM serving engine built from scratch in
PyTorch: own Qwen2 model, KV cache, continuous batching and an OpenAI-compatible streaming API. Benchmarked on
one Tesla T4 at 229 tokens/s, against 32 for Hugging Face `generate` and 1,680 for vLLM, with the gap measured.

**[text2sql-qlora](https://github.com/zahidhasancode/text2sql-qlora)** — completed QLoRA fine-tune of
Qwen2.5-1.5B: execution accuracy on 500 held-out questions rose from 61.6 % to 71.8 %.

**[voxera](https://github.com/zahidhasancode/voxera)** — real-time voice agent prototype. Streaming
speech-to-text → LLM → text-to-speech over one WebSocket, with turn-taking, barge-in during playback,
sentence-by-sentence speech and a benchmark that measures latency from outside; barge-in 63 ms median with
Deepgram. Python, FastAPI.

**[llm-evaluation-platform](https://github.com/zahidhasancode/llm-evaluation-platform)** — prototype
service for storing LLM request data, running evaluators and aggregating quality, latency and cost.

**[llm-data-platform](https://github.com/zahidhasancode/llm-data-platform)** — prototype pipeline for
dataset versioning and config-driven runs (training and evaluation steps are simulated stubs).

**Fine-tuning study notebooks** (QLoRA setups) — [Mixtral 8x7B](https://github.com/zahidhasancode/Finetuning-mixtral8x7b),
[LLaMA 2 7B](https://github.com/zahidhasancode/Fine-Tuning-Llama-Custom-dataset).

**Retrieval** — [RAG backend with FastAPI and FAISS](https://github.com/zahidhasancode/RAG-APPLICATION),
[RAG chatbot](https://github.com/zahidhasancode/RAG-Chatbot-Application).

**Earlier work** — [IoT botnet detection with simulated federated learning](https://github.com/zahidhasancode/iot-botnet-detection-federated-learning),
[worker detection with YOLOv8](https://github.com/zahidhasancode/garment-worker-detection-yolov8),
[GPT-2 (124M) fine-tuning demo](https://github.com/zahidhasancode/Building-GPT-LLM-124M).

## Working with

Python · FastAPI · PyTorch · Hugging Face · LangGraph / LangChain · LlamaIndex · vLLM ·
Docker · Kubernetes · AWS / GCP / Azure

## Contact

[LinkedIn](https://www.linkedin.com/in/md-zahid-hasan-88321716a) · zahidhasancode.ml@gmail.com
