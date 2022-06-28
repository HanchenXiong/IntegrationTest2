# HanchenXiong/IntegrationTest2 

[![Boltzbit Project](https://img.shields.io/badge/Boltzbit-Project-blueviolet?style=for-the-badge)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2)

[![Data Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/data?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Dataset)
[![Training Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/train?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Training)
[![Serving Status](http://demo.platform.boltzbit.com/github-service/api/v1/cubes/status/serving?repositoryOwnerPlusName=HanchenXiong/IntegrationTest2&token=PUBLIC)](https://demo.platform.boltzbit.com/demo-user/HanchenXiong/IntegrationTest2?tab=Deployment)


# Requirements
In all examples, we used:
- `pytorch 1.7.0`
- `numpy 1.17.2`
- `matplotlib 3.1.1`
- `scikit-learn 0.21.3`
- `pytorch-model-summary 0.1.1`
- `jupyter 1.0.0`


# Examples
All examples of implemented deep generative models are provided as jupyter notebooks. They can be find in the following folders:
1. `arms`: an example of an autoregressive model with a causal convolutiona layer in 1D.
2. `flows`: an example of a flow-based model, namely, RealNVP with coupling layers and permutation layers, and IDFs (Integer Discrete Flows).
3. `vaes`: an example of a Variational Auto-Encoder using fully-connected layers and a standard Gaussian prior, and another example of various priors for VAEs, and a third example on a hierarchical VAE.
4. `ddgms`: an example of a Diffusion-based Deep Generative Model using the a Gaussian forward diffusion with a fixed variace and a reverse diffusion parameterized by MLPs.
5. `hybrid_modeling`: an example of a hybrid model using fully-connected layers and IDFs.
6. `ebms`: an example of an energy-based model parameterized by an MLP.
7. `gans`: an example of a GAN parameterized by MLPs.
8. `neural_compression`: an example of applying deep generative modeling to image neural compression.


# Citation
If you use this code in any way, please refer to it by citing my book <a href="https://link.springer.com/book/10.1007/978-3-030-93158-2">"Deep Generative Modeling"</a>:
- APA style:
```
Tomczak, J. M. (2022). Deep Generative Modeling. Springer Nature
```
- Bibtex:
```
@book{tomczak2022deep,
  title={Deep Generative Modeling},
  author={Tomczak, Jakub M},
  publisher={Springer Nature},
  year={2022}
}
```
