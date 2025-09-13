# Stacking

## 简介

在集成学习中，当训练数据很多时，“学习法”是一种强大的结合策略，即通过另一个学习器来进行结合。Stacking 是学习法的典型代表，把弱学习器称为初级学习器，用于结合的学习器称为次级学习器。

## 原理

Stacking 先从初始训练集训练出初级学习器，即首先训练多个不同的模型，然后再以之前训练的各个模型的输出作为输入来训练一个“组合”模型，以得到一个最终的输出。如果可以选用任意一个结合算法，那么理论上 Stacking 可以表示之前提到的各种 Ensemble 方法。然而，实际中，通常使用单层逻辑回归作为结合模型。


## Lab

- [Stack Iris](11_stacking-Iris.ipynb)
- [Stack Iris](13_stacking-Iris.ipynb)
- [Stack Pipeline](15_stacking-pipeline.ipynb)

