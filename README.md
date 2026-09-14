![Hi, I'm Nikhil](https://capsule-render.vercel.app/api?type=waving&height=200&color=gradient&text=Hi%20I%27m%20Nikhil%21&fontSize=52&fontAlignY=38&)

- 🎓 **MS Computer Science @ Northeastern University**
- 🔬 **Applied AI Intern @ Nanonets**, working on vision-language models
- 🔧 Mechanical engineering @ Santa Clara University
- ⚡ **Post-training:** distillation, compression, and the evals that tell you whether either one worked

Five years as a mechanical engineer at Cisco before this, doing thermal and interconnect design and experimentation for optical systems. I worked on their first co-packaged optics system, demoed at OFC 2023, led reliability studies on thermal interface materials, and optimized manufacturing lines for throughput and cost. I taught myself ML there to go after hardware failure analysis. Between what that project showed me and what GPT-3 showed everyone, the case for diving into the field made itself.

---

### Currently

**Nanonets:** compression, evaluation, and post-training for OCR vision-language models.

**Co-Training and Co-Distillation:** exploring the benefits of mutual learning and distillation in post-training. First results published at SPIE 2026; now extending the work to open-ended generation. Advised by Karl Ni.

**Going deeper on:** distributed training, RL post-training and reward design, gated linear attention, inference optimization, and the statistics of running honest experiments. Always happy to talk about any of these.

---

### Repositories

#### [CTCD_Post_Training](https://github.com/nikhitrivedi1/CTCD_Post_Training)
`pytorch` `knowledge-distillation` `post-training` `glue` `research-code`

Code behind the SPIE 2026 paper. A single YAML switch moves a run anywhere from standard fine-tuning to full CTCD. Seven GLUE tasks plus CLINC150, BERT-base teachers, DistilBERT students. The result is null-ish and reported that way: CTCD matches vanilla KD rather than beating it, and the effect that does show up lands on the teacher, not the student.

#### [PULSY](https://github.com/nikhitrivedi1/PULSY) · [live](https://pulsy-768224718837.us-west1.run.app/)
`agentic-rag` `langgraph` `pinecone` `fastapi` `wearables`

An advisor that turns raw Oura Ring metrics into guidance grounded in health research. Retrieval tuning took Precision@3 up 90% and MRR up 61% over baseline; agent traces scored 90.4% workflow compliance under an LLM-as-Judge.

#### [Transformer_HAC](https://github.com/nikhitrivedi1/Transformer_HAC)
`patchtst` `time-series` `har` `pytorch`

Wrist-accelerometer activity classification on CAPTURE-24, with PatchTST's forecasting head swapped for a classification head. In progress, tracked against the CNN+HMM benchmark.

---

### Stack

|  |  |
|---|---|
| **Training & post-training** | PyTorch · HuggingFace Transformers · Weights & Biases · SLURM |
| **Agents & retrieval** | LangGraph · LangChain · Pinecone |
| **Serving & apps** | FastAPI · Node.js · GCP · MongoDB |
| **Languages** | Python · C · Java · JavaScript |

---

[LinkedIn](https://www.linkedin.com/in/nikhil-trivedi-5897b1125/) · nikhitrivedi1@gmail.com
