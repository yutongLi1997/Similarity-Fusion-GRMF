# Similarity-Fusion-GRMF
This repository contains the code for the LOD-2022 conference paper: [A Matrix Factorization-based Drug-virus Link Prediction Method for SARS-CoV-2 Drug Prioritization](https://link.springer.com/chapter/10.1007/978-3-031-25599-1_4).


![The pipeline of this project is showed as follows:](https://github.com/yutongLi1997/Similarity-Fusion-GRMF/blob/main/grmf_flowchart.png)
## Absctract

Matrix factorization (MF) has been widely used in drug discovery for link prediction, which aims to reveal new drug-target links by integrating drug-drug and target-target similarity information with a drug-target interaction matrix. The MF method is based on the assumption that similar drugs share similar targets and \textit{vice versa}. However, one major disadvantage is that only one similarity metric is used in MF models, which is not enough to represent the similarity between drugs or targets. In this work, we develop a similarity fusion enhanced MF model to incorporate different types of similarity for novel drug-target link prediction. We apply the proposed model on a drug-virus association dataset for anti-COVID drug prioritization, and compare the performance with other existing MF models developed for COVID. The results show that the similarity fusion method can provide more useful information for drug-drug and virus-virus similarity and hence improve the performance of MF models. The top 10 drugs as prioritized by our model are provided, together with supporting evidence from literature.


## Requirements

The DVA dataset used in this work is available at https://github.com/aanchalMongia/DVA.

The code was tested in Python 3.8.

## Cite us
Li, Yutong, Xiaorui Xu, and Sophia Tsoka. "A Matrix Factorization-Based Drug-Virus Link Prediction Method for SARS-CoV-2 Drug Prioritization." International Conference on Machine Learning, Optimization, and Data Science. Cham: Springer Nature Switzerland, 2022.

```
@inproceedings{li2022matrix,
  title={A Matrix Factorization-Based Drug-Virus Link Prediction Method for SARS-CoV-2 Drug Prioritization},
  author={Li, Yutong and Xu, Xiaorui and Tsoka, Sophia},
  booktitle={International Conference on Machine Learning, Optimization, and Data Science},
  pages={35--47},
  year={2022},
  organization={Springer}
}
```
