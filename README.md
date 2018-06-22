# Benchmarking Fashion MNIST
Here is a project in which we use different Machine Learning and Deep Learning Algorithms to benchmark [FashionMNIST Dataset](https://github.com/zalandoresearch/fashion-mnist) and compare the results with original [MNIST Dataset](http://yann.lecun.com/exdb/mnist/).

| Classifier | Optimizer | Preprocessing | Fashion test accuracy | MNIST test accuracy | Location |
| --- | --- | --- | --- | --- | --- |
|2 Conv Layers with max pooling + 2 Connected Layer (PyTorch) | SGD + Nesterov | None | 92.69% | 99.34% | CNN-FashionMNIST Model A |
|2 Conv Layers with max pooling + 1 Connected Layer (PyTorch) | SGD + Nesterov | None | 91.21% | 99.23% | CNN-FashionMNIST Model B |
|3 Conv Layers with max pooling + 2 Connected Layer (PyTorch) | SGD + Nesterov | None | 93.18% | 99.37% | CNN-FashionMNIST Model C |

More Algorithms will be added soon.
