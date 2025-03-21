# Plagiarism Checker AI

This repository contains a paraphrase detection model using **Logistic Regression** with **TF-IDF Vectorization**.

## Model Performance

The model was trained and evaluated with the following results:

| Metric         | Score |
|--------------|--------|
| **Training Accuracy** | 0.7265 |
| **Testing Accuracy**  | 0.7052 |
| **Precision**  | 0.7058 |
| **Recall**     | 0.7052 |
| **F1-score**   | 0.7050 |

### **Classification Report**
| Class | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| **0** | 0.72      | 0.68   | 0.70     | 36,795  |
| **1** | 0.69      | 0.73   | 0.71     | 36,680  |
| **Accuracy** | | | **0.71** | 73,475 |
| **Macro Avg** | 0.71 | 0.71 | 0.71 | 73,475 |
| **Weighted Avg** | 0.71 | 0.71 | 0.70 | 73,475 |

![](https://github.com/nknitish9/plagiarism_checker/blob/main/Image/Screenshot%202025-03-21%20130530.png)

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python main.py
   ```

## Dataset
The dataset used is **MIT Plagiarism Detection Dataset**, where the task is to predict whether one sentence is a paraphrase of another.

📌 **Dataset Link:** [MIT Plagiarism Detection Dataset](https://www.kaggle.com/datasets/ruvelpereira/mit-plagairism-detection-dataset?utm_source=chatgpt.com)

## Future Improvements
- Use deep learning models (LSTM, Transformers)
- Optimize feature engineering
- Fine-tune hyperparameters for better accuracy

---

Feel free to contribute or raise issues!

📌 **Author:** Nitish Kumar  
📧 **Contact:** nknitish90062@gmail.com.com
