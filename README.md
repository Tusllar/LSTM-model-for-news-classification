# LSTM-model-for-news-classification
This repository contains a deep learning project for text classification of news topics based on a given dataset (`train_02.csv` and `test_02.csv`). The model uses multiple LSTM layers along with Dense and Dropout layers to classify news articles into 4 categories:  
- 1: World  
- 2: Sports  
- 3: Business  
- 4: Science and Technology  

## 📂 Dataset

- **train_02.csv**: Training data with class labels and news descriptions.
- **test_02.csv**: Testing data with class labels and news descriptions.

Each row contains:
- Class index (1-4)
- Text description

## 🧪 Data Preprocessing
- Text cleaning (lowercasing, punctuation removal, tokenization)
- Padding sequences to a fixed length (e.g., maxlen=100)
- Label encoding for class indices (1-4)
- Train/Test split: 80% for training, 20% for validation

## 💡 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/news-classification-lstm.git
   cd news-classification-lstm

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
