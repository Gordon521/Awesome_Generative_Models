# Awesome_Generative_Models
Awesome Generative Models is a curated repository tracking progress in generative AI, serving as a resource for state-of-the-art papers, code, and datasets. *(The project is under active development, and contributions are warmly welcome!)*
# Table of Contents
- [Papers](#papers)
  - [Surveys](#surveys)
  - [Foundation Models](#foundation-models)
  - [Dataset](#datasets)
  - [Tokenizer](#Tokenizer)
  - [Diffusion models](#diffusion-models)
  - [Autogressive models](#autogressive-models)
  - [Table]
## Surveys
* A Survey on Generative Diffusion Models. [[Paper]](https://ieeexplore.ieee.org/abstract/document/10419041)
* Personalized Image Generation with Deep Generative Models: A Decade Survey. [[Paper]](https://arxiv.org/abs/2502.13081)
## Foundation Models
- `LDM` **High-Resolution Image Synthesis with Latent Diffusion Models.**
  [[Paper](https://arxiv.org/abs/2112.10752)] [[Code](https://github.com/CompVis/latent-diffusion)]
- `DALL·E 1` **Zero-Shot Text-to-Image Generation.**
  [[Paper](https://arxiv.org/abs/2102.12092)] [[Code](https://github.com/openai/DALL-E)]
- `DALL·E 2` **Hierarchical Text-Conditional Image Generation with CLIP Latents.** 
  [[Paper](https://arxiv.org/abs/2204.06125)] 
- `Imagen` **Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding.**
  [[Paper](https://arxiv.org/abs/2205.11487)]
- `Parti` **Scaling Autoregressive Models for Content-Rich Text-to-Image Generation.**
  [[Paper](https://arxiv.org/abs/2206.10789)]
- `StyleGAN` **A Style-Based Generator Architecture for Generative Adversarial Networks.**
  [[Paper](https://arxiv.org/abs/1812.04948)] [[Code](https://github.com/NVlabs/stylegan)]
- `StyleGAN 2` **Analyzing and Improving the Image Quality of StyleGAN.**
  [[Paper](https://arxiv.org/abs/1912.04958)] [[Code](https://github.com/NVlabs/stylegan2)]
- `StyleGAN 3` **Alias-Free Generative Adversarial Networks.**
  [[Paper](https://arxiv.org/abs/2106.12423)] [[Code](https://github.com/NVlabs/stylegan3)]​
## Dataset
## Tokenizer
- `VAE` **Auto-Encoding Variational Bayes**
  [[Paper](https://arxiv.org/abs/1312.6114)]
- `VQVAE` **Neural Discrete Representation Learning**
  [[Paper](https://arxiv.org/abs/1711.00937)]
- `VQVAE 2` **Generating Diverse High-Fidelity Images with VQ-VAE-2**
  [[Paper](https://arxiv.org/abs/1906.00446)]
- `VAVAE` **Neural Discrete Representation Learning**
  [[Paper](https://arxiv.org/abs/2412.04852)] [[Code](https://github.com/hustvl/LightningDiT)]
- `Titok` **An Image is Worth 32 Tokens for Reconstruction and Generation**
  [[Paper](https://arxiv.org/abs/2406.07550)] [[Code](https://github.com/bytedance/1d-tokenizer)]
- `TA-Titok` **Democratizing Text-to-Image Masked Generative Models with Compact Text-Aware One-Dimensional Tokens**
  [[Paper](https://arxiv.org/abs/2501.07730)] [[Code](https://github.com/bytedance/1d-tokenizer)]
- `MAEtok` **Masked Autoencoders Are Effective Tokenizers for Diffusion Models**
  [[Paper](https://arxiv.org/abs/2502.03444)] [[Code](https://github.com/Hhhhhhao/continuous_tokenizer)]
## Diffusion models
Please also see a LaTeX table (located in xxx) containing a curated list of references from this repository for your convenience in citing directly within your papers.
(To be revised)
- `REPA` **Representation Alignment for Generation: Training Diffusion Transformers Is Easier Than You Think**
  [[Paper](https://arxiv.org/abs/2410.06940)] [[Code](https://github.com/sihyun-yu/REPA)]
- `REG` **Representation Entanglement for Generation: Training Diffusion Transformers Is Much Easier Than You Think**
  
  [[Paper](https://arxiv.org/abs/2507.01467)] [[Code](https://github.com/Martinser/REG)] [[论文解读](https://zhuanlan.zhihu.com/p/1952346823168595518)]
- `REPA-E` **REPA-E: Unlocking VAE for End-to-End Tuning with Latent Diffusion Transformers**
  [[Paper](https://arxiv.org/abs/2504.10483)] [[Code](https://github.com/End2End-Diffusion/REPA-E)]
- `RAE` **Diffusion Transformers with Representation Autoencoders**
  [[Paper](https://arxiv.org/abs/2510.11690)] [[Code](https://github.com/bytetriper/RAE)]
- `SIT` **SiT: Exploring Flow and Diffusion-based Generative Models with Scalable Interpolant Transformers**
  [[Paper](https://arxiv.org/abs/2401.08740)] [[Code](https://github.com/willisma/SiT)]
- `DIT` **Scalable Diffusion Models with Transformers**
  [[Paper](https://arxiv.org/abs/2212.09748)] [[Code](https://www.github.com/facebookresearch/DiT)]
- `MDT` **Masked Diffusion Transformer is a Strong Image Synthesizer**
  [[Paper](https://arxiv.org/abs/2303.14389)] [[Code](https://github.com/sail-sg/MDT)]

## Autogressive models
Please also see a LaTeX table (located in xxx) containing a curated list of references from this repository for your convenience in citing directly within your papers.
(To be revised)
- `MAR` **Autoregressive Image Generation without Vector Quantization**
  [[Paper](https://arxiv.org/abs/2410.06940)] [[Code](https://github.com/LTH14/mar)]
- `Llamagen` **Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation**
  [[Paper](https://arxiv.org/abs/2410.06940)] [[Code](https://github.com/FoundationVision/LlamaGen)]
- `show-o` **Show-o: One Single Transformer to Unify Multimodal Understanding and Generation**
  [[Paper](https://arxiv.org/abs/2408.12528)] [[Code](https://github.com/showlab/Show-o)]
- `DC-AR` **DC-AR: Efficient Masked Autoregressive Image Generation with Deep Compression Hybrid Tokenizer**
  [[Paper](https://arxiv.org/abs/2507.04947)] [[Code](https://github.com/dc-ai-projects/DC-AR)]
- `NEPA` **Next-Embedding Prediction Makes Strong Vision Learners**
  [[Paper](https://arxiv.org/abs/2512.16922)] [[Code](https://github.com/SihanXU/nepa)]

## Table
| Method | Epochs | #Params | gFID↓ | IS↑ | Prec.↑ | Rec.↑ | gFID↓ | IS↑ | Prec.↑ | Rec.↑ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| | | | **Generation@256 w/o guidance** | | | | **Generation@256 w/ guidance** | | | |
| **Autoregressive** | | | | | | | | | | |
| VAR | 350 | 2.0B | 1.92 | 323.1 | 0.82 | 0.59 | 1.73 | 350.2 | 0.82 | 0.60 |
| MAR | 800 | 943M | 2.35 | 227.8 | 0.79 | 0.62 | 1.55 | 303.7 | 0.81 | 0.62 |
| xAR | 800 | 1.1B | - | - | - | - | 1.24 | 301.6 | 0.83 | 0.64 |
| **Pixel Diffusion** | | | | | | | | | | |
| ADM | 400 | 554M | 10.94 | 101.0 | 0.69 | 0.63 | 3.94 | 215.8 | 0.83 | 0.53 |
| RIN | 480 | 410M | 3.42 | 182.0 | - | - | - | - | - | - |
| PixelFlow | 320 | 677M | - | - | - | - | 1.98 | 282.1 | 0.81 | 0.60 |
| PixNerd | 160 | 700M | - | - | - | - | 2.15 | 297.0 | 0.79 | 0.59 |
| SiD2 | 1280 | - | - | - | - | - | 1.38 | - | - | - |
| **Latent Diffusion** | | | | | | | | | | |
| DiT | 1400 | 675M | 9.62 | 121.5 | 0.67 | 0.67 | 2.27 | 278.2 | 0.83 | 0.57 |
| MaskDiT | 1600 | 675M | 5.69 | 177.9 | 0.74 | 0.60 | 2.28 | 276.6 | 0.80 | 0.61 |
| SiT | 1400 | 675M | 8.61 | 131.7 | 0.68 | 0.67 | 2.06 | 270.3 | 0.82 | 0.59 |
| MDTv2 | 1080 | 675M | - | - | - | - | 1.58 | 314.7 | 0.79 | 0.65 |
| VA-VAE | 80 | 675M | 4.29 | - | - | - | - | - | - | - |
| REPA | 80 | 675M | 7.90 | 122.6 | 0.70 | 0.65 | - | - | - | - |
| REPA-E | 80 | 675M | 1.70 | 159.8 | 0.77 | 0.63 | 1.67 | 266.3 | 0.80 | 0.63 |
