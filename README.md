# 一个简单Diffusion Model的最小实现
基于OpenAI的[repo](https://github.com/openai/improved-diffusion)剥离出来一个最简单的版本，方便大家学习

暂时只实现了DDPM的采样

暂时只支持单卡跑，一张A100训练64x64大小的CIFAR10，大概6个小时

运行命令：

```shell
python main.py
```

TODO:
1. 实现DDIM的加速采样
2. 单机多卡，多机多卡
3. 条件采样，从类别条件争取扩充到文字引导
