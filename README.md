# Leveraging Transfer Learning and Legal Named Entity Masking for Classification of Rhetorical Roles in Indian Legal Judgments 
Research work to create an efficient, transparent framework for Indian legal judgment documents classification to counter challenges with document sorting, information retrieval, by the combination of pre-trained models fine-tuned for the Indian Legal domain, by applying Named Entity masking for legal entities, and explainability techniques. 
Published in **2025 5th International Conference on Pervasive Computing and Social Networking (ICPCSN)** - https://ieeexplore.ieee.org/document/11035781

## Abstract
The lengthy and complex nature of Indian legal documents, such as judgment texts, makes manual information retrieval challenging, time-consuming and prone to errors. Legal document classification is an important task in the Indian Judicial system, where huge volumes of data are generated on a daily basis. There is a need for automating the classification of different sections within these judgments, in order to extract important legal insights and improve legal analysis. This research aims to address this by identifying the rhetorical roles of sentences in legal texts such as facts, arguments, precedents, and issues- by exploring a transfer learning-based approach on labelled Indian legal decision texts. A pre-trained language model fine-tuned for the Indian legal domain is used in combination with legal named masking for legal entities, to improve the model’s classification performance and generalization. The study also addresses the challenges related to the unstructured nature of the legal documents and class imbalance, where some labels/sections are cited more often than others. An F1-score of 72.54 is achieved through hyperparameter tuning with Optuna, using multiple features and TF-IDF based representations in combination with the pre-trained InLegalBERT model. Additionally, explainable AI techniques are employed to provide transparency and trust in the predictions of the model, making the decision-making process clearer for legal professionals and improving the model’s applicability in the real-world scenarios.

## Keywords
Indian Legal Classification, Rhetorical Roles, Named Entity Recognition, Transformers, Explainable AI, Natural Language Processing

## Corpus
Available - https://huggingface.co/opennyaiorg/InRhetoricalRoles
Research Article - Corpus for Automatic Structuring of Legal Documents https://aclanthology.org/2022.lrec-1.470/

## Authors
- Anirud Ramani **Contact**- **anirud25@gmail.com**
- Dr. Manju Venugopalan
Dept of CSE, Amrita School of Computing, Amrita Vishwa Vidyapeetham, Bengaluru, India

## Proposed Framework
<img width="1055" height="447" alt="image" src="https://github.com/user-attachments/assets/47bbcca6-f088-40a3-ac31-cec50bf6d6fd" />
Fig. Proposed Framework for Rhetorical Role Classification

## Project Structure
Legal-Named-Entity-Masking-for-Classification-of-Rhetorical-Roles-in-Indian-Legal-Judgments/
│
├── notebooks/
│   ├── RR_LegalClassification.ipynb   # Full pipeline: preprocessing → models → explainability → LLMs
│   └── LegalClassifcation_ExtraModels.ipynb       # Additional classification experiments
│
├── README.md

## Citation
If you use this code or build upon this work, please cite our paper:
[A. Ramani and M. Venugopalan, "Leveraging Transfer Learning and Legal Named Entity Masking for Classification of Rhetorical Roles in Indian Legal Judgments," 2025 5th International Conference on Pervasive Computing and Social Networking (ICPCSN), Salem, India, 2025, pp. 1193-1200, doi: 10.1109/ICPCSN65854.2025.11035781.]



