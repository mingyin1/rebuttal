**Table A1.** Statistical significance tests between major model tiers (McNemar’s test for TSR; Wilcoxon test for ARS).

| Comparison Pair | McNemar’s p-value (TSR) | Wilcoxon p-value (ARS) | Significance |
| :--- | :---: | :---: | :---: |
| GPT-5 vs. o3 | $p = 0.013$ | $p = 0.008$ | Significant |
| GPT-5 vs. Claude-4.1-Opus (ET) | $p = 0.002$ | $p = 0.001$ | Highly Significant |
| Claude-4.1-Opus (ET) vs. Qwen3-235B | $p < 0.001$ | $p < 0.001$ | Highly Significant |
| Qwen3-235B vs. Llama-3.3-70B | $p < 0.001$ | $p < 0.001$ | Highly Significant |


**Table A2.** Strict vs. Relaxed TSR across models, and the absolute improvement under the relaxed threshold.

| Model | Strict TSR (%) | Relaxed TSR (%)| Improvement (%)|
| :--- | :---: | :---: | :---: |
| GPT-5 | 58.42 | 69.30 | +10.88 |
| o3 | 46.53 | 59.41 | +12.88 |
| Claude-4.1-Opus (ET) | 41.58 | 55.44 | +13.86 |
| Qwen3-235B  | 22.77 | 36.63 | +13.86 |
| Gemini-2.5-Flash | 10.89 | 18.81 | +7.92 |
| Llama-3.3-70B | 1.98 | 3.96 | +1.98 |



**Table A3.** Results of additional SOTA models (GPT-5.4 and Claude-4.6-Opus) compared with the previous best.

| Model | Strict TSR (%) | Relaxed TSR (%) | ARS (%) |
| :--- | :---: | :---: | :---: |
| GPT-5.4 | 67.33 | 76.24 | 79.70 |
| Claude-4.6-Opus | 64.36 | 73.26 | 78.71 |
| GPT-5 (Previous Best) | 58.42 | 69.30 | 73.02 |


**Table A4.** Comparison of ReAct vs. Plan-and-Execute (P&E) scaffolds across models (TSR and ARS).
| Model | ReAct TSR (%) | P&E  TSR (%) | ReAct ARS (%) | P&E ARS (%) |
| :--- | :---: | :---: | :---: | :---: |
| GPT-5 | **58.42** | 52.48 | **73.02** | 67.57 |
| o3 | **46.53** | 41.58 | **62.87** | 57.67 |
| Claude-4.1-Opus (ET) | **41.58** | 37.62 | **58.17** | 53.71 |
| Qwen3-235B | **22.77** | 17.82 | **35.15** | 29.21 |
| Gemini-2.5-Flash | **10.89** | 6.93 | **21.04** | 16.83 |
| Llama-3.3-70B | **1.98** | 0.99 | **5.69** | 3.96 |
