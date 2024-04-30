# Toy-QVAE
Quantum Variational Regularized Auto-encoder for Drug Molecule Generation (Purely experimental)

Based on [this tutorial](https://keras.io/examples/generative/molecule_generation/) from Keras.io, but replacing classical graph encoding methods with quantum equivariant graph embedding as in [this tutorial](https://pennylane.ai/qml/demos/tutorial_equivariant_graph_embedding/) from PennyLane.ai. Implemented using Keras 2 and TensorFlow, as PennyLane does not yet support Keras 3 for the creation of `KerasLayer`s. Model is trained using the [Lion](https://keras.io/api/optimizers/lion/) optimizer. 

This project is not affiliated with QNetGAN® 
