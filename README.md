# GSSR

~~Gene Splice Site Recognition by WAM, Bayesian Network and SVM approaches~~

A Computing Data Science Perspective on Gene Splice Site Identification.

## Abstract

As molecular biology and information technology advances, machine learning techniques have a wide range of applications in bioinformatics. In this work, on the problem of gene splicing donor site identification, on both balanced dataset and unbalanced dataset, three models (WAM, BN , SVM) are evaluated comprehensively. A set of comprehensive performance metrics were also introduced in the experiments. And to detect splice signals precisely, a correction has also made to Bayesian network. The result shows that SVM has a good ability on take caring of unbalanced data while WAM and BN do not. Besides, the fitness of metrics is also tested. It shows that auPRC is more sensitive to unbalanced data and so is more applicable in many situations.

随着分子生物学和信息技术的发展，机器学习技术在生物信息学中有着广泛的应用。在本工作中，针对基因拼接供体位点识别问题，在平衡数据集和非平衡数据集上，对三种模型（WAM，BN ，SVM）进行了综合评价。实验中还引入了一套综合性能指标。而为了精确检测拼接信号，还对贝叶斯网络进行了修正。结果表明，SVM对不平衡数据有很好的处理能力，而WAM和BN则没有。此外，还测试了指标的适用性。表明auPRC对不平衡数据比较敏感，所以在很多情况下比较适用。

## Report

[A Computing Data Science Perspective on Gene Splice Site Identification](Report/A Computing Data Science Perspective on Gene Splice Site Identification.pdf)

## Requirements

see [requirements.txt](requirements.txt)

## Reproducibility

The data, code and running process are retained in the report and [Report.ipynb](Source/Report.ipynb)

## Models

Weighted Array Model, Bayesian network, and Support vector machine.

See [Models.ipynb](Source/Models.ipynb) for details in implementation.

## Maintainer

| Name      | Email                                           | Organization                                                 |
| --------- | ----------------------------------------------- | ------------------------------------------------------------ |
| Hui Chong | chonghui@hust.edu.cn<br />huichong.me@gmail.com | Research Assistant, School of Life Science and Technology, Huazhong University of Science & Technology |






