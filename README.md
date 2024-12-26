# GNN_Project_Yekaterina
In addition to processing tabular, textual, audio data, and images, deep learning often involves solving tasks with graph-structured data. Examples of such data include descriptions of road and computer networks, social graphs, citation graphs, molecular graphs, and knowledge graphs that describe relationships between entities, events, and abstract categories. 

This project is dedicated to the overall understanding of what graphs are, and how they work, their applications and limitations.
First, it is important to understand the graph, which is a complex data structure that represents the objects and relationships between them. The ZINC dataset served as an example dataset
![image](https://github.com/user-attachments/assets/f19eeab5-01fb-45bf-b52f-f12ac6c14063)

In the second part,a GNN model was created and trained on the ZINC dataset.
**ZINC dataset** contain around 250,000 molecular graphs with up to 38 heavy atoms, where atoms are nodes and bonds are edges. Goal is to predict properties such as solubility or drug-likeness based on those graph representations.

In the next part I played around with optimization techniques trying to improve the performance of the model. The architecture was changed multiple times, learning rate, batch size, dropout added, batch normalization added, etc.
![image](https://github.com/user-attachments/assets/6b0175f3-92e5-4ac2-8363-5051b1a93adf)
