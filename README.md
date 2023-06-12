# Monolingual, multilingual and cross-lingual code comment classification

This repository contains the data and source code used in journal paper [*Monolingual, multilingual and cross-lingual code comment classification*](https://doi.org/10.1016/j.engappai.2023.106485).

## Abstract

Code comments are one of the most useful forms of documentation and metadata for understanding software implementation. Previous research on code comment classification has focused only on comments in English, typically extracted from a few programming languages. This paper addresses the problem of code comment classification not only in the monolingual setting, but also in the multilingual and cross-lingual one, in order to examine whether they can outperform the traditional monolingual approach. To tackle this task, we introduce a novel, publicly available code comment dataset, consisting of over 10,000 code comments collected from software projects written in eight programming languages (C, C++, C#, Java, JavaScript/TypeScript, PHP, Python, and SQL). About half of them are written in Serbian while the other half are written in English. This dataset was manually annotated according to a newly proposed taxonomy of code comment categories. We fine-tune and evaluate multiple monolingual and multilingual pre-trained neural language models on the code comment classification task and compare their performances to several baselines. The best results for Serbian comments are obtained using the monolingual neural model BERTić, trained on Serbian and closely related languages. On the other hand, the optimal choice for English is the multilingual neural model multilingual BERT, which successfully extracts useful patterns from data in both languages. Although the cross-lingual setting shows some promise for simple binary classification, it has yet to reach sufficiently high performance levels for practical use. We also analyze model performance across different programming languages.

## Citation 

```bibtex
@article{KOSTIC2023106485,
  title = {Monolingual, multilingual and cross-lingual code comment classification},
  journal = {Engineering Applications of Artificial Intelligence},
  volume = {124},
  pages = {106485},
  year = {2023},
  issn = {0952-1976},
  doi = {https://doi.org/10.1016/j.engappai.2023.106485},
  url = {https://www.sciencedirect.com/science/article/pii/S0952197623006693},
  author = {Marija Kostić and Vuk Batanović and Boško Nikolić},
  keywords = {Code comments, Code comment classification, Pre-trained language models, Transformers, Annotated dataset},
}
```
