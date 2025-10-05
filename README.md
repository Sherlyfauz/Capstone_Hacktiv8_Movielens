# Capstone_Hacktiv8_Movielens
Capstone Project Hacktiv8 – Analisis dataset MovieLens untuk klasifikasi rating film (low/mid/high) dan summarization insight menggunakan IBM Granite Models.

# Capstone Project Hacktiv8: MovieLens Rating Classification & Summarization

## Project Overview
Tujuan project ini adalah menganalisis dataset **MovieLens** untuk memahami pola rating film, melakukan klasifikasi rating (low, mid, high), serta menghasilkan insight yang dapat digunakan untuk rekomendasi film.  
Selain itu, project ini juga menggunakan **IBM Granite Models** untuk membantu proses klasifikasi berbasis AI serta membuat ringkasan (summarization) dari review pengguna.

## Dataset
- Nama: MovieLens Latest Small Dataset
- Link: http://files.grouplens.org/datasets/movielens/ml-latest-small.zip
- Jumlah data: ±100,000 rating dari 600 pengguna terhadap 9,000 film.

## Methods
1. **EDA**: Eksplorasi distribusi rating, genre, dan perilaku user.  
2. **Preprocessing**: One-hot encoding genre, pembuatan label `rating_bucket`.  
3. **Modeling**:  
   - Baseline model: RandomForestClassifier  
   - AI model: IBM Granite untuk classification & summarization.  
4. **Evaluation**: Confusion Matrix, Classification Report.  
5. **Insight & Recommendations**: Rekomendasi genre, pola rating user.  

## AI Support
IBM Granite digunakan untuk:  
- **Classification assistance**: membantu klasifikasi review/rating.  
- **Summarization**: merangkum alasan utama film disukai/tidak disukai.  
- **Explainability**: memberikan penjelasan berbasis natural language terhadap hasil prediksi.

## Results
- Baseline model mencapai akurasi ±75% pada klasifikasi rating.  
- Insight: Genre *Animation* dan *Adventure* cenderung mendapat rating lebih tinggi.  
- Granite summarization: “Users appreciate strong visuals and unique storytelling, while criticism often relates to weak plots.”

## How to Run
1. Clone repo:  
   ```bash
   git clone <repo-url>
