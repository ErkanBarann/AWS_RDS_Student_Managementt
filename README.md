# 🎓 AWS RDS Student Management

A simple **Flask web application** deployed on AWS, designed for managing student records using an **AWS RDS PostgreSQL** database.

---

## 🚀 Features

- View all students
- Add new student
- Update existing student
- Delete student record
- Fully integrated with AWS RDS PostgreSQL

---

## 🛠 Tech Stack

- **Flask** (Python Web Framework)
- **PostgreSQL** hosted on **AWS RDS**
- **HTML + Jinja2** templates (for UI)
- **Bootstrap** (optional styling)
- Hosted on **EC2** (optional)

---

## 📁 Project Structure

```
AWS_RDS_Student_Managementt/
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
└── templates/
    ├── index.html       # List + add students
    └── update.html      # Edit student form
```

---

## ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/ErkanBarann/AWS_RDS_Student_Managementt.git
   cd AWS_RDS_Student_Managementt
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Update your AWS RDS credentials inside `app.py`:
   ```python
   DB_CONFIG = {
       'dbname': 'your-db',
       'user': 'your-user',
       'password': 'your-pass',
       'host': 'your-rds-endpoint',
       'port': '5432'
   }
   ```

4. Run the app:
   ```bash
   python app.py
   ```

5. Access it on: `http://localhost:5000`

---

## 🧪 Example Use Cases

- University or school student management
- Backend demo for RDS-connected apps
- Learning Flask + AWS RDS integration

---

## ✅ To Do (Optional)

- Add form validation
- Add search/filter functionality
- Deploy with NGINX + Gunicorn on EC2

---

## 📸 Screenshot

> Add a screenshot here showing the student list table and add form (optional but useful)

---

## 📄 License

MIT — free to use and modify.