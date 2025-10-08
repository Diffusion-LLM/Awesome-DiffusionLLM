# Awesome-DiffusionLLM

A curated list of awesome research papers and resources on Diffusion Language Models (DLMs). Diffusion models have emerged as a promising alternative to autoregressive models for text generation, offering parallel generation capabilities and unique advantages in various scenarios.

## Tag Legend

**Task:** ![General](https://img.shields.io/badge/Task-General-blue) ![Code](https://img.shields.io/badge/Task-Code-green)  
**Methods:** ![Inference](https://img.shields.io/badge/Methods-Inference-orange)  
**Training Stage:** ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple) ![SFT](https://img.shields.io/badge/Stage-SFT-yellow) ![RL](https://img.shields.io/badge/Stage-RL-pink)

## 2025 Papers

⭐ **Large Language Diffusion Models (LLaDA)**  
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)  
*Shen Nie et al.*  
[[Paper]](https://arxiv.org/abs/2502.09992) [[Project]](https://ml-gsai.github.io/LLaDA-demo/)  
Introduces LLaDA, a diffusion model trained from scratch that challenges the dominance of autoregressive models and demonstrates competitive performance.

**Continuous Diffusion Model for Language Modeling**  
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)  
*Jaehyeong Jo, Sung Ju Hwang*  
[[Paper]](http://arxiv.org/abs/2502.11564)  
Proposes a continuous diffusion model that incorporates the geometry of categorical distributions and establishes connections between discrete diffusion and continuous flow.

**d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning**  
![General](https://img.shields.io/badge/Task-General-blue) ![SFT](https://img.shields.io/badge/Stage-SFT-yellow) ![RL](https://img.shields.io/badge/Stage-RL-pink)  
*Siyan Zhao et al.*  
[[Paper]](http://arxiv.org/abs/2504.12216) [[Project]](https://dllm-reasoning.github.io/)  
Framework to adapt pre-trained masked dLLMs into reasoning models via SFT and novel critic-free RL algorithm diffu-GRPO.

**LLaDA 1.5: Variance-Reduced Preference Optimization for Large Language Diffusion Models**  
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink)  
*Fengqi Zhu et al.*  
[[Paper]](http://arxiv.org/abs/2505.19223) [[Project]](https://ml-gsai.github.io/LLaDA-1.5-Demo/)  
Proposes VRPO framework for aligning diffusion models with human preferences, achieving significant improvements across benchmarks.

**Reasoning with Exploration: An Entropy Perspective**  
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink)  
*Daixuan Cheng et al.*  
[[Paper]](http://arxiv.org/abs/2506.14758)  
Examines the relationship between entropy and exploratory reasoning in LMs, introducing entropy-based advantage function augmentation.

**DiffuCoder: Understanding and Improving Masked Diffusion Models for Code Generation**  
![Code](https://img.shields.io/badge/Task-Code-green) ![RL](https://img.shields.io/badge/Stage-RL-pink)  
*Shansan Gong et al.*  
[[Paper]](http://arxiv.org/abs/2506.20639) [[Code]](https://github.com/apple/ml-diffucoder)  
Investigates dLLMs for code generation, proposing coupled-GRPO and achieving +4.4% improvement on EvalPlus benchmark.

**Diffusion Beats Autoregressive in Data-Constrained Settings**  
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)  
*Mihir Prabhudesai et al.*  
[[Paper]](http://arxiv.org/abs/2507.15857) [[Project]](https://diffusion-scaling.github.io)  
Systematically studies masked diffusion models in data-constrained settings, showing they significantly outperform AR models when data is scarce.

**Seed Diffusion: A Large-Scale Diffusion Language Model with High-Speed Inference**  
![Code](https://img.shields.io/badge/Task-Code-green) ![Inference](https://img.shields.io/badge/Methods-Inference-orange)  
*Yuxuan Song et al.*  
[[Paper]](http://arxiv.org/abs/2508.02193) [[Demo]](https://studio.seed.ai/exp/seed_diffusion/)  
Achieves remarkable inference speed of 2,146 token/s while maintaining competitive performance, setting new state-of-the-art on speed-quality frontier.

**Diffusion LLMs Can Do Faster-Than-AR Inference via Discrete Diffusion Forcing**  
![General](https://img.shields.io/badge/Task-General-blue) ![Inference](https://img.shields.io/badge/Methods-Inference-orange)  
*Xu Wang et al.*  
[[Paper]](http://arxiv.org/abs/2508.09192) [[Code]](https://github.com/zhijie-group/Discrete-Diffusion-Forcing)  
Proposes D2F strategy enabling block-wise autoregressive generation and achieving >2.5× speedup over LLaMA3 and Qwen2.5.

**Reinforced Context Order Recovery for Adaptive Reasoning and Planning**  
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink)  
*Long Ma et al.*  
[[Paper]](http://arxiv.org/abs/2508.13070)  
Proposes ReCOR framework for extracting adaptive token generation orders to improve reasoning and planning capabilities.

**DPad: Efficient Diffusion Language Models with Suffix Dropout**  
![General](https://img.shields.io/badge/Task-General-blue) ![Inference](https://img.shields.io/badge/Methods-Inference-orange)  
*Xinhua Chen et al.*  
[[Paper]](http://arxiv.org/abs/2508.14148) [[Code]](https://github.com/Crys-Chen/DPad)  
Training-free method that delivers up to 61.4× speedup over vanilla dLLMs while maintaining comparable accuracy.

⭐ **Dream 7B: Diffusion Large Language Models**  
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)  
*Jiacheng Ye et al.*  
[[Paper]](http://arxiv.org/abs/2508.15487)  
The most powerful open diffusion large language model to date, demonstrating superior planning abilities and inference flexibility.

**Scaling Diffusion Language Models via Adaptation from Autoregressive Models**  
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)  
*Shansan Gong et al.*  
[[Paper]](http://arxiv.org/abs/2410.17891) [[Code]](https://github.com/HKUNLP/DiffuLLaMA)  
Proposes adapting AR models to build diffusion models (DiffuGPT, DiffuLLaMA), showing systematic evaluation and competitive performance.

**Latent Diffusion for Language Generation** \
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple) \
*Justin Lovelace et al.* \
[[Code]](https://github.com/justinlovelace/latent-diffusion-for-language) \
Demonstrates that continuous diffusion models can be learned in the latent space of language autoencoders for effective text generation.

**CreditDecoding: Accelerating Parallel Decoding in Diffusion Large Language Models with Trace Credits** \
![General](https://img.shields.io/badge/Task-General-blue) ![Inference](https://img.shields.io/badge/Methods-Inference-orange) \
[[Paper]](https://arxiv.org/abs/2510.06133) \
Introduces Trace Credit concept to quantify token convergence potential and accelerate confidence convergence of underconfident tokens, achieving 5.48× speedup on LLaDA-8B-Instruct with improved performance.

**LaDiR: Latent Diffusion Enhances LLMs for Text Reasoning** \
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink) \
*Haoqiang Kang et al.* \
[[Paper]](https://arxiv.org/abs/2510.04573) \
Unifies continuous latent representation with iterative refinement capabilities via VAE-based latent reasoning space and latent diffusion model, enabling longer horizon reasoning with adaptive test-time compute.

**Finish First, Perfect Later: Test-Time Token-Level Cross-Validation for Diffusion Large Language Models** \
![General](https://img.shields.io/badge/Task-General-blue) ![Inference](https://img.shields.io/badge/Methods-Inference-orange) \
*Runchu Tian et al.* \
[[Paper]](https://arxiv.org/abs/2510.05090) \
Proposes Tolerator, a training-free decoding strategy leveraging cross-validation among predicted tokens to allow revision of accepted tokens, addressing the limitation that early mistakes persist across iterations.

**Principled and Tractable RL for Reasoning with Diffusion Language Models**
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink) \
[[Paper]](https://arxiv.org/abs/2510.04019) \
Presents AGRPO, the first principled and tractable online RL algorithm for dLLMs using Monte Carlo sampling for unbiased policy gradients, achieving +7.6% on GSM8K and 1.3× gains over comparable RL methods.

**Coevolutionary Continuous Discrete Diffusion: Make Your Diffusion Language Model a Latent Reasoner** \
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple) \
*Cai Zhou et al.* \
[[Paper]](https://arxiv.org/abs/2510.03206) \
Proposes CCDD with joint multimodal diffusion process on continuous and discrete spaces, leveraging single model to simultaneously denoise, combining expressivity of continuous diffusion with trainability of discrete tokens.

**Why mask diffusion does not work**\
![General](https://img.shields.io/badge/Task-General-blue)\
*Authors et al.*\
[[Paper]](https://arxiv.org/abs/2510.03289)\
Demonstrates theoretical and empirical analysis showing mask diffusion predictions collapse to marginal distributions, lacking joint coherence and being essentially autoregressive, misaligning training with inference.

**Training Optimal Large Diffusion Language Models**\
![General](https://img.shields.io/badge/Task-General-blue) ![Pre%20training](https://img.shields.io/badge/Stage-Pre--training-purple)\
*Jinjie Ni al.*\
[[Paper]](https://arxiv.org/abs/2510.03280)\
Introduces Quokka, the first systematic scaling law for diffusion language models encompassing compute- and data-constrained regimes, showing masked diffusion consistently outperforms uniform diffusion and AR models under data constraints.

**DiffuSpec: Unlocking Diffusion Language Models for Speculative Decoding**\
![General](https://img.shields.io/badge/Task-General-blue) ![Inference](https://img.shields.io/badge/Methods-Inference-orange)\
*Guanghao Li et al.*\
[[Paper]](https://arxiv.org/abs/2510.02358)\
Training-free framework using pretrained DLM for multi-token drafts in speculative decoding with causal-consistency path search and adaptive draft-length controller, yielding up to 3× wall-clock speedup.

**Revolutionizing Reinforcement Learning Framework for Diffusion Large Language Models**\
![General](https://img.shields.io/badge/Task-General-blue) ![RL](https://img.shields.io/badge/Stage-RL-pink)\
[[Paper]](https://arxiv.org/abs/2509.06949)\
Proposes TraceRL, a trajectory-aware RL framework with diffusion-based value model, deriving TraDo models where TraDo-4B-Instruct outperforms 7B-scale AR models on complex math reasoning tasks with 18.1% gain on MATH500.

**DIFFA: Large Language Diffusion Models Can Listen and Understand**\
![General](https://img.shields.io/badge/Task-General-blue) ![SFT](https://img.shields.io/badge/Stage-SFT-yellow)\
*Jiaming Zhou et al.*\
[[Paper]](https://arxiv.org/abs/2507.18452)\
First diffusion-based large audio-language model integrating frozen diffusion LM with dual-adapter architecture for speech understanding, achieving competitive performance on MMSU, MMAU, and VoiceBench benchmarks.



**SDAR: Synergy of Diffusion and AutoRegression**\
![General](https://img.shields.io/badge/Task-General-blue) ![SFT](https://img.shields.io/badge/Stage-SFT-yellow)\
*Shuang Cheng et al.*\
[[Paper]](https://jetastra.github.io/SDAR/)\
Propose SDAR (Synergy of Diffusion and AutoRegression), a large-scale diffusion language model that unites the complementary strengths of autoregressive and discrete diffusion modeling.


## Surveys & Resources

- **A Survey on Diffusion Language Models** [[Paper]](https://arxiv.org/abs/2508.10875) [[Project]](https://github.com/VILA-Lab/Awesome-DLMs)

- **Dream-Coder 7B: An Open Diffusion Language Model for Code** [[Paper]](https://arxiv.org/abs/2509.01142)

- **Time Is a Feature: Exploiting Temporal Dynamics in Diffusion Language Models** [[Paper]](https://arxiv.org/abs/2508.09138)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request to add new papers, fix errors, or improve the organization.

## License

This project is licensed under the same license as the original repository.
