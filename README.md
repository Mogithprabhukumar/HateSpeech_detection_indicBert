# 🛡️ HATE SPEECH HUNTER: BERT TACKLES TAMIL

## 📌 Overview
Social media platforms have become a major communication hub but also a breeding ground for **hate speech** and **cyberbullying**. Current detection methods rely heavily on **manual moderation**, which is time-consuming and ineffective.  

This project introduces **Hate Speech Hunter**, an **AI-powered hate speech detection system** trained specifically for **Tamil text**. Using **IndicBERT**, our system **automates hate speech detection**, making online spaces safer.

---

## 🚀 Approach & Technologies Used

### 🧠 Machine Learning & Deep Learning Models:
- **IndicBERT:** A transformer-based model fine-tuned for Tamil text.
- **LSTM (Long Short-Term Memory):** Used for hate speech classification.
- **Random Forest & Logistic Regression:** Baseline models for comparison.
- **TF-IDF Vectorization:** Enhances feature extraction for text classification.

### 🗂 Dataset:
- **Tamil hate speech dataset** 📃 collected using **YouTube Comment Downloader**.
- **Preprocessing:** Stop word removal, stemming, special character handling.

### 📊 Evaluation Metrics:
To assess our model's effectiveness, we used:
- ✅ **Accuracy**
- ✅ **Precision**
- ✅ **Recall**
- ✅ **F1-score**

---

## 🔍 Key Findings & Challenges
- **IndicBERT outperformed traditional ML models**, capturing **Tamil-specific hate speech nuances**.
- **Handling noisy text, dialect variations, and code-mixed Tamil remains challenging**.
- **Future Improvements:**
  - Implement **data augmentation** to improve model generalization.
  - Enhance preprocessing to **handle special characters & misspellings**.
  - Explore **real-time detection** capabilities.

---

## 📅 Future Scope
- **Expansion to other Dravidian languages** for broader hate speech detection.
- **Integration into social media platforms** for **real-time moderation**.
- **Deploying as a web-based API** for developers to integrate into applications.

---

## 🔧 How to Use
### 🔽 Installation:
```bash
# Clone the repository
git clone https://github.com/your-repo-name.git
cd hate-speech-hunter

# Install dependencies
pip install -r requirements.txt
