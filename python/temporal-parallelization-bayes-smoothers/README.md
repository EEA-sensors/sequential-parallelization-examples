# Examples for the paper Temporal Parallelization of Bayesian Smoothers [1]

### Author: [Adrien Corenflos](https://github.com/AdrienCorenflos/)

These notebooks illustrate the gain in perfomance of using the parallel implementation of Kalman filters and smoothers on GPU. They can be downloaded to be run locally or on Google Colab:
- JAX: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EEA-sensors/sequential-parallelization-examples/blob/main/python/temporal-parallelization-bayes-smoothers/parallel_kalman_jax.ipynb)
- TensorFlow: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EEA-sensors/sequential-parallelization-examples/blob/main/python/temporal-parallelization-bayes-smoothers/parallel_kalman_tf.ipynb)

### Last run with:
- Tensorflow:  
  tensorflow==2.4.0  
  tensorflow_probability==0.11.0  
- JAX:  
  jax==0.1.77   
  jaxlib==0.1.55+cuda101  

### References
[1] Simo Särkkä and Ángel F. García-Fernández (2021). Temporal Parallelization of Bayesian Smoothers. IEEE Transactions on Automatic Control, Volume: 66, Issue: 1, Pages 299-306. arXiv: https://arxiv.org/abs/1905.13002 DOI: https://doi.org/10.1109/TAC.2020.2976316
