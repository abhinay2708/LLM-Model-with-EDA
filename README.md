# 📊 LLM-Powered Exploratory Data Analysis (EDA) Tool

An interactive Python + Gradio application for automated Exploratory Data Analysis, integrated with **Mistral-7B (via Ollama)** to generate AI-powered insights from datasets.

---

## 🚀 Features
- **CSV Upload** – Load any dataset in `.csv` format.
- **Automatic Data Cleaning**:
  - Median imputation for numeric columns.
  - Mode imputation for categorical columns.
- **Statistical Summary** – Generates `describe()` output with all columns.
- **Missing Value Report** – Shows null counts per column.
- **Data Visualizations**:
  - Distribution plots for numeric columns.
  - Correlation heatmap for numeric features.
- **AI Insights**:
  - Uses **Ollama** and **Mistral-7B** LLM to explain dataset patterns in plain English.
- **Interactive UI** – Powered by **Gradio**.

---

## 🛠 Tech Stack
- **Python**: Pandas, Seaborn, Matplotlib
- **Gradio** – For user interface
- **Ollama** – Local LLM API
- **Mistral-7B** – AI model for insights

---

## 📂 Project Structure
