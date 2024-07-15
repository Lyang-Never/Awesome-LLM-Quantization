![image](https://github.com/user-attachments/assets/8e11ebe6-7683-4a2a-a8ae-73f5ef3fda9c)# Awesome-LLM-Quantization
Awesome list of LLM Quantization

eg:
=========================================================================

- SparseGPT: Massive Language Models Can be Accurately Pruned in One-shot 
    - Label: <img src=https://img.shields.io/badge/unstructured-turquoise.svg ><img src=https://img.shields.io/badge/semi_structured-brightgreen.svg >
    - Author: Elias Frantar, Dan Alistarh
    - Link: https://arxiv.org/pdf/2301.00774.pdf 
    - Code: https://github.com/IST-DASLab/sparsegpt 
    - Pub: ICML 2023
    - Summary: First to prune GPT with at least 50% sparsity without any training. SparseGPT is entirely local, which only focus on weight updates without any global gradient information.

List:
=========================================================================

- OWQ: Outlier-Aware Weight Quantization for Efficient Fine-Tuning and Inference of Large Language Models
    - Label: -
    - Author: Changhun Lee, Jungyu Jin, Taesu Kim, Hyungjun Kim, Eunhyeok Park
    - Link: https://arxiv.org/abs/2306.02272
    - Code: -
    - Pub: -
- Prefixing Attention Sinks can Mitigate Activation Outliers for Large Language Model Quantization
    - Label: -
    - Author: Seungwoo Son, Wonpyo Park, Woohyun Han, Kyuyeun Kim, Jaeho Lee / POSTECH Google
    - Link: https://arxiv.org/pdf/2406.12016
    - Code: -
    - Pub: -
- GPTQ: accurate post-training quantization for generative pre-trained transformers
    - Label: -
    - Author: Elias Frantar, Saleh Ashkboos, Torsten Hoefler, Dan Alistarh
    - Link: https://arxiv.org/abs/2210.17323
    - Code: https://github.com/IST-DASLab/gptq
    - Pub: -
    - Summary: 每量化一列参数便在其他所有列加一个“补偿”，以减少整体的精度误差；即W->Q(W)的过程中，使Loss的变化最小。
- AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration
    - Label: -
    - Author: Ji Lin, Jiaming Tang, Haotian Tang, Shang Yang；MIT
    - Link: https://arxiv.org/abs/2306.00978
    - Code: https://github.com/mit-han-lab/llm-awq
    - Pub: -
    - Summary: 通过保护更"重要"的权重不进行量化，从而在不进行训练的情况下提高准确率。
- ZeroQuant: Efficient and Affordable Post-Training Quantization for Large-Scale Transformers
    - Label: -
    - Author: Zhewei Yao, Reza Yazdani Aminabadi, Minjia Zhang, Xiaoxia Wu, Conglong Li, Yuxiong He
    - Link: https://arxiv.org/abs/2206.01861
    - Code: https://github.com/kunalkumar168/ZeroQuant
    - Pub: -
- Outlier Suppression: Pushing the Limit of Low-bit Transformer Language Models
    - Label: -
    - Author:  Beihang University, SenseTime Research
    - Link: https://arxiv.org/abs/2209.13325
    - Code: https://github.com/wimh966/outlier_suppression
    - Pub: NeurIPS 2022

