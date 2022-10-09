---
title: "Nepglue"
date: 2022-10-09T12:07:55+05:45
draft: true
---

## Nep-gLUE Benchmark:

In this project we have tried to incorporate different Natural Language Understanding (NLU) tasks in Nepali at one place. This benchmark contains 4 different task: Named Entity Recognition (NER), Part Of Speech Tagging (POS Tagging), Content Classification (CC) and Catagorical Pair Similarity (CPS) as per now. We will continue to expand the number of tasks but it is a work in progress. 
All the scores are calcualted using macro-f1 metric.

|     Model        |   Params  --   |     -- NER  --    |  --    POS  --  |   -- CPS --  |  -- CC -- |    --    Nep-gLUE Score |
|:----------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
|[multilingual BERT](https://huggingface.co/bert-base-multilingual-cased) | 172M  | 85.45 | 94.65 | 93.60 | 91.08| 91.19|
|[XLM-R (base)](https://huggingface.co/xlm-roberta-base) |  270M   | 87.59 |94.88 |93.65 |92.33| 92.11 |
|[NepBERT](https://github.com/pudasainishushant/NepaliLanguageModelPretraining) | 110M | 79.12 |90.63 |91.05 |90.98| 87.94|
|[NepaliBERT](https://huggingface.co/Rajan/NepaliBERT) | 110M | 82.45 |91.67 |89.46| 90.10|88.42 |
|NepBERTa (Ours) | 110M | **91.09**|**95.56** |**94.42**|**93.13**|**93.55**|



To get benchmarking dataset you can visit as follows:

* **POS:** **[Part Of Speech Tagging](https://drive.google.com/file/d/1ZnwSxPaNimEPKC0baN9gvYD3rNz4p56v/view?usp=sharing)**
* **NER:** **[Named Entity Recognition](https://drive.google.com/file/d/1WQ2CtwxIO0wljl9FD9k3T6Zpurdqu8T4/view?usp=sharing)**
* **CPS:** **[Catagorical Pair Similarity](https://drive.google.com/drive/folders/1IDzPBGz1Yj4K1JLyoJQYCYB-27l_TOK9?usp=sharing)**
* **CC:** **[Content Classification](https://drive.google.com/drive/folders/1sVyAY8eD7hi3e9ebae5dz5xItCkVyANP?usp=sharing)**

Note: If you want to contribute to the project with your own dataset or if you get improved results on these tasks, please consider mailing us to our address.