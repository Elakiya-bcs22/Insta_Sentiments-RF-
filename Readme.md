## Insta Sentiments — Instagram Sentiment Classifier (Random Forest) 

A Python-based machine learning application that analyzes Instagram text (such as captions or comments) and classifies sentiment as **positive**, **negative**, or **neutral** using a **Random Forest** model.  
This project is great for beginners looking to understand NLP, model training, and building prediction pipelines.

---

##  Project Structure

```
Insta_Sentiments-RF/
├── app.py                  # Runs predictions using the trained model
├── train.py                # Trains the Random Forest sentiment model
├── data/                   # Stores raw and/or preprocessed datasets
├── model/                  # Contains the trained model file (e.g., `.pkl`)
├── requirements.txt        # Lists required Python packages
└── README.md               # This documentation file
```

---

##  Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Elakiya-bcs22/Insta_Sentiments-RF-.git
   cd Insta_Sentiments-RF-
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

##  Usage

1. **Train the model** (if training from scratch or updating it):

   ```bash
   python train.py
   ```

2. **Run the application** to classify sentiment for new text inputs:

   ```bash
   python app.py
   ```

---

##  Features

- **Random Forest** classifier for sentiment analysis.
- Supports both training and inference in a clean pipeline.
- Beginner-friendly and modular enough for easy customization or expansion.
- Easily swappable dataset or model, with scope for backend extension (e.g., Flask web interface).

---

##  Conclusion

The **Insta Sentiments** project delivers robust sentiment predictions from Instagram text using a Random Forest model.  
With more labeled data and enhanced feature engineering (e.g., TF-IDF, embeddings), its accuracy and handling of nuanced sentiments can be further improved.  
