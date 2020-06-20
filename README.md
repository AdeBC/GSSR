# 真核基因剪接位点预测

Still working in progress!

## Abstract

- 真核基因剪接位点预测的WAM模型编程实现；
- 利用贝叶斯网络方法预测真核基因剪接位点；
- 利用支行向量机方法预测真核基因剪接位点。

## Introduction

## Materials and Methods

### Data

Data are provided by teacher.

### Preprocessing

I used python language to preprocess the data. The pseudo code for the conversion from the initial sequence to the input feature vector acceptable to the model is as follows.

```python
    positive samples <- empty set
    netative samples <- empty set
    for each sequence in sequences data:
        for each coordination in sequence:
            if coordination is an end of an exon:
                positive samples <- positive samples + coordination
            else:
                negative samples <- negative samples + coordination
    save positive samples and negative samples
```

### Models

### Evaluation

## Result and discussion












