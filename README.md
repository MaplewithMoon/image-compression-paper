# image-compression-paper

本项目旨在收录和建立一个deep image compression领域的paper list（画饼），目前收录了部分早期的deep image compression方面的工作，作为入门级别的论文导读。
根据使用网络结构的不同，将早期deep image compression方向的工作分为3部分，即基于RNN的方法、基于CNN的方法和基于GAN的方法。在此基础上，将目前主流的，即基于超先验模型（hyper prior model）和上下文模型(context model)（本质上也是CNN based methods）的相关基础论文单列为一类，值得精读。此外，也会逐步在others类别中，收录一些关于deep image compression方向的思考与探索性工作，以及一些炼丹向的实用tricks或验证实验方向的工作。

由于RNN、CNN、GNN based methods存在比较明显的时间梯度，建议阅读顺序为survey——RNN——CNN——GAN。值得注意的是，虽然网络结构不同，但这些方法大体上都遵循着“变换——量化——熵编码”这一基本思路，如果阅读过程中有所迷失，建议对照这一思路加以分析阅读。

Survey:

RNN based compression methods:

[Variable Rate Image Compression with Recurrent Neural Networks  2016](https://arxiv.org/abs/1511.06085)

[Full Resolution Image Compression with RecurrentNeural Networks   2016](https://www.ijraset.com/fileserve.php?FID=9723)

[Improved Lossy Image Compression with Priming and Spatially Adaptive Bit Rates for Recurrent Networks   2017](https://openaccess.thecvf.com/content_cvpr_2018/papers/Johnston_Improved_Lossy_Image_CVPR_2018_paper.pdf)

CNN based compression methods:

[Lossy Image Compression with Compressive Autoencoders 2017](https://arxiv.org/pdf/1703.00395.pdf)

[Learning Convolutional Networks for Content-weighted Image Compression 2017](https://arxiv.org/pdf/1904.00664.pdf)

[Deep Image Compression via End-to-End Learning 2018](https://arxiv.org/pdf/1806.01496.pdf)


GAN based:

[Real-Time Adaptive Image Compression 2017](https://arxiv.org/pdf/1705.05823.pdf)

[Generative Adversarial Networks for Extreme Learned Image Compression 2018](https://arxiv.org/pdf/1804.02958.pdf)

[Extreme Image Coding via Multiscale Autoencoders Generative Adversarial Optimization 2019](https://arxiv.org/pdf/1904.03851v2.pdf)

Hyper Prior:

[Density Modeling of Images using a Generalized Normalization Transformation 2016](https://arxiv.org/pdf/1511.06281.pdf)

[End-to-end optimized image compression 2017](https://arxiv.org/pdf/1611.01704.pdf)

[Variational image compression with a scale hyperprior 2018](http://export.arxiv.org/pdf/1802.01436)

[Joint Autoregressive and Hierarchical Priors for Learned Image Compression 2018](https://arxiv.org/pdf/1809.02736.pdf)



Other stuffs:

[Efficient Nonlinear Transforms for Lossy Image Compression 2018](https://arxiv.org/pdf/1802.00847.pdf)

[The perception- distortion tradeoff 2018](https://arxiv.org/pdf/1711.06077.pdf)

