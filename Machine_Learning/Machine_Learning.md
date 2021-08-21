# Machine Learning

## 一、Glossary

* Regression: The function outputs a scalar.

* Classification: Given options(classes), the function outputs the correct one.

* Structured Learning: create something with structure ( image, document ).

* Model: Objective function.

* feature: Known data.

* weight: Variables that are multiplied by known data.

* bias: Corrected deviation.

* Loss: A function of parameters.
  $$
  L=\frac{1}{N}\sum_n e_n
  $$

* Label: Correct value.

* MAE: Means absolute error.
  $$
  e=|y-\hat y|.
  $$

* MSE: Means square error.
  $$
  e=(y-\hat y)^2
  $$

* e: The difference between the true value and the predicted value.

* η: Learning rate.

* hyperparameters: Variable value set by yourself.

* global minima: Smallest L.

* Local minima: Minimum L.

* Linear models: A simple model.

* Model Bias: 由 model 造成的误差。

* sigmoid: s 型的 function 。

* gradient: Loss 对 θ 的微分所构成的向量。

* batch: 将全部的 data 进行分组，每一个分组就是 batch ，用于更新 Θ 。

* epoch: 表示使用所有的 batch 更新了数据。

* update: 表示使用一个batch 更新了数据。

* ReLU: 钩子型的曲线。

* Neuron: 一个 sigmoid 或 ReLU 。

* Neural Network: 由多个 Neuron 组成的网络。

* hidden layer: 一组 Neuron 。

* Deep: 由多个 hidden layer组成的网络。

* Deep Learning: Deep 所采用的整套技术。

* Overfitting: 在训练 data 上表现较好，在 预测 data 上表现较差的情况。

## 二、概述

### 1. Training

1. function with unknown;
2. define loss from training data;
3. optimization.

### 2. 