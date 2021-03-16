# Importance weighting paper summaries

By Cyril Ionov

### Rethinking Importance Weighting for Deep Learning under Distribution Shift (2020)
[arxiv:2006.04662](https://arxiv.org/abs/2006.04662)

Official code: https://github.com/TongtongFANG/DIW

**Essence:** The learning task is divided into two stages: weight estimation (WE) and weighted learning (classification) (WC). The key idea is to iteratively train WC and WE on minibatches. For WC we use weighted loss. For WE we invertibly map $(x,y) \mapsto z$ to latent space with reduced dimensions. Then the weights are acquired through kernel mean matching (minimizing maximum mean discrepancy).

**Key words:** distribution shift, important weighting, distribution matching

Weighted classification loss:
![](https://i.imgur.com/VZAULTO.png)


### Importance Weighting and Variational Inference (2018)
[arxiv:1808.09034](https://arxiv.org/abs/1808.09034v3)

**Essence:** the paper gives new perspective on importance weighted variational inference proving its connection with self-normalized importance sampling.

Actually, not relevant for our task.

**Key words:** importance weighting, importance sampling, importance weighted ELBO, elliptical distributions, reparametrization, self-normalized importance sampling, 

IW-ELBO (importance weighted ELBO)
![](https://i.imgur.com/ZzgUNwy.png)

