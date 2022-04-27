# GAN Disadvantages and Bias

## (Optional Notebook) Score-based Generative Modeling

+ Click [this link](https://colab.research.google.com/github/https-deeplearning-ai/GANs-Public/blob/master/C2W2_(Optional_Notebook)_Score_Based_Generative_Modeling.ipynb) to access the Colab notebook!

This is a hitchhiker's guide to score-based generative models, a family of approaches based on [estimating gradients of the data distribution](https://arxiv.org/abs/1907.05600). They have obtained high-quality samples comparable to GANs (like below, figure from [this paper](https://arxiv.org/abs/2006.09011)) without requiring adversarial training, and are considered by some to be the [new contender to GAN](https://ajolicoeur.wordpress.com/the-new-contender-to-gans-score-matching-with-langevin-sampling/).

## (Optional Notebook) GAN Debiasing

+ [Notebook link](https://colab.research.google.com/github/https-deeplearning-ai/GANs-Public/blob/master/C2W2_GAN_Debiasing_(Optional).ipynb)

[Fair Attribute Classification through Latent Space De-biasing](https://princetonvisualai.github.io/gan-debiasing/). Vikram V. Ramaswamy, Sunnie S. Y. Kim, Olga Russakovsky. CVPR 2021.

Fairness in visual recognition is becoming a prominent and critical topic of discussion as recognition systems are deployed at scale in the real world. Models trained from data in which target labels are correlated with protected attributes (i.e. gender, race) are known to learn and perpetuate those correlations.

In this notebook, you will learn about _Fair Attribute Classification through Latent Space De-biasing_ (Ramaswamy et al. 2020) that introduces a method for training accurate target classifiers while mitigating biases that stem from these correlations. Specifically, this work uses GANs to generate realistic-looking images and perturb these images in the underlying latent space to generate training data that is balanced for each protected attribute. They augment the original dataset with this perturbed generated data, and empirically demonstrate that target classifiers trained on the augmented dataset exhibit a number of both quantitative and qualitative benefits.

## Works Cited

### From the videos

+ [Hyperspherical Variational Auto-Encoders (Davidson, Falorsi, De Cao, Kipf, and Tomczak, 2018)](https://arxiv.org/abs/1804.00891)
+ [Generating Diverse High-Fidelity Images with VQ-VAE-2 (Razavi, van den Oord, and Vinyals, 2019)](https://arxiv.org/abs/1906.00446)
+ [Conditional Image Generation with PixelCNN Decoders (van den Oord et al., 2016)](https://arxiv.org/abs/1606.05328)
+ [Glow: Better Reversible Generative Models (Dhariwal and Kingma, 2018)](https://openai.com/blog/glow/)
+ [Machine Bias (Angwin, Larson, Mattu, and Kirchner, 2016)](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing)
+ [Fairness Definitions Explained (Verma and Rubin, 2018)](https://fairware.cs.umass.edu/papers/Verma.pdf)
+ [Does Object Recognition Work for Everyone? (DeVries, Misra, Wang, and van der Maaten, 2019)](https://arxiv.org/abs/1906.02659)
+ [PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models (Menon, Damian, Hu, Ravi, and Rudin, 2020)](https://arxiv.org/abs/2003.03808)
+ [What a machine learning tool that turns Obama white can (and can't) tell us about AI bias (Vincent, 2020)](https://www.theverge.com/21298762/face-depixelizer-ai-machine-learning-tool-pulse-stylegan-obama-bias)

### From the notebook

+ [Mitigating Unwanted Biases with Adversarial Learning (Zhang, Lemoine, and Mitchell, 2018)](https://m-mitchell.com/papers/Adversarial_Bias_Mitigation.pdf)
+ [Tutorial on Fairness Accountability Transparency and Ethics in Computer Vision at CVPR 2020 (Gebru and Denton, 2020)](https://sites.google.com/view/fatecv-tutorial/schedule?authuser=0)
+ [Machine Learning Glossary: Fairness (2020)](https://developers.google.com/machine-learning/glossary/fairness)
+ [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
