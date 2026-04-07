# 🚀 AI Recruitment Mail Parser

An intelligent system that **fetches emails, detects spam, extracts resumes, and analyzes candidate data using Machine Learning**.

---

## 🔥 Features

* 📧 Fetch emails from Gmail using IMAP
* 🤖 Spam Detection using ML (Naive Bayes)
* 📄 Resume Parsing (PDF & DOCX)
* 🧠 Extract:

  * Name
  * Email
  * Phone
  * Skills
  * Education
  * Job Role
* 🗂️ Store data in MySQL (no duplicates)
* 🌐 REST API using Flask
* ⚡ Real-time processing

---

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Machine Learning:** Scikit-learn
* **Database:** MySQL
* **Libraries:**

  * OpenCV (optional)
  * PyPDF2
  * python-docx
  * imaplib

---

## 📦 Installation

```bash
git clone https://github.com/your-username/ai-recruitment-mail-parser.git
cd ai-recruitment-mail-parser
pip install -r requirements.txt
```

---

## ▶️ Run Project

```bash
python app.py
```

Server runs on:

```
http://127.0.0.1:5000
```

---

## 📡 API Endpoints

### 🔹 Fetch Emails

```
GET /get_emails
```

### 🔹 Get Stored Emails

```
GET /get_saved_emails
```

### 🔹 Get Resumes

```
GET /get_resumes
```

### 🔹 Dashboard Stats

```
GET /stats
```

---

## 📊 Sample Output

```json
{
  "sender": "abc@gmail.com",
  "subject": "Job Application",
  "prediction": "Not Spam"
}
```

---
<img width="908" height="1741" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/62487e3e-9cb7-4521-9748-77e2adc87aa2" />


## 🎯 Use Cases

* HR automation
* Resume screening
* Spam filtering
* Recruitment analytics

---

## 🔒 Security Note

⚠️ Use Gmail App Password (not your real password)

---

## 👨‍💻 Author

Shantanu Shete
Data Scientist | ML Engineer

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
graph TD
