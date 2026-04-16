# ✨ GASim

This repository is the implementation of our ACL 2026 paper *GASim: A Graph-Accelerated Hybrid Framework for Social Simulation*. Our contributions can be summarized as follows:

- We introduce **GASim**, a graph-accelerated hybrid multi-agent framework for large-scale social simulations, with **EDG** as a hybrid coordinator that dynamically partitions agents into core and ordinary types.
- We propose **GOM** for core agents to rapidly retrieve memories with a lightweight graph-based memory model, alleviating the heavy latency in LLM-based retrieval process.
- We design **GMP** for ordinary agents to update opinion in parallel with fine-grained features and Graph Attention Network, resolving the sequential execution bottlenecks of ABMs.

With the above design, GASim not only delivers a substantial **9.94× end-to-end speedup** over the traditional hybrid framework, but also consumes **less than 20\% of baseline tokens**. 


---

Our code will be released soon!



