---
author: Kurt Choi
title:  "Training a Digit Classifier"
date:   2020-12-28 19:24:00 -0500
tags: [deeplearning, pytorch, fastai]
categories: [coding]
math: false
mermaid: false
---
Today, I'm going through Chapter 4 of a Deep Learning book[^1] by Jeremy Howard and Sylvain Gugger. The ultimate goal today will be **creating a model that can classify *handwritten digits*, from scratch**.

 &nbsp;

----

&nbsp;

## Creating a model that can distinguish two different digits; 3 and 7

*Trying to solve an easier version of a problem* is often a great way to start out - in the Fast.AI lesson, it has been suggested to try to create a model that can distinguish between only two digits, namely 3 and 7.

Fast.AI's dataset library provides many different datasets - one of them is the **MNIST dataset** which contains many images of *handwritten digits*. Fast.AI also provides a simpler version of the MNIST dataset, namely `MNIST_SAMPLE`, which only contains handwritten digits of 3s and 7s.

```python
data_path = untar_data(URLs.MNIST_SAMPLE)
```



&nbsp;

##### References

[^1]: Deep Learning for Coders with fastai & PyTorch by Jeremy Howard and Sylvain Gugger

