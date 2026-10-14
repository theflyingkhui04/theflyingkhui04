# Hi, I'm Khoi 👋

Final-year computer science student at PTIT, Hanoi. I work as a junior AI developer at a Japanese IT company.
I like to train models, make them run faster and put them into real products.

[LinkedIn](https://linkedin.com/in/duckhoi04) · [Email](mailto:itsduckhoi04@gmail.com) · [Hugging Face](https://huggingface.co/duckhoi)

## What I work on

- **At work:** I co-developed an internal RAG chatbot for Japanese design documents. It runs on a self-hosted LLM and a team of 20-30 people uses it. I also built the backend for a multi-agent tool that writes test cases. Both use LangGraph.
- **Thesis:** I am the project manager and inference engine lead in a team of 3. We work on speculative decoding in vLLM on a T4 GPU.
- **Now learning:** model quantization and how to run models on small devices.

## Projects

**Speculative decoding for self-hosted LLMs** · graduation thesis, ongoing
I built a draft controller in vLLM. It picks 0 to 4 draft tokens for each request based on the recent acceptance rate. Fixed-length drafting gave 1.34x throughput on JSON tasks but only 0.81x on free text. The controller tries to close this gap.
I also trained an [EAGLE-3.1 draft head for Qwen2.5-7B](https://huggingface.co/duckhoi/qwen2.5-7b-eagle3.1-speculator) on 30K English and Vietnamese samples. Benchmarking is still in progress.

**[Referring image segmentation](https://github.com/theflyingkhui04/Referring-Image-Segmentation)** · course project, team of 4
The model cuts out the object described by a sentence. A large model, LAVT, teaches a smaller model, CLIPSeg. I did the training and distillation. It reached mIoU 0.51 on RefCOCO+.

**[Graph-based e-commerce recommender](https://github.com/nguyenmaiductrong/heterogeneous-graph-based-ecom-recsys)** · course project, team of 4
A graph neural network predicts what users buy next on REES46, with 203K users and 32M interactions. I designed the time-aware modules, built the MixRec baseline and made the demo.

**[TNKV-DB](https://github.com/theflyingkhui04/TNKV-DB)** · course project, team of 3, team lead
A small sparse vector database built from scratch. It has an inverted index with compression, BM25 ranking, query expansion and a Streamlit demo.

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

- **Deep learning:** PyTorch, PyTorch Geometric, Hugging Face, OpenCV, CLIP, BLIP
- **LLM:** LangGraph, RAG, Qdrant, vLLM, LoRA and QLoRA, speculative decoding
- **Backend:** FastAPI, PostgreSQL, Redis, Celery, Docker
