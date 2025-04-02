

# Document Clustering Project

## Overview 📖✍️  
This project applies **unsupervised learning techniques** to cluster documents from two datasets:  
- **People Wikipedia Dataset**  
- **20 Newsgroups Dataset**  

The goal is to uncover inherent structures within these datasets, providing insights into the natural groupings of the documents.

---

## Datasets 📚  
### 1️⃣ 20 Newsgroups Dataset  
- **Description**: Contains ~20,000 newsgroup documents categorized into 20 different topics, covering politics, religion, sports, technology, and more.  
- **Source**: Available via `sklearn.datasets.fetch_20newsgroups()`

### 2️⃣ People Wikipedia Dataset  
- **Description**: Consists of biographical texts from Wikipedia about various individuals.  
- **Source**: Extracted and preprocessed for clustering tasks.

---

## Approach & Methodology 🛠️  
### 1️⃣ Data Preprocessing  
- Text cleaning (removal of stopwords, punctuation, and special characters)  
- Tokenization and vectorization (TF-IDF)

### 2️⃣ Feature Extraction  
- Using **TF-IDF Vectorization** to convert text into numerical representations.  
- Applied **BERT embeddings** for richer semantic representations of the text.

### 3️⃣ Clustering Techniques  
- **K-Means Clustering**  
- Enhanced clustering with **UMAP** for dimensionality reduction and **scaling** to improve model performance.

### 4️⃣ Evaluation & Visualization  
- **Silhouette Score** for cluster evaluation  
- **Word Clouds & PCA plots** for visualization

### 5️⃣ Business Insights & Cluster Meaning  
### News Clusters

#### **Cluster 1: Computer Graphics**
- **Insights**: 
  - For **Tech and Gaming Companies**: Invest in AI-driven graphics and real-time rendering.
  - For **Marketing & Advertising**: Use AR/VR to create immersive marketing experiences.
  - For **Education**: Develop educational platforms with 3D visualizations.

#### **Cluster 2: Space**
- **Insights**: 
  - For **Tech & Innovation**: Invest in satellite data analytics and propulsion technology.
  - For **Space Tourism**: Leverage VR-based space travel simulations.

#### **Cluster 3: Religion**
- **Insights**: 
  - For **Media**: Develop multilingual platforms for trusted religious content.
  - For **Tech**: Create prayer reminder apps and VR experiences for religious tourism.

### People Wikipedia Clusters

#### **Cluster 0: Business, Books & Politics**
- **Insights**:
  - **Publishing & Books**: Analyze political themes to shape book releases.
  - **Government**: Track discussions to shape policy strategies.

#### **Cluster 1: Competitive Sports & Championships**
- **Insights**:
  - **Sports Brands**: Partner with athletes for brand visibility.
  - **Media**: Create data-driven narratives around sports achievements.

#### **Cluster 2: Music & Entertainment**
- **Insights**:
  - **Music Production**: Track trending songs and albums for targeted marketing.
  - **Film Industry**: Leverage popular music trends for film content development.

#### **Cluster 3: Sports & Teams**
- **Insights**:
   - **Sports Brands**: Partner with teams and athletes for high visibility during major sporting events like World Cup or Olympics.
   - **Media: Leverage** data-driven storytelling around team performance and milestones to engage fans and boost media coverage.
   - **Fitness & Training Platforms**: Develop AI-based training programs and VR coaching solutions for athletes and teams, focusing on personalized performance improvement.
---

## Installation & Setup ⚙️  
### Prerequisites  
Ensure you have the following Python libraries installed:  
```bash  
pip install numpy pandas scikit-learn nltk matplotlib seaborn wordcloud transformers umap-learn
```

### Running the Project  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/MennatullahTarek/Document-Cluster-Project.git  
   cd Document-Cluster-Project  
   ```  
2. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook Document_cluster_project.ipynb  
   ```  
3. Run all the cells sequentially to execute the analysis.

---

## Results & Insights 📊  
- Successfully clustered documents into meaningful groups.  
- **TF-IDF + K-Means** provided interpretable topic clusters.  
- **BERT embeddings** enhanced clustering with more accurate semantic representations.  
- **UMAP** helped visualize clusters in lower dimensions.  
- **LDA** generated topic distributions that align with human-labeled categories.

---

## Improvements 🚀  
- Experimenting with **Deep Learning (BERT embeddings)** for better representations.

---

### ⭐ Star this repository if you found it useful!
