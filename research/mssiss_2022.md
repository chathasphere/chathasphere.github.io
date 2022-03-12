---
layout: page
title: Early Detection of Alcoholic Liver Disease in the Optum Claims Dataset with Transformers
---

*Prayag Chatha (1), Jessica Mellinger (2), Jeffrey Regier (1)*

(1) Department of Statistics, University of Michigan; 
(2) Department of Internal Medicine, Michigan Medicine

## Abstract

Alcoholic liver disease (ALD) is a leading cause of liver-related death world- wide. Unfortunately, ALD is often diagnosed too late for effective intervention. The Optum Claims dataset contains billing codes for the employee-sponsored insurance claims of millions of individuals--a vast amount of observational data about a general population, including patients with ALD. As a patient inter- acts with the medical system over time, they generate a detailed sequence of ICD diagnostic codes, lab results, and drug prescriptions in Optum Claims. A transformer is a deep learning architecture that excels at modeling long-range sequential dependencies in sequential data through self-attention. Unlike a recurrent neural network, a transformer admits parallel computation for efficient training. We developed a transformer-based model called “tf-md” that differ- entiates early-stage and late-stage ALD based on Optum Claims data. tf-md achieved a validation AUROC of 0.689, whereas a fully-connected ”bag of words” neural network model had a best AUROC of 0.674. The latter model has access only to the frequency of codes, not their sequence position, suggesting that the ordering of a patient’s insurance claims contains information that helps to detect ALD early.


