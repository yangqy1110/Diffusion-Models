# Diffusion-Models
扩散模型原理和pytorch代码实现初学资料汇总
有侵权的资料联系我删除哈，如果能帮得上忙的话荣幸之至，一个Star是对我的最大支持，感谢！

### 1.扩散模型和分数匹配模型的资源和论文的汇总

https://github.com/heejkoo/Awesome-Diffusion-Models 是一个github网站

### 2. 三篇经典论文

- [《Deep Unsupervised Learning using Nonequilibrium Thermodynamics》](https://proceedings.mlr.press/v37/sohl-dickstein15.html) 2015年 扩散模型起源

- [《Denoising Diffusion Probabilistic Models》](http://arxiv.org/abs/2006.11239) 2020年 扩散模型兴起
  - https://github.com/lucidrains/denoising-diffusion-pytorch 对应pytorch实现

- [《Improved Denoising Diffusion Probabilistic Models》](https://proceedings.mlr.press/v139/nichol21a.html) 2021年 第二篇论文的改进
   - https://github.com/openai/improved-diffusion 对应pytorch实现

### 3.看过的扩散模型博客

- [The recent rise of diffusion-based models](https://maciejdomagala.github.io/generative_models/2022/06/06/The-recent-rise-of-diffusion-based-models.html)
  - 可以了解到扩散模型近年比较经典的应用
- [Introduction to Diffusion Models for Machine Learning](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/)
  - 从中可以了解到一个实现扩散模型的库denoising_diffusion_pytorch，博客中有使用案例
- [What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
  - 也是扩散模型的一个理论介绍博客，推导挺详细的
- [Diffusion Models as a kind of VAE](https://angusturner.github.io/generative_models/2021/06/29/diffusion-probabilistic-models-I.html)
  - 探究了VAE和扩散模型的联系
- [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion)
  - 扩散模型理论和代码实现，**代码我进行理解加了注释与理论对应，方便大家理解**
- [An introduction to Diffusion Probabilistic Models](https://ayandas.me/blog-tut/2021/12/04/diffusion-prob-models.html) 
  - 也是一个介绍性博客，公式也很工整

### 4. 看过的一个B站视频

- [54、Diffusion Model扩散模型理论与完整PyTorch代码详细解读](https://www.bilibili.com/video/BV1b541197HX?spm_id_from=333.337.search-card.all.click&vd_source=76d3e05c80d0417f315b79db5b98b2cf)
  - 我是看过其他资料后才看的这个视频，所以一遍都能全看懂，不知道初看怎么样

  **代码我也进行理解加了注释与理论对应，方便大家理解**

### 5.未看过的扩散模型博客

- https://jmtomczak.github.io/blog/10/10_ddgms_lvm_p2.html 扩散模型理论和代码实现
- [Generative Modeling by Estimating Gradients of the Data Distribution](https://yang-song.net/blog/2021/score/)

### 其他相关资料

- [机器学习-白板推导系列(十二)-变分推断（Variational Inference）](https://www.bilibili.com/video/BV1DW41167vr?spm_id_from=333.999.0.0&vd_source=76d3e05c80d0417f315b79db5b98b2cf) 知道Lvlb等概念是什么(B站视频)
- [【学习笔记】生成模型——变分自编码器](http://www.gwylab.com/note-vae.html) 理解VAE(博客)
- [【机器学习】白板推导系列(三十二) ～ 变分自编码器(VAE)](https://www.bilibili.com/video/BV15E411w7Pz?spm_id_from=333.999.0.0&vd_source=76d3e05c80d0417f315b79db5b98b2cf) 理解VAE(B站视频)
- https://github.com/labmlai/annotated_deep_learning_paper_implementations 有很多深度学习算法的实现
- [The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) transformer的pytorch实现的一个解释博客
- [positional_encoding的一个实现案例](https://github.com/jalammar/jalammar.github.io/blob/master/notebookes/transformer/transformer_positional_encoding_graph.ipynb ) github代码
- [强烈推荐！台大李宏毅自注意力机制和Transformer详解！](https://www.bilibili.com/video/BV1v3411r78R?spm_id_from=333.337.search-card.all.click&vd_source=76d3e05c80d0417f315b79db5b98b2cf) B站视频
- [《Attention Is All You Need》](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) transformer和注意力机制原论文
- [Transformer论文逐段精读【论文精读】](https://www.bilibili.com/video/BV1pu411o7BE?spm_id_from=333.999.0.0&vd_source=76d3e05c80d0417f315b79db5b98b2cf)
- [64 注意力机制【动手学深度学习v2】](https://www.bilibili.com/video/BV1264y1i7R1?spm_id_from=333.337.search-card.all.click&vd_source=76d3e05c80d0417f315b79db5b98b2cf)  **我根据官方资料整理了jupyter代码实现文件，可从头到尾直接运行**
- [Reparameterization Trick](https://lilianweng.github.io/posts/2018-08-12-vae/#reparameterization-trick) 白板推导变分推断后两节也有提到
- [isotropic Gaussian distribution](https://math.stackexchange.com/questions/1991961/gaussian-distribution-is-isotropic)
- [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/)



