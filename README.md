# 📈 Ai-Business-Data-Analyzer
# Generative AI

An AI-powered, intelligent, interactive dashboard for business in- sights using uploaded datasets built using **Streamlit**, **Java (Spring Boot)**, and **MySQL**, with integrated **Gemini AI Chatbot** support for Natural Language Queries to assist in business insights and decision-making. Features include automated sum- mary statistics, data visualizations, dynamic PDF/Excel report generation. The application allows users to upload datasets, visualize trends, generate reports, and interact with their data in a user-friendly and insightful way.

---

## 🚀 Features

- 📊 Upload CSV/Excel files for instant data analysis
- 🔍 View descriptive statistics and top data rows
- 📈 Interactive visualizations: Bar charts, Pie charts
- 📄 Auto-generate downloadable PDF and Excel reports
- 🤖 Ask Gemini: AI chatbot for natural language data queries
- 🧠 Backend powered by Java (Spring Boot) with MySQL for data storage

---

## 🛠️ Technologies Used

- **Frontend / UI**: Streamlit
- **Backend**: Java (Spring Boot)
- **Database**: MySQL
- **Data Processing**: Pandas, Matplotlib
- **AI Integration**: Google Gemini API
- **PDF Reports**: ReportLab
- **Excel Export**: XlsxWriter

---

## 📷 Screenshots

> Add screenshots here

> ![Dashboard Overview](![Screenshot 2025-06-08 195856](https://github.com/user-attachments/assets/bd3d02f6-7aa6-4772-98a9-907bd5002ec1)
)
> ![Summary Statistics](![Screenshot 2025-06-08 200649](https://github.com/user-attachments/assets/e6464023-cc66-4ae7-a2c5-1be7ad640c72)
)
> > ![Visualization](![Screenshot 2025-06-08 201657](https://github.com/user-attachments/assets/111429ad-a02d-4a38-826c-4d60d5801bbb)
)
>  ![Report Download & Gemini ChatBot](![Screenshot 2025-06-08 202657](https://github.com/user-attachments/assets/c0addd67-5df7-4bc6-b4d5-41dc7d8475ed)
)
  
---

## 📂 Project Structure

```bash
├── Ai_Business_Analysit.py       # Main Streamlit app
├── README.md
├── requirements.txt
└── screenshots/
    ├── dashboard.png
    └── ai_query.png
⚙️ Setup Instructions
🔧 Python Dependencies
bash
Copy code
pip install -r requirements.txt
▶️ Run the App
bash
Copy code
streamlit run Ai_Business_Analysit.py
Upload a .csv or .xlsx file to begin exploring your data!

🔑 Gemini API Setup
To enable AI chat support:

Generate your Gemini API Key from Google AI Studio.

Replace the placeholder in the code:

python
Copy code
genai.configure(api_key="YOUR_API_KEY")
📤 Export Features
📄 PDF Report: Auto-generated summary report of your dataset

📥 Excel File: Export the processed dataset to .xlsx

✨ Demo Prompt Examples
"Which product has the highest sales?"

"Show the top 3 regions by revenue."

"Give a summary of customer count by month."

👨‍💻 Author
Logeshwaran P

📧 masterlogesh18@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/logeshwaran-p-18mas01ter2005/

🧠 GitHub: https://github.com/MasterLogesh

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

⭐ If you like this project, consider giving it a star!

yaml
Copy code

---

### 📌 Next Step:
- Add `requirements.txt` using:
  ```bash
  pip freeze > requirements.txt
