# Arabic Visual Question Generation (VQG)
# Generating Context-Aware Questions from Images Using Deep Learning

## Abstract

This project presents a deep learning-based framework for Visual Question Generation (VQG) focused on the Arabic language. The primary objective is to generate natural, meaningful, and context-aware Arabic questions from input images. To achieve this, the system utilizes a **Bottom-Up and Top-Down Attention** mechanism.

The model architecture integrates **Faster R-CNN** with a ResNet-101 backbone to extract salient visual features (Bottom-Up Attention) and employs a two-layer **LSTM** with attention mechanisms to generate linguistic sequences (Top-Down Attention). [cite_start]The model was trained on the **MS-COCO 2014** dataset, which was translated and adapted to create an Arabic VQG dataset specifically for this research[cite: 33, 34, 35, 39].

## Code Adaptation and Modifications

The core implementation of this project is based on the "Image Captioning using Bottom-Up Top-Down Attention" repository by Pooja Hira, available at:
[https://github.com/poojahira/image-captioning-bottom-up-top-down](https://github.com/poojahira/image-captioning-bottom-up-top-down)

[cite_start]Significant modifications were made to the original codebase to align with the specific requirements of this research[cite: 712, 713, 714]:

1.  **Task Adaptation:** The architecture was redesigned to perform **Visual Question Generation (VQG)** instead of Image Captioning.
2.  **Language Support:** The decoder and data processing pipelines were modified to support the **Arabic language**, including specific preprocessing steps for Arabic text (normalization and cleaning).
3.  **Environment Updates:** The Python version and library dependencies (including PyTorch) were updated to ensure compatibility with modern training environments (e.g., Google Colab and Vast.ai).
4.  **Dataset Structure:** Custom modules were developed to handle the translated MS-COCO dataset, including data loading, evaluation metrics adaptation (BLEU, METEOR, ROUGE, CIDEr, BERTScore), and HDF5 feature integration.


## Team Members

<div align="left">

[![Tala Alhadawi – LinkedIn](https://img.shields.io/badge/LinkedIn-Tala_Alhadawi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/talamohammed11?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
[![Tala Alhadawi – GitHub](https://img.shields.io/badge/GitHub-talamh0-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/talamh0)

[![Joud Alsadhan – LinkedIn](https://img.shields.io/badge/LinkedIn-Joud_Alsadhan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joud-alsadhan-b95a95239/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
[![Joud Alsadhan – GitHub](https://img.shields.io/badge/GitHub-joudalsadhan-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joudalsadhan)

[![Reem Alsuhaim – LinkedIn](https://img.shields.io/badge/LinkedIn-Reem_Alsuhaim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/reem-alsuhaim-185639364?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
[![Reem Alsuhaim – GitHub](https://img.shields.io/badge/GitHub-Reem--Alsuhaim-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Reem-Alsuhaim)

[![Hissah Ibn Qurmulah – LinkedIn](https://img.shields.io/badge/LinkedIn-Hissah_Ibn_Qurmulah-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hissah-ibn-qurmulah-4342a2241/?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
[![Hissah Ibn Qurmulah – GitHub](https://img.shields.io/badge/GitHub-Hissah--IbnQurmulah-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hissah-IbnQurmulah)

[![Remas M. Almania – LinkedIn](https://img.shields.io/badge/LinkedIn-Remas_M._Almania-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/remas-m-almania-7522ba26a/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
[![Remas M. Almania – GitHub](https://img.shields.io/badge/GitHub-RemasAlmania-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RemasAlmania)

</div>

