# ComPaSC^3

> Our code is currently being organized and will be subsequently updated and open-sourced for public access.

This repository contains the code for the SIGIR 2025 paper *Social Context-Aware Community-Level Propagation Prediction*.

Authors: Jinfei Gao, Xiao Wang, Tian Gan$^*$, Jianhua Yin, Chuanchen Luo, Liqiang Nie

Organizations: Shandong University, Harbin Institute of Technology Shenzhen

If our code or data helps you in your research, please kindly cite us:

```

```

## Introduction

With the increasing prevalence of online communities, social networks have become pivotal platforms for information propagation. However, this rise is accompanied by issues such as the spread of misinformation and online rumors. Community Level Information Pathway Prediction (CLIPP) is proposed to effectively stop the propagation of harmful information within specific communities. While progress has been made in understanding user-level propagation, there is a significant gap in addressing the CLIPP problem at the community level, particularly with regard to social context interpretation and the cold start problem in niche communities. To bridge this gap, we propose a novel model, named Community-Level Pagation Prediction with LLM enhanced Social Context Interpretation and Community Coldstart ($ComPaSC^3$), which integrates three primary modules. The video enhancement module leverages LLMs to enrich the interpretation of multimedia content by embedding world knowledge. The community portrait building module utilizes LLMs to generate detailed community portraits for community interpretation. To tackle the community cold start problem, the dynamic commLink module links non-popular communities to the popular ones based on their portrait similarity, and dynamically updates their relationship weights. Our experimental results demonstrate that $ComPaSC^3$  significantly improves predictive accuracy in both popular and non-popular scenarios. Particularly in non-popular communities, our approach outperforms existing state-of-the-art methods, achieving improvements of 10.00% - 15.20% in Rec@5 and 7.31% - 12.32% in NDCG@10.

## Dataset

You can obtain the dataset from [here](https://github.com/claws-lab/INPAC) [1].

1. Yiqiao Jin, Yeon-Chang Lee, Kartik Sharma, Meng Ye, Karan Sikka, Ajay Divakaran, and Srijan Kumar. 2023. Predicting Information Pathways Across Online Communities. In Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD '23). Association for Computing Machinery, New York, NY, USA, 1044–1056. https://doi.org/10.1145/3580305.3599470

## Train & test

Our code is currently being organized and will be subsequently updated and open-sourced for public access.

## Contact

If you have any questions, please contact the author Jinfei Gao.

