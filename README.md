# 🚀 Deep Learning Final Project

This project enhances transformer-based language models, specifically **BERT**, to improve story-ending comprehension. By fine-tuning a pre-trained model, we refine its ability to evaluate narrative coherence and select the most suitable story ending.

## 🔹 Project Overview
- Fine-tunes **BERT** for contextual story understanding.
- Adapts and extends the **OpenAI fine-tune-transformer-lm** framework.
- Explores different training strategies, hyperparameter tuning, and dataset enhancements.

## 📂 Files Overview
- **`Final_project_dl.ipynb`** – Main notebook for training and evaluation.
- **`Final Project Report.pdf`** – Comprehensive report detailing the project, methodologies, experiments, and results.

## 📖 References
This project is based on the original implementation from:
- [OpenAI's fine-tune-transformer-lm](https://github.com/openai/finetune-transformer-lm).

## 👥 Individual Contributions
- **Adi Yogev Golbari**: Led the integration of the **BERT-based model**, incorporated additional training data from Wikipedia, and modified the existing codebase to support these enhancements. Responsibilities included:
  - Modifying the **data preprocessing pipeline**.
  - Updating the **model architecture**.
  - Ensuring seamless compatibility with the training framework.

- **Or Chen**: Focused on optimizing the model through **hyperparameter tuning** and experimental adjustments. Responsibilities included:
  - Fine-tuning **learning rates, batch sizes, and dropout rates** to enhance performance.
  - Integrating and evaluating the **IMDb dataset** to explore its impact on model generalization and contextual understanding.
