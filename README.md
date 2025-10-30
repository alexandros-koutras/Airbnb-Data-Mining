# Airbnb-Data-Mining


---


## 💡 Overview

This project is a data mining and analysis pipeline using Airbnb listing and review data for the Athens region. The project is divided into two phases: (1) Data Exploration and a Similarity-Based Recommendation System, and (2) Advanced Text Analysis using contemporary techniques like Word Embeddings and Pre-trained Transformer Models. The analysis is performed on two separate datasets (2019 and 2023) to identify and compare trends over a four-year period.


---


## ⚙️ Features

- Combined and cleaned monthly Airbnb CSV datasets for two time periods (2019 & 2023)
- Handled missing values, outliers, and data inconsistencies.
- Performed statistical analysis and extracted insights.
- Created interactive maps using latitude/longitude coordinates.
- Generated word clouds for textual data (neighborhood, transit, description, and comments).
- Compared temporal trends between 2019 and 2023 datasets.
- Preprocessed raw review text by removing punctuation and special symbols, converting all text to lowercase
  and removed stopwords
- Annotated dataset with positive / neutral / negative sentiment labels using Hugging Face models.
- Created training (80%) and testing (20%) datasets in .tsv format.
- Extracted text features using TF0IDF and word embeddings
- Trained multiple classification models (e.g., Logistic Regression, Random Forest, Naive Bayes).
- Evaluated and compared model performance on 2019 vs 2023 data.
- Visualized overall and per-neighborhood sentiment distributions with histograms.

---


🧰 Technologies & Libraries

- Language: Python 3.x
- Framework: Jupyter Notebook
- Data Manipulation: pandas, numpy
- Sentiment Analysis: transformers (Hugging Face)
- Visualization: matplotlib, seaborn
- Text Pre-processing: nltk
- Embeddings: gensim
- Geographic Data Visualization: Folium
- Feature Extraction: TF–IDF, Word2Vec


---


📂 Project Structure

├── notebooks/ # Includes the 2 notebooks for the project
└── README.md # Project documentation
