## Comparison of Performance and Best Practices of Data Imputation Techniques

### Abstract 📑

GAN training can be tricky and very sensitive. It is still an active research domain to achieve a stable and consistent training method for GANs. This work mainly focuses on DC-GANs and the best practices that can be followed for stable GAN training. The manuscript dives into the hyperparameters and architectural choices to optimize the min-max game for stable nash equilibrium. Common pitfalls and challenges in training are discussed, and possible solutions to overcome the same. A comprehensive guide to stable and consistent GAN training is the main focus of this work. We also explore the controllability of the generator's output by achieving disentanglement in DC-GANs. Finally, compare various architectures and designs of DC-GANs to arrive at a recommendable design choice for a stable GAN training.

### Results

A sample generation of cats when trained with a set of CAT faces ONLY
<div align='center'>
<img src = 'results/cats/vanilla_generated_plot_e830.png'
     width="500" 
     height="500">
</div>


A sample generation of cats when trained with a set of CAT (set of 5000) and WILD ANIMAL (set of 5000) faces
<div align='center'>
<img src = 'results/cats+wild/vanilla_generated_plot_e2570.png'
     width="500" 
     height="500">
</div>
