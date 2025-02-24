# 🌱 NLP-Driven Sustainability Analysis in Hospitality  

## 📌 Project Overview  
This project explores **sustainability concerns in hospitality industry reviews** using **Natural Language Processing (NLP)** techniques. By analyzing customer feedback from **Booking.com & Expedia**, we uncover sustainability trends using:  
- **BERT embeddings & Cosine Similarity** for text comparison.  
- **AI-generated reviews** as a baseline for sustainability themes.  
- **Data visualization** to identify trends & customer concerns.  

## 🚀 Features  
- ✅ **Used BERT embeddings** to measure review similarity with AI-generated sustainability reviews.  
- ✅ **Extracted key sustainability insights** from real customer reviews.  
- ✅ **Created visualizations** to highlight trends in sustainability levels, review sentiment, and similarity scores.  
- ✅ **Explored geographic differences** in sustainability concerns.  

## 📂 Repository Structure  
NLP-Sustainability-Analysis-Hospitality/   
│── README.md     # Project Overview  
│── LICENSE       # BSD 3-Clause License  
│── .gitignore    # Ignore unnecessary files  
│  
├── data/  
│ ├── V1BookingHotel_with_AvgSimilarity_Scores.xlsx   # Dataset with similarity scores  
│ ├── reviewsAIV1.xlsx                                # AI-generated reviews dataset  
│ ├── V1BookingHotel_-_TH_SG.xlsx                     # Original hotel review dataset  
│  
├── notebooks/  
│ ├── Bert_Cosine_Similarity.ipynb     # NLP model & similarity calculation  
│ ├── Hotel_Data_Visualization.ipynb   # Data visualization & insights  
│  
├── reports/  
│ ├── Sustainability_Analysis_Report.pdf   # Final research report  


## 💾 Dataset  
The dataset consists of **real customer reviews** and **AI-generated sustainability-focused reviews**, processed for NLP analysis.  

**Data Sources:**  
- **Booking.com & Expedia hotel reviews**  
- **AI-generated sustainability reviews** (GPT, Claude, Gemini)  

## 📊 Key Insights  
- **Sustainability concerns impact hotel ratings.**  
- **Certain keywords (eco-friendly, green, sustainable) correlate with high similarity scores.**  
- **Travelers from different regions express varying sustainability expectations.**  

## 🛠️ How to Run  
### 1️⃣ **Install Dependencies:**  
```bash
pip install torch transformers pandas numpy matplotlib seaborn wordcloud
```

### 2️⃣ Run NLP Analysis (BERT Cosine Similarity):
- Open `notebooks/Bert_Cosine_Similarity.ipynb` in Jupyter Notebook.
- Run all cells to compute similarity scores between hotel reviews & AI-generated sustainability reviews.

### 3️⃣ Run Data Visualization Notebook:
- Open `notebooks/Hotel_Data_Visualization.ipynb` to explore trends & insights.

## 🔍 Future Enhancements
- Enhance AI-generated sustainability review dataset for better benchmarking.
- Integrate topic modeling (LDA) to extract dominant sustainability themes.
- Develop a sustainability rating prediction model using ML techniques.


