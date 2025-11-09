# InfoAffect-Dataset

Dataset repository for the paper **“InfoAffect: A Dataset for Affective Analysis of Infographics”**.  
This repo hosts the **corresponding dataset** presented in the paper.

---

## Overview
Infographics are widely used to convey complex information, yet their affective dimensions remain underexplored due to the scarcity of data resources. We introduce a 3.5k-sample affect-annotated InfoAffect dataset, which combines textual content with real-world infographics. We first collect the raw data from six domains and aligned them via preprocessing, the accompanied-text-priority method, and three strategies to guarantee the quality and compliance. After that we construct an affect table and use it to constrain annotation. Five state-of-the-art multimodal large language models (MLLMs) then analyze both modalities, and their outputs are fused with Reciprocal Rank Fusion (RRF) algorithm to yield robust affects and confidences. We conducted a user study with two experiments to validate usability and assess InfoAffect dataset using the Composite Affect Consistency Index (CACI), achieving an overall score of 0.986, which indicates high accuracy.
