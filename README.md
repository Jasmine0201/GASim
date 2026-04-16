# ✨ GASim

This is the official implementation of the **ACL 2026 paper** *GASim: A Graph-Accelerated Hybrid Framework for Social Simulation*. GASim not only delivers a substantial **9.94× end-to-end speedup** over the traditional hybrid framework, but also consumes **less than 20\% of baseline tokens**. **Our code will be released soon🔥!**

## 🌟 Overview

Large-scale social simulators are essential for studying complex social patterns. Prior work explores hybrid methods to scale up simulations, combining large language models (LLM)-based agents with numerical agent-based models (ABM). However, this incurs high latency due to expensive memory retrieval and sequential ABM execution. 
To address this challenge, we propose GASim with key components as follows:

- A hybrid coordinator **EDG** that dynamically partitions agents into core and ordinary types.
- **GOM** for core agents, which rapidly retrieves memories with a lightweight graph-based memory model, alleviating the heavy latency in LLM-based retrieval process.
- **GMP** for ordinary agents, which updates opinions in parallel with fine-grained features and Graph Attention Network, resolving the sequential execution bottlenecks of ABMs.

---

![framework](/readme_pics/framework.png)

---

## 📅 TODO List
- [ ] Release "Getting Started" guidelines
- [ ] Release the overall social simulation module
- [ ] Release GOM validation on LoCoMo dataset
- [ ] Release GMP training module
- [ ] Release anonymized social topic-based datasets


## 🙏 Acknowledgements

This repo is built upon the [AgentVerse](https://github.com/OpenBMB/AgentVerse) and [HiSim](https://github.com/xymou/HiSim) framework. We sincerely thank the authors for their contributions to the community.







