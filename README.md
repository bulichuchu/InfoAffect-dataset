# InfoAffect Dataset 📊

Dataset repository for the paper **“InfoAffect: Affective Annotations of Infographics in Information Spread”**.  
This repo hosts the **corresponding dataset** presented in the paper.  
For more details, please refer to our paper on arXiv: [arXiv Link](https://arxiv.org/abs/2511.06404) 📄

---

## Overview 🔍
Infographics are widely used in social media to convey complex information, yet how they influence users' affects remains underexplored due to the scarcity of relevant datasets. To address this gap, we introduce a 3.5k-sample affect-annotated InfoAffect dataset, which combines textual content with real-world infographics. We first collected the raw data from six fields and aligned it via preprocessing, the accompanied-text-priority method, and three strategies to guarantee quality and compliance. After that, we constructed an Affect Table to constrain annotation. We used five state-of-the-art multimodal large language models (MLLMs) to analyze both modalities, and their outputs were fused with the Reciprocal Rank Fusion (RRF) algorithm to yield robust affects and confidences. We conducted a user study with two experiments to validate usability and assess the InfoAffect dataset using the Composite Affect Consistency Index (CACI), achieving an overall score of 0.608, which indicates high accuracy.

---

## Data Access 📦
The InfoAffect dataset is hosted on Hugging Face: 🤗 [Hugging Face Link](https://huggingface.co/datasets/fushuai0823/InfoAffect)

The complete infographics are also available on Google Drive: 📁 [Google Drive Link](https://drive.google.com/file/d/104is1SArDGYMWGDGQtIgfLsexsgDHQPk/view?usp=sharing)
