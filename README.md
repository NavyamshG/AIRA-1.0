# Predicting Scientific Research Trends Based on Hyperedge Link Prediction

**Business objective**
Explore the future of scientific research through hypergraph-based link prediction. This project applies advanced hypergraph analysis techniques to predict emerging relationships between research topics, offering valuable insights into the evolution of multidisciplinary research fields.

🔍 **Project Overview**
This project leverages models like HyperGCN, HyperSage, and HNN-LSTM to analyze hypergraphs and predict hyperedge links. By identifying patterns in research topics, the goal is to forecast scientific trends and foster collaboration across disciplines.

**Key outcomes include:**

- **Hypergraph Construction:** Build hypergraphs where nodes represent research topics and hyperedges denote multi-topic associations.
- **Link Prediction:** Forecast new research connections using advanced neural network models.
- **Evaluation and Visualization:** Generate insights through performance metrics and visualizations of hypergraph structures.

📦 **Prerequisites**
Ensure Python is installed along with the following libraries:

- `numpy==1.26.4`
- `pandas`
- `scikit-learn`
- `torch==2.1.2`
- `torchvision==0.16.2`
- `torchaudio==2.1.2`
- `tensorflow`
- `networkx`
- `matplotlib`
- `gensim`
- `deepwalk`
- `torch-geometric`

You can install them using the following command:

```bash
pip install numpy pandas scikit-learn torch torchvision torchaudio tensorflow networkx matplotlib gensim deepwalk torch-geometric
```

📂 **Project Structure**

1. **Data Cleaning and EDA** (`DataCleaning_EDA.ipynb`)

   - Perform data cleaning and preprocessing to extract research topics.
   - Build incidence matrices representing hypergraph connections.

2. **Embedding Generation** (`Embeddings.ipynb`)

   - Generate embeddings using techniques like DeepWalk and Word2Vec.
   - Create vector representations for nodes and hyperedges.

3. **HNN-LSTM Model** (`HNN_LSTM.ipynb`)

   - Develop and train a Hypergraph Neural Network (HNN) with LSTM layers.
   - Perform time-series prediction for hyperedge link formation.

4. **HyperGCN Model** (`HyperGCN.ipynb`)

   - Apply HyperGraph Convolutional Networks for link prediction.
   - Evaluate model performance using metrics like accuracy and F1-score.

🚀 **Steps to Run the Project**

1. **Prepare Data:**

   - Run `DataCleaning_EDA.ipynb` to preprocess and generate the hypergraph.

2. **Generate Embeddings:**

   - Use `Embeddings.ipynb` to compute embeddings using DeepWalk or Word2Vec.

3. **Train Models:**

   - Train models using `HNN_LSTM.ipynb` or `HyperGCN.ipynb`.

4. **Evaluate and Visualize:**

   - Assess model performance and generate visualizations of predicted links.

📊 **Key Features**

- Accurate prediction of emerging research trends using hypergraph-based models.
- Visualization of topic associations and evolving research patterns.
- Comparative analysis of model performance using multiple evaluation metrics.

🤝 **Conclusion**
This project serves as a powerful tool for analyzing and forecasting scientific research trends. By utilizing hypergraph structures and state-of-the-art neural networks, it provides actionable insights for researchers and policymakers.

---

For any questions or contributions, feel free to reach out!
