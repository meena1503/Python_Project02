**DDoS Attack Detection Using Machine Learning:**

A machine learning-powered system developed to detect Distributed Denial of Service (DDoS) attacks from network traffic data. The project implements supervised learning models and includes a GUI for real-time analysis and performance visualization.

**Project Overview:**

As cyber threats continue to rise, early detection of DDoS attacks is critical. This project focuses on detecting such attacks using machine learning models trained on network traffic features. It provides a visual interface to analyze predictions and evaluate the performance of different algorithms.

**Key Features:**

- Implements multiple ML models: Logistic Regression, Decision Tree, Random Forest, Naive Bayes  
- Analyzes network traffic data to classify benign vs malicious requests  
- Visualizes model performance using accuracy graphs and confusion matrix  
- GUI built with Tkinter for easy interaction and real-time result display

**Tools & Technologies:**

- **Language:** Python  
- **Algorithms:** Logistic Regression, Decision Tree, Random Forest, Naive Bayes  
- **Libraries:** pandas, scikit-learn, matplotlib, seaborn, Tkinter  
- **IDE:** VS Code / Jupyter Notebook  
- **Dataset:** Public DDoS dataset with labeled network request types

**GUI Overview:**

The Tkinter-based interface allows users to:
- Load and preprocess datasets
- Train different ML models
- View real-time predictions and accuracy comparisons

**Dataset:**

The dataset includes labeled traffic data containing both benign and DDoS patterns. Feature extraction and data cleaning were performed before training.

**How to Run:**

Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ddos-attack-detection.git
   cd ddos-attack-detection

Install the required libraries:
   pip install -r requirements.txt  

Run the application:
   python main.py  

