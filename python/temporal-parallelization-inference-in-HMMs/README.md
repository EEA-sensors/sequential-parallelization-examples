# Experiments for the paper Temporal Parallelization of Inference in Hidden Markov Models [2]

### Author: [Sakira Hassan](https://github.com/sakira/)

These notebooks illustrate the gain in perfomance of using the parallel implementation of HMM forward-backward and Viterbi algorithms on GPU. They can be downloaded to be run locally or on Google Colab:
- Classical HMM: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EEA-sensors/sequential-parallelization-examples/blob/main/python/temporal-parallelization-inference-in-HMMs/phmm_classical.ipynb)
- Potential based HMM: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EEA-sensors/sequential-parallelization-examples/blob/main/python/temporal-parallelization-inference-in-HMMs/phmm_potentials.ipynb)
- Viterbi: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EEA-sensors/sequential-parallelization-examples/blob/main/python/temporal-parallelization-inference-in-HMMs/phmm_viterbi.ipynb)



### Last run with:
- Tensorflow:  
  tensorflow==2.6.0  
  tensorflow_probability==0.14.1
  
- GPU:
  nvcc: NVIDIA (R) Cuda compiler driver
  Built on Mon_Oct_12_20:09:46_PDT_2020
  Cuda compilation tools, release 11.1, V11.1.105
  Build cuda_11.1.TC455_06.29190527_0  


### References
[2] S. S. Hassan, S. Särkkä and Á. F. García-Fernández, "Temporal Parallelization of Inference in Hidden Markov Models," in IEEE Transactions on Signal Processing, vol. 69, pp. 4875-4887, 2021, doi: https://10.1109/TSP.2021.3103338.
