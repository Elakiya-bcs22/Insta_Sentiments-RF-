📸 Insta Sentiments — Instagram Sentiment Classifier (Random Forest)

A lightweight Python app that analyzes Instagram captions or comments and classifies sentiment as positive, negative, or neutral using a Random Forest model 🌲🤖. Perfect for beginners interested in NLP, model building, and prediction workflows.

📂 Project Structure
Insta_Sentiments-RF/
├── app.py                  # Runs predictions using the trained model
├── train.py                # Trains the Random Forest sentiment model
├── data/                   # Raw and/or preprocessed datasets
├── model/                  # Trained model (e.g., `.pkl`)
├── requirements.txt        # Python dependencies
└── README.md               # This file

⚙️ Installation

Clone the repo:

git clone https://github.com/Elakiya-bcs22/Insta_Sentiments-RF-.git
cd Insta_Sentiments-RF-


Install dependencies:

pip install -r requirements.txt

🚀 Usage

Train the model (if starting from scratch or updating):

python train.py


Run the sentiment classifier:

python app.py

✨ Features

Built using a Random Forest classifier for sentiment analysis 🌳

Clean, modular structure—easy to extend or integrate into a Flask UI 🖥️

Beginner-friendly framework—ideal for learning and experimentation 📘

Easy to swap datasets or upgrade the model (TF-IDF, word embeddings, neural networks) 🔄

📈 Next Steps

Enhance NLP performance with better text preprocessing (lemmatization, stop-word removal) 📝

Use richer features like TF-IDF vectors or word embeddings for improved accuracy 📊

Add a Flask or web UI for live sentiment classification 🌐

Expand to classifying emojis, emoticons, or hashtags alongside text 😀🎯

🤝 Contribution

Contributions are welcome! Feel free to:

Improve feature engineering or text preprocessing ✨

Enhance training or evaluation pipelines ✔️

Add documentation, unit tests, or deployment scripts 📦

Simply open an issue or submit a PR—happy to collaborate! 🚀
