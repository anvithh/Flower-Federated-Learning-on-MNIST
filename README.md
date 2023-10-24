# Flower-Federated-Learning-on-MNIST

This repository demonstrates Federated Learning using the Flower framework with the MNIST dataset.

Server: The server coordinates the training process by aggregating model updates from clients and broadcasting global model updates.

Clients: There are two clients involved in the Federated Learning process. These clients train local models on their non-IID subsets of the MNIST dataset.

Dataset: The dataset used for this implementation is MNIST, a dataset of hand-written digits. Non-IID data distribution implies that the clients have different subsets of the data, ensuring a more realistic and challenging Federated Learning scenario.
