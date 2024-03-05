<h2>Classical Graph Neural Network for High Energy Physics (HEP) at CERN</h2>
<p>This notebook presents a detailed exploration of applying classical Graph Neural Networks (GNNs) to High Energy Physics (HEP) data from CERN. It focuses on the innovative approach of utilizing graph-based data structures to analyze and classify collision events, a key aspect in the field of particle physics. By leveraging the spatial relationships between particles generated in high-energy collisions, the project aims to enhance event classification and understanding.</p>

<b>Libraries and Frameworks:</b>
<ul>
  <li><code>numpy</code> for handling numerical operations and data manipulation.</li>
  <li><code>torch</code> and its extension <code>torch-geometric</code> for constructing and training GNN models.</li>
  <li><code>matplotlib</code> and <code>networkx</code> for data visualization and graph-based data structures, respectively.</li>
  <li><code>scikit-learn</code> for additional machine learning utilities like train-test split and metrics evaluation.</li>
</ul>

<b>Data Overview:</b>
<ul>
  <li>Utilizes the QG_jets dataset loaded from an NPZ file, which includes features (X) representing particle properties and labels (y) indicating the class of each jet event.</li>
  <li>Each particle's feature vector includes its momentum and type, crucial for understanding the event's dynamics.</li>
</ul>

<b>Methodology:</b>
<ul>
  <li>Creation of adjacency matrices and edge indices to represent the geometric and dynamic relationships between particles within each event.</li>
  <li>Training a GNN model to learn from the graph-based representation of events, aiming to classify them accurately.</li>
  <li>Evaluation of model performance through loss metrics and accuracy, using both training and validation datasets to ensure model generalization.</li>
</ul>

<b>Key Findings and Insights:</b>
<ul>
  <li>Demonstrates the potential of GNNs in capturing the complex relationships and interactions between particles in HEP events, surpassing traditional analysis methods.</li>
  <li>Highlights the importance of graph-based data structures in representing non-Euclidean data, such as the spatial arrangements of particles in collider events.</li>
  <li>Emphasizes the role of deep learning, particularly GNNs, in advancing the analysis capabilities in HEP and other scientific fields.</li>
</ul>

<b>Conclusion:</b>
<p>The notebook provides a comprehensive guide on applying GNNs to HEP data, showcasing the enhanced classification performance and deeper insights into the particle interactions. This approach opens new avenues for research and experimentation in particle physics, leveraging the latest advancements in machine learning and graph theory.</p>
