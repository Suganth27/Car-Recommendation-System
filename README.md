#  Car Recommendation System

An intelligent car recommendation system that understands **natural language user queries** and recommends suitable cars using a **hybrid AI approach** combining traditional machine learning, semantic embeddings and large language models.

---

## 📌 Project Overview

Choosing the right car is challenging due to the vast number of available options and complex user preferences. Most existing platforms rely on rigid filters that fail to capture user intent expressed in natural language.

This project solves that problem by allowing users to search for cars using **free text queries**, such as:
- “Affordable sports car with good performance”.
- “Electric SUV for family use”.
- “Luxury car with high horsepower”.

The system interprets user intent and returns **ranked, relevant car recommendations** through a modern, interactive web interface.

---

## 🎯 Objectives

- Enable natural language based car search.
- Understand semantic user intent.
- Recommend and rank cars using similarity scores.
- Provide a clean, modern, dark themed web UI.
- Demonstrate a real world AI recommendation pipeline.

---

## 🧠 AI Techniques Used

This project uses a **hybrid recommendation approach**:

- **TF-IDF Vectorization** – keyword based similarity.
- **Sentence Transformers (all-MiniLM-L6-v2)**  semantic similarity.
- **Cosine Similarity** – ranking recommendations.
- **Flan-T5 (LLM)** – explanation and interpretability.
- **Gradio** – interactive web-based UI

---

## 🏗️ System Architecture (High-Level)

1. User enters a natural language query.
2. Query is converted into vector representations.
3. Similarity is computed against car descriptions. 
4. Scores are combined and ranked.
5. Results are displayed via a web interface.

---

## 📊 Dataset

The dataset is a structured CSV file containing:

| Column Name        | Description                                   |
|--------------------|-----------------------------------------------|
| Company Name       | Manufacturer of the car                       |
| Car Name           | Model name of the car                         |
| Price              | Price of the car                              |
| Fuel Type          | Type of fuel used (Petrol/Diesel/Electric)    |
| Engine Specs       | Engine configuration and displacement details |
| Horsepower         | Engine power output                           |
| Seating Capacity   | Number of passengers supported                |
| Speed              | Maximum speed of the car                      |
| Description Text   | Additional descriptive information about car  |

### Sample Record

| Company Name | Car Name | Price  | Fuel Type | Engine Specs | Horsepower | Seating Capacity | Speed   | Description Text |
|--------------|----------|--------|-----------|--------------|------------|------------------|---------|------------------|
| Toyota       | Corolla  | $16.6k | Petrol    | 1798cc I4    | 138 HP     | 5                | 180km/h | Reliable sedan   |

> Recommendation quality depends on dataset completeness and accuracy.

---

## 🧪 Evaluation Method

- **Qualitative evaluation** (no labeled ground truth)
- Manual inspection of:
  - Relevance of recommendations.
  - Semantic alignment with user intent.
  - Consistency across similar queries.

---

## 🌐 Web Interface

- Built using **Gradio**.
- Dark-themed, modern UI.
- Natural language input.
- Ranked recommendations with similarity scores.
- [![Launch Screen](https://raw.githubusercontent.com/Suganth27/Car-Recommendation-System/main/Web%20Interface/Web%20Interface%20when%20launched.png)](https://github.com/Suganth27/Car-Recommendation-System)

- [![Search Query Screen](https://raw.githubusercontent.com/Suganth27/Car-Recommendation-System/main/Web%20Interface/Web%20Interface%20when%20search%20query%20is%20initiated.png)](https://github.com/Suganth27/Car-Recommendation-System)


---

## 🛠️ Tools & Technologies

- Python [Pandas, Scikit Learn, Gradio, Pytorch] 
- Sentence Transformers  
- Hugging Face Transformers  
- Flan-T5    
- Jupyter Notebook  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Suganth27/Car-Recommendation-System.git
cd car-recommendation-system
```
### 2️⃣ Create and Activate Virtual Environment
```bash
python -m venv env
env\Scripts\activate   # Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Application
```bash
open the notebook:
jupyter notebook
```

--- 

## 📂 Project Structure
```bash
├── data/
│   └── cars.csv
├── app.py / notebook.ipynb
├── requirements.txt
├── README.md
└── assets/
    └── screenshots/
```

---

## ⚖️ Ethical Considerations
- No personal or demographic user data is collected.
- Recommendations are for informational purposes only.
- Potential dataset bias is acknowledged.
- Transparent similarity based ranking is used.

---

## 👤 Author
```bash
Suganth S
Minor in Artificial Intelligence
```
---

## 📜 License

This project is intended for academic and educational purposes only.
