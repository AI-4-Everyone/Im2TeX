# 🧠 Image-to-LaTeX: Generating Image to LaTeX synthetic Datasets

Welcome to **Image-to-LaTeX**, a project designed to generate high-quality **synthetic image-to-LaTeX datasets**. This resource is ideal for training and evaluating models on coding in LaTeX and generating higher quality tables and diagrams.
---

## 📑 Table of Contents

- [🚀 What’s Inside](#-whats-inside)
- [🚀🚀 Getting Started](#-getting-started)
- [📘 Paper (Coming Soon)](#-paper-coming-soon)
- [📁 Repository Structure](#-repository-structure)
- [🔄 Pipeline](#-pipeline)
- [📦 Setup](#-setup)
- [📤 Dataset Access](#-dataset-access)
- [📄 License](#-license)
- [📚 Citation](#-citation)

---

## 🚀 What’s Inside

- 📓 **Notebook** for finetuning VLMs with Reinforcement Learning on this dataset  
- 📓 **Notebook** for VLMs Evaluation on this dataset  
- ⚡ Ready-to-use for fine-tuning custom LLMs, vision-language models, or benchmarking pipelines

---

## 🚀🚀 Getting Started
To quickly load and explore the dataset in Python, you can use the 🤗 `datasets` library:

```python
from datasets import load_dataset

# Load the test split of the Im2TeX dataset
dataset = load_dataset('AI-4-Everyone/Im2TeX')

# Print dataset info
print(dataset)
```
---

## 📘 Paper (Coming Soon)

📝 A detailed dataset paper describing the methodology, QA strategy, and dataset statistics is coming soon.  
<!-- Replace the placeholder below with your actual paper link -->
**[📄 Read the Paper (coming soon)](https://arxiv.org/abs/XXXXX)**

---

## 📁 Repository Structure

```text
├── Finetuning/
├── Examples/ # Example generated images and records
├── Evaluation/
├── README.md
└── LICENSE
```
## 📦 Setup

```bash
pip install -r requirements.txt
```

## 📤 Dataset Access
You can find the generated dataset hosted on 🤗 Hugging Face:
**[TableQA Synthetic Dataset →](https://huggingface.co/datasets/AI-4-Everyone/Im2TeX)**

## 📄 License

This project is licensed under the [MIT License](LICENSE).

You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided that the original copyright and permission notice are included in all copies or substantial portions of the software.

## 📚 Citation

If you use this code or dataset in your research, please cite:

**Plain-text citation:**  
Marc Haraoui, Boammani Aser Lompo *Im2TeX*. GitHub repository: https://github.com/AI-4-Everyone/Im2TeX

**BibTeX:**
```bibtex
@misc{haraouilompo2025tableqa,
  author       = {Marc Haraoui and Boammani Aser Lompo},
  title        = {Im2TeX},
  year         = {2025},
  howpublished = {\url{https://huggingface.co/datasets/AI-4-Everyone/Im2TeX}},
}
