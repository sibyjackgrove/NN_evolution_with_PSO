# NN_evolution_with_PSO
Demonstrating how the optimal architecture for a FFNN to predict earthquake magnitude can found using PSO algorithm.
Uses earthquake data from: https://www.kaggle.com/usgs/earthquake-database/data

# Implemented using three classes:
1) NN_model(): Abstracts a Feed forward NN model.
2) PSO_NN_Particle(): Abstracts PSO particle.
3) PSO_NN_Swarm(): Abstracts the PSO swarm.

# Implementation details:
1) NN built using Keras with TensorFLow backend.
2) tf.data API used for feeding data into keras model.
