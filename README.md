# Smart---prompt--template
# ⚡ Smart Prompt Template Library & Tester

An interactive, AI-powered prompt engineering dashboard built inside Google Colab using Python, `ipywidgets`, and the official Google Gemini API SDK.

This project enables prompt engineers and developers to organize, variable-parse, live-test, rate, and store LLM prompt templates efficiently.

---

## 🌟 Key Features

* **Categorized Prompt Repository:** Easily structure and manage prompts by categories (Coding, Marketing, Writing, Productivity).
* **Dynamic Variable Parser:** Automatically detects `{placeholder}` variables in prompt templates and generates live UI input fields for them.
* **Live Gemini API Execution:** Evaluates prompts in real-time using `gemini-2.5-flash`.
* **Rating & Storage System:** Rate prompt outputs on a scale from 1 to 5 stars and automatically persist ratings and updates to a `prompt_library.csv` file.
* **Secure Environment:** Built using Google Colab Secrets to safely handle API keys without hardcoding secrets in public code repositories.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **AI Model:** Google Gemini API (`google-genai` SDK)
* **UI/UX:** `ipywidgets`, `IPython.display`
* **Data Management:** `pandas`
* **Environment:** Google Colab

---

## 🚀 Getting Started

### 1. Google Colab Setup
1. Open the notebook in **Google Colab**.
2. Get a free Gemini API Key from [Google AI Studio](https://aistudio.google.com).
3. In Colab, click the **Secrets** (🔑) tab on the left panel.
4. Add a new secret with:
   * **Name:** `GEMINI_API_KEY`
   * **Value:** *Your API Key string*
5. Toggle **Notebook access** to **ON**.

### 2. Execution
Run all code cells in sequential order. The interactive dashboard UI will launch directly within the notebook output cell.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
