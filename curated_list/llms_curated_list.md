While I am working on the blog series on [the LLaMA family of models](https://www.icodeformybhasa.com/p/the-llama-family-of-models-model), I have also put together a curated reading list of papers that chart the evolution of large language models. These papers provide crucial context for understanding the foundations of large language models and the landscape of LLMs that led to the development of systems like Meta AI, ChatGPT, and Claude, among others.

In this blog, my attempt is to create a comprehensive reading list, including some that are featured in my blog above.

### Key Research Papers on Deep Learning Architectures

- [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215). Sutskever et al., 2014, Google
- [Attention is All You Need](https://arxiv.org/abs/1706.03762). Vaswani et al., 2017, Google
- [Improving Language Understanding by Generative Pre-Training](https://www.cs.ubc.ca/~amuham01/LING530/papers/radford2018improving.pdf). Radford et al., 2018. OpenAI - GPT-1
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805). Devlin et al., 2018. Google
- [BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension](https://arxiv.org/abs/1910.13461). Lewis et al., 2019. Facebook
- [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). Radford et al., 2019. OpenAI - GPT-2
- [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683). Raffel et al., 2019. Google - T5
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165). Brown et al., 2020. OpenAI - GPT-3
- [On Layer Normalization in the Transformer Architecture](https://arxiv.org/abs/2002.04745). Xiong et al., 2020

### Survey Papers

- [A Survey of Large Language Models](https://arxiv.org/abs/2303.18223). Zhao et al., 2023. [GitHub](https://github.com/RUCAIBox/LLMSurvey)
- [Multilingual Large Language Model: A Survey of Resources, Taxonomy and Frontiers](https://arxiv.org/pdf/2404.04925). Qin et al., 2024
- [Large Language Models: A Survey](https://arxiv.org/pdf/2402.06196). Minaee et al., 2024

### Efficient Pre-training and Scaling Laws

- [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361). Kaplan et al., 2020. OpenAI
- [Scaling Language Models: Methods, Analysis & Insights from Training Gopher](https://arxiv.org/abs/2112.11446). Rae et al., 2021. DeepMind
- [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556). Hoffmann et al., 2022. DeepMind - Chinchilla
- [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135). Dao et al., 2022. Stanford University
- [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311). Chowdhery et al., 2022. Google
- [Cramming: Training a Language Model on a Single GPU in One Day](https://arxiv.org/abs/2212.14034). Hoffmann et al., 2022. DeepMind

### Survey Papers

- [Efficient Transformers: A Survey](https://arxiv.org/abs/2009.06732). Tay et al., 2020 (Revised 2022). Google
- [A Survey on Efficient Training of Transformers](https://arxiv.org/pdf/2302.01107). Zhuang et al., 2023

### Fine-tuning and Parameter-Efficient Transfer Learning

- [Parameter-Efficient Transfer Learning for NLP](https://arxiv.org/abs/1902.00751). Houlsby et al., 2019. Google [GitHub](https://github.com/google-research/adapter-bert)
- [Finetuned Language Models are Zero-Shot Learners](https://arxiv.org/abs/2109.01652). Wei et al., 2021. Google
- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685). Hu et al., 2021. Microsoft [GitHub](https://github.com/microsoft/LoRA) [Video](https://www.youtube.com/watch?v=g5HAYVz9c9A)
- [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314). Dettmers et al., 2023. University of Washington [GitHub](https://github.com/artidoro/qlora)

### Survey Papers

- [A Survey of Quantization Methods for Efficient Neural Network Inference](https://arxiv.org/abs/2103.13630). Gholami et al., 2021. UC Berkeley
- [Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning](https://arxiv.org/pdf/2303.15647). Lialin et al., 2022. UMass Lowell
- [Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond](https://arxiv.org/pdf/2304.13712). Yang et al., 2023 [GitHub](https://github.com/THUDM/ChatGLM-6B)
- [The Efficiency Spectrum of Large Language Models: An Algorithmic Survey](https://arxiv.org/abs/2312.00678). Ding et al., 2024. Microsoft

### Aligning LLMs

- [Deep Reinforcement Learning from Human Preferences](https://arxiv.org/abs/1706.03741). Christiano et al., 2017 (Revised 2023). Google
- [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593). Ziegler et al., 2019 (Revised 2020)
- [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155). Ouyang et al., 2022. OpenAI - InstructGPT
- [Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/pdf/2204.05862). Bia et al., 2022. Anthropic
- [Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/pdf/2209.07858). Ganguli et al., 2022. Anthropic
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/pdf/2212.08073). Bia et al., 2022. Anthropic

### Survey Papers

- [Aligning Large Language Models with Human: A Survey](https://arxiv.org/pdf/2307.12966). Wang et al., 2023. Huawei Noah’s Ark Lab
- [Large Language Model Alignment: A Survey](https://arxiv.org/pdf/2309.15025). Shen et al., 2023. Tianjin University

Note, this is not an exhaustive reading list, and I will be updating it as I come across any new paper while I work on #icodeformyभाषा! There will be more of such reading lists in the future for different areas within natural language processing.
