# [Wasserstein Adversarial Transformer for Cloud Workload Prediction](https://ojs.aaai.org/index.php/AAAI/article/view/21509)
*Shivani Arbat , Vinod K. Jayakumar, Jaewoo Lee, Wei Wang, In Kee Kim*

---
Predictive VM (Virtual Machine) auto-scaling is a promising technique to optimize cloud applications' operating costs and performance. 
Understanding the job arrival rate is crucial for accurately predicting future changes in cloud workloads and proactively provisioning and de-provisioning VMs for hosting the applications. 
However, developing a model that accurately predicts cloud workload changes is extremely challenging due to the dynamic nature of cloud workloads.
Long-Short-Term-Memory (LSTM) models have been developed for cloud workload prediction. 
Unfortunately, the state-of-the-art LSTM model leverages recurrences to predict, which naturally adds complexity and increases the inference overhead as input sequences grow longer. 
To develop a cloud workload prediction model with high accuracy and low inference overhead, 
this work presents a novel time-series forecasting model called WGAN-gp Transformer, inspired by the Transformer network and improved Wasserstein-GANs. The proposed method adopts a Transformer network as a *generator* and a multi-layer perceptron as a *critic*. The extensive evaluations with real-world workload traces show WGAN-gp Transformer achieves 5 times faster inference time with up to 5.1% higher prediction accuracy against the state-of-the-art.
We also apply WGAN-gp Transformer to auto-scaling mechanisms on Google cloud platforms, and the WGAN-gp Transformer-based auto-scaling mechanism outperforms the LSTM-based mechanism by significantly reducing VM over-provisioning and under-provisioning rates.

---
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Official Implementation of our [WGAN-gp Transformer paper](https://ojs.aaai.org/index.php/AAAI/article/view/21509) for both training and evaluation. This paper is accepted in IAAI'22 to be presented at AAAI-22. WGAN-gp Transformer introduces a novel approach for effectively predicting job arrival rates in dynamic cloud workloads.
