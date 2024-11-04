# Efficient Temporal Multimodal Sequences for Vision, Language, and Audio

This repository is the official implementation of the paper **Efficient Temporal Multimodal Sequences for Vision, Language, and Audio**.

## Project Overview

This code repository includes implementations of the TWM mechanism algorithm applied to nine different state-of-the-art models. The steps to run the code are as follows:

1. **Download the repository**: Clone this repository to your local environment.
2. **Data Preprocessing**: Prepare data following the preprocessing steps in each original model repository.
3. **Training TWM**: For each model, adjust the number of training epochs and relevant model-specific hyperparameters in the `main_alvs.py` file within each model’s directory. Follow the recommendations in each model's original paper for parameter settings, and then train TMW.
4. **Inference**: Set `epochs = 0` in each model's `main_alvs.py` file, and run to obtain TMW searching results.

## Models and References

1. [Cross-modal prompts: Adapting large pre-trained models for audio-visual downstream tasks](https://proceedings.neurips.cc/paper_files/paper/2023/file/af01716e08073368a7c8a62be46dba17-Paper-Conference.pdf)
2. [Tackling data bias in music-avqa: Crafting a balanced dataset for unbiased question-answering](https://openaccess.thecvf.com/content/WACV2024/papers/Liu_Tackling_Data_Bias_in_MUSIC-AVQA_Crafting_a_Balanced_Dataset_for_WACV_2024_paper.pdf)
3. [Vision transformers are parameter-efficient audio-visual learners](https://openaccess.thecvf.com/content/CVPR2023/papers/Lin_Vision_Transformers_Are_Parameter-Efficient_Audio-Visual_Learners_CVPR_2023_paper.pdf)
4. [Action knowledge for video captioning with graph neural networks](https://www.sciencedirect.com/science/article/pii/S1319157823000666)
5. [Git: A generative image-to-text transformer for vision and language](https://arxiv.org/abs/2205.14100)
6. [Narrativebridge: Enhancing video captioning with causal-temporal narrative](https://arxiv.org/abs/2406.06499)
7. [Learning video context as interleaved multimodal sequences](https://arxiv.org/abs/2407.21757)
8. [Testa: Temporal-spatial token aggregation for long-form video-language understanding](https://arxiv.org/abs/2310.19060)
9. [VindLU: A Recipe for Effective Video-and-Language Pretraining](https://arxiv.org/abs/2212.05051)
