# Addressing Key Challenges of Adversarial Attacks and Defenses in the Tabular Domain: A Methodological Framework for Coherence and Consistency

[![Published at Elsevier 2025](https://img.shields.io/badge/Published-Elsevier%202025-blue.svg)](link_to_paper)
[![arXiv](https://img.shields.io/badge/arXiv:2412.07326-b31b1b.svg)](
https://doi.org/10.48550/arXiv.2412.07326)


## Abstract

Machine learning models trained on tabular data are vulnerable to adversarial attacks, even in realistic scenarios where attackers have access only to the model's outputs. Researchers evaluate such attacks by considering metrics like success rate, perturbation magnitude, and query count. However, unlike other data domains, the tabular domain contains complex interdependencies among features, presenting a unique aspect that should be evaluated: the need for the attack to generate coherent samples and ensure feature consistency for indistinguishability.

Currently, there is no established methodology for evaluating adversarial samples based on these criteria.

In this paper, we address this gap by proposing new evaluation criteria tailored for tabular attacks' quality;
we defined anomaly-based framework to assess the distinguishability of adversarial samples and utilize the SHAP explainability technique to identify inconsistencies in the model’s decision-making process caused by adversarial samples.
These criteria could form the basis for potential detection methods and be integrated into established evaluation metrics for assessing attack's quality Additionally, we introduce a novel technique for perturbing dependent features while maintaining coherence and feature consistency within the sample.

We compare different attacks' strategies, examining black-box query-based attacks and transferability-based gradient attacks across four target models. Our experiments, conducted on benchmark tabular datasets, reveal significant differences between the examined attacks' strategies in terms of the attacker's risk and effort and the attacks' quality. 

The findings provide valuable insights on the strengths, limitations, and trade-offs of various adversarial attacks in the tabular domain, laying a foundation for future research on attacks and defense development.

# Overview
![screenshot](paper_overview.png)

# Contents
1. Processed datasets
    * Hate
    * ICU
2. Models
    * Gradient Boosting
    * Light Gradient Boost
    * Xgboost
    * Random Forest
3. Edditable-Features file for each dataset
4. Adversarial Attacks for tabular models
    * boundary attack
    * HopSkipJump attack
    * iterative transferable attack

#Pythom Packages Requirments
The Xgboost models required pip install ...
The ...

## Citation

```bibtex
@article{itzhakev2024addressing,
  title={Addressing Key Challenges of Adversarial Attacks and Defenses in the Tabular Domain: A Methodological Framework for Coherence and Consistency},
  author={Itzhakev, Yael and Giloni, Amit and Elovici, Yuval and Shabtai, Asaf},
  journal={arXiv preprint arXiv:2412.07326},
  year={2024}
}
```
