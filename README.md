# Transformer-Based Text Classification: Human vs AI Generated Text

This project focuses on **text classification** using **transformer-based models** to detect whether a given text is **human-generated** or **AI-generated**.  
It leverages Hugging Face's `transformers` library along with `PyTorch` and `scikit-learn` for model training and evaluation.

---

## 📌 Dataset
This project uses a dataset provided for academic purposes (**PAN 2025 - Generative AI Detection Task**).  
Due to license restrictions, the dataset is **not included** in this repository.  

If you want to run the notebook with your own dataset, make sure it follows the same format (`train.jsonl`):

- `text` → The input text  
- `label` → 0 for Human, 1 for AI  
- `genre` → Type of text (e.g., news, reviews, etc.)  
- `model` → Model used for AI generation (if available)  

---

## ⚙️ Installation & Requirements

Install dependencies with:
```bash
pip install transformers datasets pandas numpy scikit-learn matplotlib seaborn wordcloud
