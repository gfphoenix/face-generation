# face-generation

GAN是一个很有意思的话题，如果你有兴趣，这里还有几篇综述性的文章你可以阅读，看看能否借鉴到你的模型中：
1. [NIPS 2016 Tutorial: Generative Adversarial Networks GAN](https://arxiv.org/abs/1701.00160)模型的发明者Ian Goodfellow自己写的一篇很详细的Tutorial
2. [Generative Adversarial Networks](https://github.com/tensorflow/magenta/blob/master/magenta/reviews/GAN.md)： 对GAN的简单总结以及相关项目

这个项目的主要目的是介绍GAN模型，因此只有一个epoch，生成的面部图像能到这个水平已经很不错了，你可以尝试增加epoch的数量，图像质量会有比较大的改善。如果想实现更好的效果， 可以尝试这篇文章里作者总结的一些经验，[这篇文章](https://github.com/soumith/ganhacks)的作者也是DCGAN原论文的作者之一，在训练GAN模型上有丰富的经验。
