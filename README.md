# Cluster-GAN
基于生成对抗网络多视图异常检测问题复现  
[参考文献] ClusterGAN : Latent Space Clustering in Generative Adversarial Networks (https://arxiv.org/pdf/1809.03627v2.pdf)  

基于生成器G和判别器D的博弈，主要公式为：  
$ \min_{\Theta_G} \max_{\Theta_{D}} \mathop{\mathbf{E}}_{x \sim \mathbb{P}^r_x} q(\mathcal{D}(x)) + \mathop{\mathbf{E}}_{z \sim \mathbb{P}_z} q(1-\mathcal{D}(\mathcal{G}(z))) $
