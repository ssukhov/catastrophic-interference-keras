# catastrophic-interference-keras
Accompanying code for the paper "Prevention of catastrophic interference and imposing active forgetting with generative methods". The link to the paper will be provided upon publishing.
The list of files:
* Joint training and Few-Shot Self-Reminder: **JointTraining_MNIST-2b.ipynb**
* Consecutive training using Elastic Weight Consolidation method: **MNIST_EWC.ipynb**
* Avoiding catastrophic interference with activation maximization: **Dreams_MNIST_plain.ipynb**
* Avoiding catastrophic interference with generative process based on Langevin dynamics around several saved training samples: **Restricted_Langevin_MNIST-3.ipynb**
* Selective erazing memory in feedforward classifier using Few-shot Self-Reminder (FSR) method and Langevin dynamics FSR method: **Erase memory-plain.ipynb**
* Selective erazing memory in conditional variational autoencoder: **Erase memory_cvae.ipynb**
* Selective erazing memory in conditional variational autoencoder which classifier produces sparse activity at its output (instead of one-hot activity): **Erase memory_cvae_sparse.ipynb**
* Embedding false memory into feedforward classifier using Few-shot Self-Reminder (FSR) method and Langevin dynamics FSR method: **False memory-plain.ipynb**
* Embedding false memory into conditional variational autoencoder: **False memory_cvae.ipynb**
