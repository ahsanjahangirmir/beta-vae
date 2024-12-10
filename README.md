# beta-vae
Beta Variational Autoencoders for DRL

This repo presents an implementation and evaluation of disentangled representation learning using the β-VAE framework on the dSprites dataset. We systematically vary the β hyperparameter and compare the resulting models against a baseline VAE. We visualize the latent traversals, evaluate metrics such as Mutual Information Gap (MIG), Z-diff, and Modularity, and discuss the implications of increasing β on both disentanglement and reconstruction quality. Finally, we highlight the limitations of β-VAEs in capturing fine-grained details and fully separating certain generative factors.
