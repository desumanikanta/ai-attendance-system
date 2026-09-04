# 🤖 AI Attendance System

An AI-powered attendance management system built with **Python, Streamlit, Face Recognition, Voice Recognition, and Supabase**.

The application helps teachers manage subjects and students while automating attendance using face and voice recognition.

## 🚀 Features

- 👨‍🏫 Teacher login and dashboard
- 👨‍🎓 Student login and dashboard
- 📚 Subject creation and management
- 🔑 Student enrollment using subject codes
- 📸 Face recognition-based attendance
- 🎙️ Voice recognition-based attendance
- 📊 Attendance records
- ☁️ Supabase database integration
- 🖥️ Interactive Streamlit interface

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Application development |
| Streamlit | Web application framework |
| OpenCV | Image processing |
| Face Recognition | Face identification |
| Voice Processing | Voice identification |
| Supabase | Backend and database |
| PostgreSQL | Data storage |
| NumPy | Numerical computation |

## 🧠 System Workflow

```text
                AI Attendance System
                         │
             ┌───────────┴───────────┐
             │                       │
          Teacher                  Student
             │                       │
      Create Subject          Enroll in Subject
             │                       │
             └───────────┬───────────┘
                         │
                    Attendance
                         │
              ┌──────────┴──────────┐
              │                     │
        Face Recognition      Voice Recognition
              │                     │
              └──────────┬──────────┘
                         │
                    Supabase
                         │
                  Attendance Logs
```

## 📂 Project Structure

```text
ai-attendance-system/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── src/
    ├── components/
    ├── database/
    ├── pipelines/
    ├── screens/
    └── ui/
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/desumanikanta/ai-attendance-system.git
cd ai-attendance-system
```

### 2. Create a virtual environment

Python **3.11** is recommended.

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

## 🔐 Supabase Configuration

This project uses **Supabase** as the backend database.

Create:

```text
.streamlit/secrets.toml
```

Add your own Supabase credentials:

```toml
SUPABASE_URL = "YOUR_SUPABASE_URL"
SUPABASE_KEY = "YOUR_SUPABASE_ANON_KEY"
```

> ⚠️ Never upload `secrets.toml` to GitHub.

The file is excluded through `.gitignore`.

## 🗄️ Database Structure

The application uses the following tables:

```text
teachers
students
subjects
subject_students
attendance_logs
```

## ▶️ Run the Application

After completing the configuration:

```bash
streamlit run app.py
```

The application will open in your browser.

## 📸 Screenshots

### Home Page

_Add screenshot here_

### Teacher Dashboard

_Add screenshot here_

### Student Dashboard

_Add screenshot here_

### Face Recognition Attendance

_Add screenshot here_

### Voice Recognition Attendance

_Add screenshot here_

## 🔮 Future Improvements

- 📊 Advanced attendance analytics
- 📥 Export attendance reports to Excel/PDF
- 📧 Attendance notifications
- 🔐 Secure role-based authentication
- 🛡️ Supabase Row Level Security
- 📱 Mobile-friendly interface
- ☁️ Cloud deployment
- ⚡ Improved recognition accuracy

## 🎯 Project Objective

The objective of this project is to automate the traditional attendance process using **AI-based face and voice recognition**, reducing manual effort and providing a centralized attendance management system.

## 👨‍💻 Author

**Manikanta Naveen Kumar**

Python | SQL | AI/ML | Data Analytics | Power BI

GitHub: https://github.com/desumanikanta

## 📄 License

This project is developed for educational and portfolio purposes.
