# What are graphs ?
Graphs are everwhere ! Examples of graphs include social networks (Twitter, Linkedin, facebook, etc.). In additionb researcxh articles (and papers with citations), molecules are also examples. Graphs also plahy a crirtical role in software execution platforns (like DAGs, TensorFlow execution, etc.). At the most basic level, a graph (G) is made up of nodes (N) connected by edges (E). The edge can be directed (direction and weights) as well undirected. This structure is powerful to represent many scenarios (also can be called as a graph schema).

A next level can be what we call as knowledge graphs (diverse domain specific such as encyclopedias, any website with hyperlinks), programming repositories like pypi.


# What is Graph Machine Learning ?
Once you have a graph schema and data loaded into its structure you can perform a number of computations on it. At the most basic level is the concept of traversal across the graph (and using the interconnection/hops), clusters, etc.). In more advanced cases we can explore graph neural network kinds of capability.

[Introduction](https://huggingface.co/blog/intro-graphml)

# GNN | Graph Neural Network
## What are GNN ?
GNNs can be used to answer questions about multiple characteristics of these graphs. By working at the graph level, we try to predict characteristics of the entire graph. We can identify the presence of certain “shapes,” like circles in a graph that might represent sub-molecules or perhaps close social relationships. 

GNNs can be used on node-level tasks, to classify the nodes of a graph, and predict partitions and affinity in a graph similar to image classification or segmentation. Finally, we can use GNNs at the edge level to discover connections between entities, perhaps using GNNs to “prune” edges to identify the state of objects in a scene.

## Basics of GNN / Tutorials
|  	| Topic 	| Link 	| Documentation 	| CodeLinks 	|
|---	|---	|---	|---	|---	|
| 1 	| Pytorch Geometric  	| [Link](https://github.com/AntonioLonga/PytorchGeometricTutorial) 	| [Link](https://pytorch-geometric.readthedocs.io/en/latest/notes/colabs.html) 	|  	|
| 2 	| UVA Deep Learning Course 	| [Link](https://www.youtube.com/channel/UCpvn0ycxIA6Uf8W00OX3frQ) 	| [Link](https://uvadlc-notebooks.readthedocs.io/en/latest/) 	|  	|
| 3 	| UVA GNN Playlist 	| [Link](https://www.youtube.com/playlist?list=PL7G194JTFn8oMpwPjyGoTM19vO0DD6cPK) 	| [Link](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial7/GNN_overview.html) 	| [Link](https://colab.research.google.com/github/phlippe/uvadlc_notebooks/blob/master/docs/tutorial_notebooks/tutorial7/GNN_overview.ipynb) 	|
| 3.1 	| Part 1<br>In this tutorial, we will discuss the application of neural networks on graphs. Graph Neural Networks (GNNs) have recently gained increasing popularity in both applications and research, including domains such as social networks, knowledge graphs, recommender systems, and bioinformatics. While the theory and math behind GNNs might first seem complicated, the implementation of those models is quite simple and helps in understanding the methodology. Therefore, we will discuss the implementation of basic network layers of a GNN, namely graph convolutions, and attention layers. Finally, we will apply a GNN on semi-supervised node classification and molecule categorization. This notebook is part of a lecture series on Deep Learning at the University of Amsterdam. The full list of tutorials can be found at https://uvadlc-notebooks.rtfd.io.<br>Link to the notebook: https://uvadlc-notebooks.readthedocs....<br><br>00:00 Introduction<br>01:08 Graph representation<br>04:30 Graph convolutions<br>10:20 Graph attention 	| https://youtu.be/fK7d56Ly9q8 	|  	|  	|
| 3.2 	| Part 2<br>In this tutorial, we will discuss the application of neural networks on graphs. Graph Neural Networks (GNNs) have recently gained increasing popularity in both applications and research, including domains such as social networks, knowledge graphs, recommender systems, and bioinformatics. While the theory and math behind GNNs might first seem complicated, the implementation of those models is quite simple and helps in understanding the methodology. Therefore, we will discuss the implementation of basic network layers of a GNN, namely graph convolutions, and attention layers. Finally, we will apply a GNN on semi-supervised node classification and molecule categorization. This notebook is part of a lecture series on Deep Learning at the University of Amsterdam. The full list of tutorials can be found at https://uvadlc-notebooks.rtfd.io.<br>Link to the notebook: https://uvadlc-notebooks.readthedocs....<br><br>00:00 PyTorch Geometric<br>02:54 Node-level tasks<br>08:51 Edge-level tasks<br>09:50 Graph-level tasks<br>16:03 Conclusion 	| [Link](https://youtu.be/ZCNSUWe4a_Q) 	|  	|  	|
| 4 	| Node Classification with Graph Neural Networks<br> (Khalid Salama) 	| [Link](https://keras.io/examples/graph/gnn_citations/) 	|  	| [Link](https://colab.research.google.com/github/keras-team/keras-io/blob/master/examples/graph/ipynb/gnn_citations.ipynb) 	|
