# Hypothesis_Generation_ML_Model

readme_content = """
# HYPER-AI: Scientific Hypothesis Generation and Statistical Validation (CLI Version)

HYPER-AI is an AI-powered research assistant that generates and scientifically validates new research hypotheses from scientific abstracts. It combines NLP-based hypothesis generation with semantic similarity analysis and statistical inference to assist researchers in proposing plausible, data-driven hypotheses.

This is a simple, command-line based version of the project, ideal for research validation and experimentation.

## 🧠 Key Features

- Generates plausible research hypotheses from scientific abstracts using HuggingFace's BART model  
- Predicts the scientific domain (AI, Biology, etc.) using a trained classification model  
- Computes cosine similarity between generated hypothesis and input abstract using Sentence Transformers  
- Statistically validates hypotheses with:  
  ✔ T-Test for small-sample significance  
  ✔ Z-Test for large-sample approximation  
- Visualizes similarity score distribution with histogram  

## 🛠 Tech Stack

- Python 3.x  
- scikit-learn (classification)  
- HuggingFace Transformers (hypothesis generation)  
- Sentence Transformers (similarity analysis)  
- SciPy & NumPy (statistical testing)  
- seaborn & matplotlib (visualizations)  

## 📦 How to Run

1. Place your dataset CSV (e.g., scientific_data_5000.csv) in the project directory  
2. Ensure your trained_model.pkl (classification model) is available  
3. Run the script:  
