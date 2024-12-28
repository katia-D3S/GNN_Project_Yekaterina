# GNN_Project_Yekaterina
In addition to processing tabular, textual, audio data, and images, deep learning often involves solving tasks with graph-structured data. Examples of such data include descriptions of road and computer networks, social graphs, citation graphs, molecular graphs, and knowledge graphs that describe relationships between entities, events, and abstract categories. 
Graph data is quite diverse and can differ in the following aspects:
- Size: This refers to the number of nodes and/or edges.
- Feature descriptions of nodes and edges: Depending on the task, graphs may contain information only on the nodes, only on the edges, or on both.
- Homogeneity vs. heterogeneity: Graphs can be homogeneous or heterogeneous, depending on whether the nodes and edges in the graph are of the same type or not.

This project is dedicated to the overall understanding of what graphs are, and how they work, their applications and limitations.
First, it is important to understand the graph, which is a complex data structure that represents the objects and relationships between them. The ZINC dataset served as an example dataset, that contains around 250,000 molecular graphs (homogenous) with up to 38 heavy atoms, where atoms are nodes and bonds are edges
![image](https://github.com/user-attachments/assets/f19eeab5-01fb-45bf-b52f-f12ac6c14063)

In the second part,a GNN model was created and trained on the ZINC dataset. This is a graph-level task, that includes graph regression, where we need to predict the 'y' - our target variable. The fundamental operation of Graph Neural Networks (GNNs) is essentially the same as that of Convolutional Neural Networks (CNNs). In a GNN, layers are applied sequentially, aggregating information from neighboring nodes and updating the information at each node. This is analogous to standard convolutions, which is why such layers are referred to as graph convolutions. A graph convolution takes as input a graph with hidden states at its nodes and edges and outputs the same graph, but with updated, more informative hidden states.

![image](https://github.com/user-attachments/assets/6b0175f3-92e5-4ac2-8363-5051b1a93adf)
Both training loss and validation loss are steadily decreasing, the model is learning and improving its predictions on both training and validation data over each epoch. Training and validation are quite close ti each other throughout the epochs, which signifies that the model does not overfit!!
