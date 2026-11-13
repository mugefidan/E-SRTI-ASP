# Benchmark Instances

This repository contains the benchmark instances used in the experimental evaluation presented in our paper:

**"Model-based Explanation Generation for Stable Roommates Problems"**

The table below maps each table and figure in the paper to the benchmark set considered in the evaluation, together with a brief description.

| Table / Figure | Benchmark Set | Description |
| :--- | :--- | :--- |
| **Table 3**  | [Benchmark Set 1](./benchmark%20instances/Benchmark%20Set%201) | Computational performance of `E-SRTI-ASP` for `wh*` queries |
| **Table 4**  | [Benchmark Set 2](./benchmark%20instances/Benchmark%20Set%202) | Computational performance of `E-SRTI-ASP` for `wh*` queries |
| **Table 5**  | [Benchmark Set 3](./benchmark%20instances/Benchmark%20Set%203) | Computational performance of `E-SRTI-ASP` for `whynone` queries |
| **Table 6**  | [Benchmark Set 1](./benchmark%20instances/Benchmark%20Set%201) | Computational performance of `E-SRTI-ASP` for `howfair` queries |
| **Figure 4**  | [Benchmark Set 1](./benchmark%20instances/Benchmark%20Set%201) | Scalability of `E-SRTI-ASP` for `whatif` queries |
| **Figure 5**  | [Benchmark Set 1](./benchmark%20instances/Benchmark%20Set%201) & [Benchmark Set 2](./benchmark%20instances/Benchmark%20Set%202) | Grounding time and program size for `whatif` queries  |
| **Figure 6**  | [Benchmark Set 1](./benchmark%20instances/Benchmark%20Set%201) | Scalability of `E-SRTI-ASP` for `howfair` queries|


Further details about the generation of the benchmark instances and the experimental setup are provided in the paper.

---
## Repository Structure

```text
benchmark instances/
├── Benchmark Set 1/  # 38 Personalized-SRTI instances with at least one stable matching, for why, whatif, howfair, and whynone queries 
├── Benchmark Set 2/  # 16 challenging SRTI instances with many stable matchings, for why, whatif, and whynone queries
├── Benchmark Set 3/  # 40 challenging SRTI instances that admit no stable matching, for whynone queries

```
