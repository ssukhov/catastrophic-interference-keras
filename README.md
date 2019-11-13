# Prevention of catastrophic interference and imposing active forgetting with generative methods

Accompanying code for the paper *"Prevention of catastrophic interference and imposing active forgetting with generative methods"*. The experiments are performed on MNIST and Fashion-MNIST datasets. The link to the paper will be provided upon publishing.

## Implementation

File Name | Description 
----------|------------
JointTraining_(f)MNIST-2b.ipynb | Joint training and Few-Shot Self-Reminder 
Catastrophic_interference.ipynb | Illustration of Catastrophic Interference during consequtive training
Training on clusters.ipynb | Clustering of training data and using clusters' centers as self-reminders during consequtive learning
(f)MNIST_EWC.ipynb | Consecutive training using Elastic Weight Consolidation method 
Dreams_(f)MNIST_plain.ipynb | Avoiding catastrophic interference with activation maximization 
(f)MNIST_Langevin-PC.ipynb | Consequtive training with samples generated by Langevin dynamics 
Restricted_Langevin_(f)MNIST-3.ipynb | Avoiding catastrophic interference with generative process based on Brownian walk around several saved training samples 
Clusters_Langevin.ipynb | Avoiding catastrophic interference with generative process based on Brownian walk around the centers of clusters 
Consequtive learning_cvae_v2.2.ipynb | Using Conditional Variational Autoencoder to fight catastrophic interference
Erase memory-plain.ipynb | Selective erazing memory in feedforward classifier using Few-shot Self-Reminder (FSR) method and Langevin dynamics FSR method 
Erase memory_cvae.ipynb | Selective erazing memory in conditional variational autoencoder 
Erase memory_cvae_sparse.ipynb | Selective erazing memory in conditional variational autoencoder which classifier produces sparse activity at its output (instead of one-hot activity) 
False memory-plain.ipynb | Embedding false memory into feedforward classifier using Few-shot Self-Reminder (FSR) method and Langevin dynamics FSR method 
False memory_cvae.ipynb | Embedding false memory into conditional variational autoencoder 

## Tips

Note that generation of 'dreams' in Dreams_(f)MNIST_plain.ipynb file is very slow process. Be prepared.