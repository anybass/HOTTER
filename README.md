# 🔥 HOTTER 🔥

Welcome to the code base for the paper "HOTTER: Hierarchical Optimal Topic Transport with Explanatory Context Representations" published in the ["Findings of EMNLP 2021"](https://aclanthology.org/2021.findings-emnlp.418/).

💥 HOTTER is a document meta-distance, combining an LDA topic model with contextual word embeddings from BERT.

💥 HOTTER is an extension of HOTT by Yurochkin et al. ([code](https://github.com/IBM/HOTT), [publication](http://papers.neurips.cc/paper/8438-hierarchical-optimal-transport-for-document-representation.pdf)). We use their code for the underlying distance computation.

## Quick Start Guide

This code works on Linux distributions or on Google Colab. Simply download the code to one destination and run the Jupyter Notebook *HOTTER.ipynb* which shall guide you through the process.

**Hint:** Depending on the dataset and BERT model you want to use, you need to make sure to meet the respective requirements regarding the device memory.
 
## Prerequisites
The code is written in the Jupyter Notebook in Python (3.8.5) and was tested on a Ubuntu system with the following pip requirements:
- tensorflow==2.4.0
- numpy==1.19.2
- POT==0.7.0
- farm==0.7.1
- scipy==1.5.2
- lda==2.0.0
- nltk==3.5
- sentence_splitter==1.4
- six==1.15.0
- torch==1.7.1
- scikit_learn==0.24.2
- tensorflow_hub==0.12.0

## Feedback and Contact
If you have any questions, please contact me: sabine DOT wehnert AT gei DOT de.

💥 Please cite using the following BibTeX entry (instead of Google Scholar):

```@inproceedings{wehnert-etal-2021-hotter-hierarchical,
    title = "{HOTTER}: {H}ierarchical Optimal Topic Transport with Explanatory Context Representations",
    author = {Wehnert, Sabine  and
      Scheel, Christian  and
      Szak{\'a}cs-Behling, Simona  and
      Niel{\"a}nder, Maret  and
      Mielke, Patrick  and
      De Luca, Ernesto William},
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2021",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.findings-emnlp.418",
    pages = "4856--4866",
    
}```

