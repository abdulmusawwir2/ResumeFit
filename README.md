# 📝 ResumeFit - ATS Resume Matching App

## 🚀 Overview
ResumeFit is an AI-powered tool that helps job seekers analyze their resumes against job descriptions. It provides a **match percentage, highlights strengths & weaknesses, and suggests improvements** to optimize resumes for ATS (Applicant Tracking Systems).

## 🎯 Features
✅ Upload resume (PDF format)  
✅ Compare with job description  
✅ Get a **match percentage** score  
✅ Identify missing keywords  
✅ Receive AI-powered resume improvement suggestions  

## 🏗️ Tech Stack
- **Python** (Backend)
- **Streamlit** (Frontend)
- **Google Gemini API (gemini-1.5-flash)** (AI Analysis)
- **pdf2image & PIL** (PDF processing)
- **dotenv** (Environment variables management)

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/resumefit.git
cd resumefit
```

### 2️⃣ Create a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables
Create a **.env** file in the root directory and add:
```sh
GOOGLE_API_KEY=your_api_key_here
```

### 5️⃣ Run the Application
```sh
streamlit run app.py
```

## 🏃‍♂️ Usage
1️⃣ Upload your resume in PDF format.  
2️⃣ Enter the job description.  
3️⃣ Click **"Tell Me About the Resume"** to get an analysis.  
4️⃣ Click **"Percentage Match"** to see how well your resume fits the job.  

## 🚀 Live Demo
Check out the live demo here: [ResumeFit Live](https://resumefitai.streamlit.app/)

## 🚀 Future Enhancements
- Support for multiple-page resumes.
- Improved AI feedback with more detailed suggestions.
- Expanded keyword analysis for better ATS optimization.

## 🤝 Contributing
Feel free to fork this repo and submit a pull request if you'd like to improve ResumeFit!  

---

Happy job hunting! 🚀

