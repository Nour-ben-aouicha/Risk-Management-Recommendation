# 🚀 Risk Management Project Overview 🚀
Welcome to the Risk Management Project! This GitHub repository encapsulates a dynamic venture in project management literature exploration and analysis. 📚
<br>
### Data Extraction and Cleaning 🧹
We initiated the project by extracting content from PMBOK and PMI risk management sections, employing image extraction using pytesseract and meticulous text processing to create clean and organized CSV datasets from both PDF sources.<br>

### Text Analysis and Modeling 📊
Moving forward, we delved into advanced text analysis, including summarization, keyword extraction, and topic modeling using Gensim. Visualization of these topics was achieved using the PyLDAvis library, providing an insightful representation:<br><br>
![393846391_190744340730509_4711644479992431814_n](https://github.com/Nour-ben-aouicha/Risk-Management-Recommendation/assets/92543024/4f07c76b-0c7c-4201-a4a0-0232b8adc6da)
<br>
### Graph Modeling 🌐
Graph modeling is the pivotal phase, where we employed NetworkX and Matplotlib to visualize taxonomic and non-taxonomic relationships in a directed graph. This not only enhanced text processing through stemming and concept association but also facilitated a deeper understanding of entity relationships.<br>
![output](https://github.com/Nour-ben-aouicha/Risk-Management-Recommendation/assets/92543024/290e8b10-c7fa-4437-a738-2e346127ed9d)
<br>
### Feature Engineering and Graph Neural Network (GNN) 🤖
Feature engineering involved converting the graph into sentences, training a Word2Vec model, and obtaining node embeddings. Subsequently, we trained a Graph Neural Network (GNN) using TensorFlow's Keras API, visualizing the learning process and ensuring effective representation of graph patterns.<br>

### Recommendation System Implementation 🎓
The final step involved the implementation of a knowledge-based recommendation system. We incorporated RoBERTa-based neural networks for text classification, using the accuracy evaluation metric.<br>
![aa](https://github.com/Nour-ben-aouicha/Risk-Management-Recommendation/assets/92543024/ec16d367-6cf6-4550-8f09-b7d249c59856)
<br>
Dive into the details by checking the report above! 🌟
