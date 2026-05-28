

Hello! I'm Ivi, a 3rd year PhD candidate at the [Max Planck Institute for Software Systems](https://www.mpi-sws.org/),
under the supervision of [Dr. Manuel Gomez-Rodriguez](https://people.mpi-sws.org/~manuelgr/index.html).
My research interests lie broadly in the area of Human-Centered Machine Learning. Currently, I am working on LLM evaluation and uncertainty.


Before joining MPI-SWS, I received my MEng in Electrical and Computer Engineering from the [National Technical University of Athens](https://www.ece.ntua.gr/en), 
where I did my diploma thesis with Prof. Symeon Papavassiliou.
During my undergraduate studies, I was fortunate to briefly work at [ETH Zürich](https://ethz.ch/en.html)
under Dr. Fanny Yang, and at the [National Observatory of Athens](https://www.noa.gr/en/), where I contributed to the development of the [Flash Detection Software](https://kryoneri.astro.noa.gr/en/flash-detection-software/).

**My Research:**
I study how the inherent stochasticity in LLMs can lead to evaluation instability and fairness concerns, and how we can account for and control this stochasticity. 
For example, inference randomness can skew model rankings [[1](#coupled-eval)], obfuscate model biases [[2](#cf-gen)], and cause identical outputs to have arbitrarily different tokenizations and costs [[5](#multiplicity)].
To address such challenges, I develop statistical and causal methods for LLM evaluation and oversight, proposing how to reliably use LLM-as-a-judge [[3](#ppr)], speed up evaluation pipelines [[1](#coupled-eval)], determine if LLM agents' tool calls comply with policy manuals [[4](#mantra)], and ensure deterministic tokenization and pricing [[5](#multiplicity)].
Overall, my goal is to make LLM systems and evaluations more predictable and trustworthy.

## Recent news

- **July 2026:** Our preprint [MANTRA: Synthesizing SMT-Validated Compliance Benchmarks for Tool-Using LLM Agents](https://arxiv.org/abs/2605.06334) will be presented in the _Failure Modes in Agentic AI_ workshop at ICML 2026.

- **May 2026:** Our paper [Evaluation of Large Language Models via Coupled Token Generation](https://arxiv.org/abs/2502.01754) was presented in AISTATS 2026.

- **May 2026:** In our new [preprint](https://arxiv.org/abs/2605.06334), we show how to use SMT validation to reliably generate policy compliance benchmarks for LLM agents.


## Publications


1. <a id="coupled-eval"></a> **Evaluation of Large Language Models via Coupled Token Generation** \
  _AISTATS 2026_ \
  _also presented at the Building Trust in LLMs and LLM Applications workshop at ICLR 2025_ \
  Nina Corvelo Benz, Stratis Tsirtis, Eleni Straitouri, **Ivi Chatzi**, Ander Artola Velasco, Suhas Thejaswi, Manuel Gomez-Rodriguez \
  [[arxiv](https://arxiv.org/abs/2502.01754)]
  [[pdf](https://qvapil.github.io/files/2502.01754v1.pdf)]
  [[code](https://github.com/Networks-Learning/coupled-llm-evaluation)]
  [[poster](https://qvapil.github.io/files/coupled_eval_poster.png)]


2. <a id="cf-gen"></a> **Counterfactual Token Generation in Large Language Models** \
  _CLeaR 2025_ \
  _also presented at the Causality and Large Models workshop at NeurIPS 2024_ \
  **Ivi Chatzi**\*, Nina Corvelo Benz\*, Eleni Straitouri\*, Stratis Tsirtsis\*, Manuel Gomez-Rodriguez \
  [[arxiv](https://arxiv.org/abs/2409.17027)]
  [[pdf](https://qvapil.github.io/files/cf-llms-v3.pdf)]
  [[code](https://github.com/Networks-Learning/counterfactual-llms)]
  [[poster](https://qvapil.github.io/files/poster_cf-llm_neurips.pdf)]


3. <a id="ppr"></a> **Prediction-Powered Ranking of Large Language Models** \
  _NeurIPS 2024_ \
  _also presented at the Human-centered Evaluation and Auditing of Language Models workshop at CHI 2024_ \
  **Ivi Chatzi**, Eleni Straitouri, Suhas Thejaswi, Manuel Gomez-Rodriguez \
  [[arxiv](https://arxiv.org/abs/2402.17826)]
  [[pdf](https://qvapil.github.io/files/2402.17826v3.pdf)]
  [[code](https://github.com/Networks-Learning/prediction-powered-ranking)]
  [[poster](https://qvapil.github.io/files/poster_ppr_neurips.pdf)]

### Workshops


4. <a id="mantra"></a> **MANTRA: Synthesizing SMT-Validated Compliance Benchmarks for Tool-Using LLM Agents** \
  _Failure Modes in Agentic AI workshop at ICML 2026_ \
  Ashwani Anand, **Ivi Chatzi**, Ritam Raha, Anne-Kathrin Schmuck \
  [[arxiv](https://arxiv.org/abs/2605.06334)]
  [[pdf](https://qvapil.github.io/files/2605.06334v1.pdf)]
  <!-- [[code](https://anonymous.4open.science/r/mantra-for-compliance/README.md)]
  [[data](https://huggingface.co/datasets/mantra-anon/MANTRA)] -->


5. <a id="multiplicity"></a> **Tokenization Multiplicity Leads to Arbitrary Price Variation in LLM-as-a-service** \
  _Tokenization workshop at ICML 2025_ \
  **Ivi Chatzi**, Nina Corvelo Benz, Stratis Tsirtsis, Manuel Gomez-Rodriguez \
  [[arxiv](https://www.arxiv.org/abs/2506.06446)]
  [[pdf](https://qvapil.github.io/files/paper-multiplicity.pdf)]
  [[code](https://github.com/Human-Centric-Machine-Learning/Tokenization-Multiplicity)]
  [[data](https://huggingface.co/datasets/Human-Centric-Machine-Learning/tokenization-multiplicity-data)]
  [[poster](https://qvapil.github.io/files/canonical-autoreg-poster.pdf)]

<!-- - **Canonical Autoregressive Generation** \
_TokShop at ICML, Vancouver, 2025_ \
Ivi Chatzi, Nina Corvelo Benz, Stratis Tsirtsis, Manuel Gomez-Rodriguez \
[[arxiv](https://www.arxiv.org/abs/2506.06446)]
[[pdf](https://qvapil.github.io/files/2506.06446v1.pdf)] -->

<!-- - **Evaluation of Large Language Models via Coupled Token Generation** \
_Building Trust workshop at ICLR, Signapore, 2025_ \
Nina Corvelo Benz, Stratis Tsirtis, Eleni Straitouri, Ivi Chatzi, Ander Artola Velasco, Suhas Thejaswi, Manuel Gomez-Rodriguez \
[[arxiv](https://arxiv.org/abs/2502.01754)]
[[pdf](https://qvapil.github.io/files/2502.01754v1.pdf)]
[[code](https://github.com/Networks-Learning/coupled-llm-evaluation)]
[[poster](https://qvapil.github.io/files/poster-coupled-eval.pdf)]

- **Counterfactual Token Generation in Large Language Models** \
_C❤LM workshop at NeurIPS, Vancouver, 2024_ \
Ivi Chatzi*, Nina Corvelo Benz*, Eleni Straitouri*, Stratis Tsirtsis*, Manuel Gomez-Rodriguez \
[[arxiv](https://arxiv.org/abs/2409.17027)]
[[pdf](https://qvapil.github.io/files/cf-llms-v3.pdf)]
[[code](https://github.com/Networks-Learning/counterfactual-llms)]
[[poster](https://qvapil.github.io/files/poster_cf-llm_neurips.pdf)]

- **Prediction-Powered Ranking of Large Language Models** \
_HEAL workshop at CHI, Honolulu, 2024_ \
Ivi Chatzi, Eleni Straitouri, Suhas Thejaswi, Manuel Gomez-Rodriguez \
[[arxiv](https://arxiv.org/abs/2402.17826)]
[[pdf](https://qvapil.github.io/files/2402.17826v3.pdf)]
[[code](https://github.com/Networks-Learning/prediction-powered-ranking)]
[[poster](https://qvapil.github.io/files/poster_ppr_chi.pdf)] -->

<!-- ### Pre-prints -->


