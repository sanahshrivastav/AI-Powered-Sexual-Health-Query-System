
> An AI-powered sexual education content generator built for awareness, accuracy, and accessibility.



## Overview

AI-based system designed to generate **accurate, age-appropriate, and context-aware educational responses** to questions related to **sexual health and education**.  

The project uses **transformer-based language models** (such as GPT or T5 architectures) combined with **prompt-engineering techniques** and **ethical content filtering** to ensure safe, factual, and inclusive information delivery.

The system is structured within a Jupyter Notebook (`sexed_ans(3).ipynb`) for research, experimentation, and demonstration of **responsible text generation** in sensitive educational domains.

---

## Objectives

- **Generate** sexual education responses that are informative, respectful, and unbiased.  
- **Ensure safety and ethical compliance** using content filtering and controlled generation.  
- **Demonstrate fine-tuning** and prompt-based conditioning for specific response control.  
- **Promote accessibility** of sex education through AI-driven conversational tools.  

---

## Features

- **Transformer-based text generation**
- **Contextual prompt conditioning** for structured outputs  
- **Toxicity and bias filtering** using moderation layers  
- **Data preprocessing and tokenization pipeline**  
- **Q&A simulation** for real-world usage  
- **Customizable notebook** for researchers and educators  

---

## Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.9+ |
| **Core Libraries** | `transformers`, `torch`, `numpy`, `pandas` |
| **Preprocessing** | `nltk`, `re`, `textblob` |
| **Notebook Environment** | `jupyter`, `tqdm`, `matplotlib` |
| **Deployment Ready** | Compatible with Colab, local GPU (T4/V100) |

---

## Getting Started

Follow these steps to set up and run the notebook locally or in Google Colab.

### 1. Clone the Repository

gh repo clone sanahshrivastav/AI-Powered-Sexual-Health-Query-System

### 2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate    # macOS / Linux
venv\Scripts\activate       # Windows

### 3. Installing dependencies 

pip install torch transformers pandas numpy jupyter tqdm textblob

### 4. Run the notebook

<img width="117" height="20" alt="image" src="https://github.com/user-attachments/assets/c6bbca18-62a1-46cb-ab9d-835b71be0a96" />

### Workflow

| Section                    | Description                                           |
| -------------------------- | ----------------------------------------------------- |
| **1. Setup**               | Import libraries, install missing dependencies        |
| **2. Data Preparation**    | Load input data or initialize knowledge base          |
| **3. Model Loading**       | Load transformer model (e.g., GPT-2 / T5 / DistilGPT) |
| **4. Prompt Construction** | Design structured prompts for accurate responses      |
| **5. Response Generation** | Generate educational answers using the model          |
| **6. Filtering**           | Apply toxicity, bias, and coherence filters           |
| **7. Evaluation**          | Review generated outputs, analyze model performance   |


##  Ethical Considerations
This project is developed for **educational and research purposes** only.  
It aims to promote **scientifically accurate and socially responsible** sexual education.  

**Key ethical guidelines followed:**
- No explicit or adult content generation.  
- Ensures inclusivity and gender neutrality.  
- Focuses on awareness, safety, and factual correctness.  
- Uses moderation filters to prevent unsafe responses.  

---

##  Future Work
- 🔹 Fine-tune models on curated sex-education datasets.  
- 🔹 Integrate real-time fact-checking API.  
- 🔹 Develop a web-based chatbot interface.  
- 🔹 Add multilingual support for accessibility.  

---

## License
This project is released under the MIT License — you’re free to use, modify, and distribute it responsibly.
See the LICENSE file for details.

### Author: Sanah Shrivastav

## Acknowledgments
OpenAI, Hugging Face, and PyTorch for the model frameworks
Pratisandhi Foundation's datasets promoting sexual education and inclusivity
