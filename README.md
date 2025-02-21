# music-genre-classification
Music Genre Classification Project with PCA and Logistic Regression

#### 📌 Project Overview

In this project, we use Principal Component Analysis (PCA) and Logistic Regression to classify music tracks into genres based on extracted audio features. Our approach reduces dimensionality while maintaining classification accuracy, making it applicable for music streaming platforms, audio data analysis, and recommendation systems.

#### 🚀 Key Features

- Dimensionality Reduction with PCA: Transforms high-dimensional musical data into a smaller feature set.
- Supervised Learning with Logistic Regression: Predicts genres based on structured audio characteristics.
- Handling Unlabeled Data: Applies the trained model to predict missing genres.
- Performance Comparison: Evaluates classification accuracy with and without PCA.
- Data Visualization: Includes correlation analysis and genre distribution graphs.

#### 📂 Project Structure
 
 - 📄 music_genre_classification.ipynb
 - 📄 README.md
 - 📊 dataset.csv 
 - 📊 Music Data Legend.xlsx 
 - 📁 images

#### 📊 Dataset

The dataset contains musical attributes such as tempo, vocal presence, and instrumental overlaps.
A portion of the dataset lacks genre labels, requiring semi-supervised classification.

#### 🔧 Technologies Used

- Python (Jupyter Notebook)
- Libraries: pandas, NumPy, scikit-learn, seaborn, matplotlib

#### 🛠️ How to Run the Project

1. Clone the repository:

  git clone https://github.com/Danielariscob/music-genre-classification.git
  cd music-genre-classification

2. Install dependencies:

  pip install -r requirements.txt

3. Run the Jupyter Notebook:

  jupyter notebook

#### 🎯 Results & Conclusions

- PCA reduced dataset dimensionality while maintaining classification performance.
- Logistic Regression achieved comparable accuracy with and without PCA, proving its robustness.
- The predicted genres followed a logical distribution, validating the model’s effectiveness.

#### 📌 Applications

- Music Streaming: Automatic genre tagging for personalized recommendations.
- Audio Data Management: Improving metadata for large media libraries.
- Content Curation: Organizing music collections with minimal human intervention.

#### 📢 Next Steps

- Implement deep learning models (e.g., CNNs) to improve classification accuracy.
- Test with larger and more diverse datasets.
- Explore other feature extraction techniques (e.g., spectrogram analysis).

#### 📬 Contact

For questions or collaboration, reach out via LinkedIn or check my portfolio at daniela-risco.com.
