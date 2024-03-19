# cicada-Algorithm-for-machine-learning
Cicada algorithm is an algorithm for artificial intelligence and machine learning that increases the accuracy. This is its first version and soon its algorithms will be published with 100 percent accuracy. Currently, this algorithm is being tested in Delta DS laboratories. It is for improvement

This algorithm is registered under the name of Delta DS company
1402/12/27

Introduction
Many datasets in various machine learning (ML) applications have structural relationships between their entities, which can be represented as graphs. Such application includes social and communication networks analysis, traffic prediction, and fraud detection. Graph representation Learning aims to build and train models for graph datasets to be used for a variety of ML tasks.

This example demonstrate a simple implementation of a Graph Neural Network (GNN) model. The model is used for a node prediction task on the Cora dataset to predict the subject of a paper given its words and citations network.

Note that, we implement a Graph Convolution Layer from scratch to provide better understanding of how they work. However, there is a number of specialized TensorFlow-based libraries that provide rich GNN APIs, such as Spectral, StellarGraph, and GraphNets.

What is a backpropagation algorithm in a neural network?
Artificial neural networks (ANNs) and deep neural networks use backpropagation as a learning algorithm to compute a gradient descent, which is an optimization algorithm that guides the user to the maximum or minimum of a function.

In a machine learning context, the gradient descent helps the system minimize the gap between desired outputs and achieved system outputs. The algorithm tunes the system by adjusting the weight values for various inputs to narrow the difference between outputs. This is also known as the error between the two.

More specifically, a gradient descent algorithm uses a gradual process to provide information on how a network's parameters need to be adjusted to reduce the disparity between the desired and achieved outputs. An evaluation metric called a cost function guides this process. The cost function is a mathematical function that measures this error. The algorithm's goal is to determine how the parameters must be adjusted to reduce the cost function and improve overall accuracy.

A graph neural network (GNN) belongs to a class of artificial neural networks for processing data that can be represented as graphs.[1][2]
{\displaystyle (3)} Global pooling (or readout) layer. Colors indicate features.
In the more general subject of "geometric deep learning", certain existing neural network architectures can be interpreted as GNNs operating on suitably defined graphs.[6] A convolutional neural network layer, in the context of computer vision, can be seen as a GNN applied to graphs whose nodes are pixels and only adjacent pixels are connected by edges in the graph. A transformer layer, in natural language processing, can be seen as a GNN applied to complete graphs whose nodes are words or tokens in a passage of natural language text.

The key design element of GNNs is the use of pairwise message passing, such that graph nodes iteratively update their representations by exchanging information with their neighbors. Since their inception, several different GNN architectures have been proposed,[2][3][7][8][9] which implement different flavors of message passing,[6] started by recursive[2] or convolutional constructive[3] approaches. As of 2022, whether it is possible to define GNN architectures "going beyond" message passing, or if every GNN can be built on message passing over suitably defined graphs, is an open research question.[10]

Relevant application domains for GNNs include Natural Language Processing,[11] social networks,[12] citation networks,[13] molecular biology,[14] chemistry,[15][16] physics[17] and NP-hard combinatorial optimization problems.[18]

Several open source libraries implementing graph neural networks are available, such as PyTorch Geometric[19] (PyTorch), TensorFlow GNN[20] (TensorFlow), jraph[21] (Google JAX), and GraphNeuralNetworks.jl[22]/GeometricFlux.jl[23] (Julia, Flux).


Copyright does not exist without permission and coordination with Delta DS and is considered a crime (GitHub)
