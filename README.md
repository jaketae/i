# ResMLP

PyTorch implementation of [ResMLP: Feedforward networks for image classification with data-efficient training](https://arxiv.org/abs/2105.03404).

![alt text](https://pic4.zhimg.com/80/v2-1e4448bd4f9fcb91870a9138d227679f_1440w.jpg)

## Quickstart

Clone this repository.

```
git clone https://github.com/jaketae/res-mlp.git
```

Navigate to the cloned directory. You can start using the model via

```python
>>> from res_mlp import ResMLP
>>> model = ResMLP()
```

By default, the model comes with the following parameters:

```python
ResMLP(
    image_size=256,
    patch_size=16,
    in_channels=3,
    num_features=128,
    expansion_factor=2,
    num_layers=6,
    num_classes=10,
)
```

## Resources

-   [Original Paper](https://arxiv.org/abs/2105.03404)
-   [Going deeper with Image Transformers](https://arxiv.org/abs/2103.17239)
-   [Image take from source](https://zhuanlan.zhihu.com/p/371049713)
