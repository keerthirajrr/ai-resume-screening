# 📄 AI Resume Screening & Ranking System  

This project is a **Streamlit-based AI Resume Screening & Ranking System** that ranks resumes based on a given job description using **TF-IDF (Term Frequency-Inverse Document Frequency)** and **Cosine Similarity**.  

## 🚀 Features  
- Extracts text from PDF resumes using `PyPDF2`.  
- Uses `TfidfVectorizer` to convert text into numerical vectors.  
- Computes **cosine similarity** between job descriptions and resumes.  
- Displays resumes ranked by relevance.  

## 📂 Project Structure  
ai-resume-screening/ │-- app.py # Main Streamlit app
│-- requirements.txt # Dependencies
│-- README.md # Project documentation


## 🛠 Technologies Used  
- **Python**  
- **Streamlit**  
- **Scikit-learn** (TF-IDF, Cosine Similarity)  
- **PyPDF2** (Extract text from PDFs)  

## 🚀 Installation & Running the App  

### **1️⃣ Clone the Repository**  

git clone https://github.com/keerthirajrr/ai-resume-screening.git  
cd ai-resume-screening

2️⃣ Install Dependencies
pip install -r requirements.txt  

3️⃣ Run the Streamlit App
streamlit run app.py

🔥 Future Enhancements
Improve PDF text extraction with pdfplumber.
Add a visual ranking chart.
Enhance keyword extraction with NLP techniques.
