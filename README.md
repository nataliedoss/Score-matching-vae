# Score-matching-vae

This is a Tensorflow implementation of the algorithm described in Section 2.1 of [Variational autoencoder via score matching](https://github.com/nataliedoss/Score-matching-vae/blob/master/vae_sm.ipynb).

This algorithm imitates the variational autoencoder of [Kingma and Welling (2013)](https://arxiv.org/abs/1312.6114), but performs variational inference by minimizing the Fisher divergence rather than the KL divergence. It is provided in a Jupyter notebook. 

Also included is a Jupyter notebook, [Variational autoencoder via ratio matching](https://github.com/nataliedoss/Score-matching-vae/blob/master/vae_rm.ipynb), implementing the algorithm described in Section 2.2 of <a href="sm_vi.pdf" download>Nonparametric variational inference via score matching</a>. Again, this algorithm imitates the variational autoencoder, but performs variational inference via ratio matching rather than by minimizing the KL divergence.
