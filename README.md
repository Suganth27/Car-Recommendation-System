# 🚗 AI-Powered Car Recommendation System

An intelligent car recommendation system that understands **natural language user queries** and recommends suitable cars using a **hybrid AI approach** combining traditional machine learning, semantic embeddings, and large language models.

---

## 📌 Project Overview

Choosing the right car is challenging due to the vast number of available options and complex user preferences. Most existing platforms rely on rigid filters that fail to capture user intent expressed in natural language.

This project solves that problem by allowing users to search for cars using **free-text queries**, such as:
- “Affordable sports car with good performance”
- “Electric SUV for family use”
- “Luxury car with high horsepower”

The system interprets user intent and returns **ranked, relevant car recommendations** through a modern, interactive web interface.

---

## 🎯 Objectives

- Enable natural language–based car search
- Understand semantic user intent
- Recommend and rank cars using similarity scores
- Provide a clean, modern, dark-themed web UI
- Demonstrate a real-world AI recommendation pipeline

---

## 🧠 AI Techniques Used

This project uses a **hybrid recommendation approach**:

- **TF-IDF Vectorization** – keyword-based similarity
- **Sentence Transformers (all-MiniLM-L6-v2)** – semantic similarity
- **Cosine Similarity** – ranking recommendations
- **Flan-T5 (LLM)** – explanation and interpretability
- **Gradio** – interactive web-based UI

---

## 🏗️ System Architecture (High-Level)

1. User enters a natural language query  
2. Query is converted into vector representations  
3. Similarity is computed against car descriptions  
4. Scores are combined and ranked  
5. Results are displayed via a web interface  

---

## 📊 Dataset

The dataset is a structured CSV file containing:
- Company name
- Car name
- Price
- Fuel type
- Engine specifications
- Horsepower
- Seating capacity
- Speed
- Description text
- (Optional) Image URLs

> Recommendation quality depends on dataset completeness and accuracy.

---

## 🧪 Evaluation Method

- **Qualitative evaluation** (no labeled ground truth)
- Manual inspection of:
  - Relevance of recommendations
  - Semantic alignment with user intent
  - Consistency across similar queries

---

## 🌐 Web Interface

- Built using **Gradio**
- Dark-themed, modern UI
- Natural language input
- Ranked recommendations with similarity scores
- Optional display of car images

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- Scikit-learn  
- Sentence-Transformers  
- Hugging Face Transformers  
- Flan-T5  
- Gradio  
- PyTorch  
- Jupyter Notebook  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ai-car-recommendation-system.git
cd ai-car-recommendation-system
