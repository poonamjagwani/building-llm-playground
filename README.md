# 🚀 Building LLM Playground

An interactive LLM playground to demystify how prompts, tokenization, and decoding work. Load GPT2, Qwen3, and inspect their internals in real-time. Master the foundations of effective LLM usage! 🤖✨

---

## 📚 Overview

This introductory project explores how **prompts**, **tokenization**, and **decoding settings** work in practice. It builds the foundation for effective use of large language models by loading models like **GPT2** and **Qwen3**, inspecting them, and running them hands-on.

---

## 🎯 Learning Objectives

Upon completing this project, we would understand:

- 🧩 **Tokenization** - How raw text gets converted into discrete tokens
- 🏗️ **GPT-2 and Transformer Architectures** - The basics of how modern LLMs work
- 🤗 **Loading Pre-trained LLMs** - Using Hugging Face to access cutting-edge models
- 🎛️ **Decoding Strategies** - Different approaches to generate text (greedy, sampling, beam search, etc.)
- 📝 **Model Comparison** - Differences between completion and instruction-tuned models like Qwen3

---

## 🚀 Quick Start

### Step 1: Clone or Download the Project
Clone this repository or download it directly from GitHub and unzip the files:

```bash
git clone https://github.com/poonamjagwani/building-llm-playground.git
cd building-llm-playground
```

Alternatively, download the repository as a ZIP file from GitHub, then unzip it on your local machine.

### Step 2: Open in Your IDE
Open any preferred IDE:
- VS Code
- Cursor
- Antigravity
- Or any alternative!

### Step 3: Follow the Instructions
Open the notebook for the project and follow the below instructions on running it.

---

## 💻 How to Run

Choose one of two options below:

### Option A: Google Colab (Recommended) ☁️

**No local setup required!**

1. Upload the notebook to [Google Colab](https://colab.research.google.com)
2. Install dependencies if needed
3. Run cells in order

**Pros:** Free GPU access, no installation headaches

### Option B: Local Development with Conda 🖥️

**For reproducibility and full control:**

1. Each project includes setup instructions
2. Install dependencies using:
   - **Conda:**
     ```bash
     conda env create -f environment.yaml
     conda activate llm-playground
     ```
   - **UV** (faster alternative):
     ```bash
     uv pip install -r requirements.txt
     ```

**Pros:** Full control, faster iteration, learn local development practices

---

## 📁 Project Structure

```
building-llm-playground/
├── llm-playground.ipynb        # Main notebook
├── environment.yaml             # Conda environment
├── requirements.txt             # Python dependencies
├── data/                        # Optional: datasets
└── [supporting files]           # Optional: utilities, configs, etc.
```

### What's Inside:
- 📔 **Primary notebook** (`llm-playground.ipynb`) - Interactive walkthrough with explanations
- 📦 **Dependencies** (`environment.yaml` & `requirements.txt`) - All required packages
- 📂 **Data folder** - Datasets and supporting files (if needed)
- 🛠️ **Supporting files** - Utility scripts, config files, etc.

---

## 📋 Prerequisites

- Python 3.8+
- Jupyter Notebook (for local development)
- GPU recommended but not required (Colab provides free GPU)
