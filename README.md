# Leanabell-Prover-V2

![Last Commit](https://img.shields.io/github/last-commit/Leanabell-LM/Leanabell-Prover-V2)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-blue.svg)]((https://github.com/Leanabell-LM/Leanabell-Prover-V2/graphs/commit-activity))
![Contributing](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

**[[arXiv]](https://arxiv.org/abs/2507.08649) | [[Codes]](https://github.com/Leanabell-LM/Leanabell-Prover-V2) | [[🤗 Huggingface]]** <br> 
Xingguang Ji, Yahui Liu, Qi Wang$^{\heartsuit}$, Jingyuan Zhang, Yang Yue, Rui Shi, Chenxi Sun, Fuzheng Zhang,  Guorui Zhou, Kun Gai

## Abstract

We introduce our Leanabell-Prover-V2, a 7B large language models (LLMs) that can produce formal theorem proofs in Lean 4, with verifier-integrated Long Chain-of-Thoughts (CoT). Following our previous work Leanabell-Prover-V1, we continual to choose to posttrain existing strong prover models for further performance improvement. In our V2 version, we mainly upgrade the Reinforcement Learning (RL) with feedback provided by the Lean 4 verifier. Crucially, verifier feedback, such as indicating success or detailing specific errors, allows the LLM to become ``self-aware'' of the correctness of its own reasoning process and learn to reflexively correct errors. Leanabell-Prover-V2 directly optimizes LLM reasoning trajectories with multi-turn verifier interactions, together with feedback token masking for stable RL training and a simple reward strategy. Experiments show that Leanabell-Prover-V2 improves performance by 3.2\% (pass@128) with Kimina-Prover-Preview-Distill-7B and 2.0\% (pass@128) with DeepSeek-Prover-V2-7B on the MiniF2F test set.

<p align="center">
<img src="figures/teaser" width="800px"/>
<br>
</p>

Source codes and models are coming soon ...

