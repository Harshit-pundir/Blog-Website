# 📝 Harshit's Blog

A fully-featured blog web application built using **Flask**, with user authentication, rich-text editing using CKEditor, admin-only post control, Gravatar integration for comments, and contact form functionality via email.

---

## 🚀 Features

- 🧑‍💻 User Registration & Login (Flask-Login + WTForms)
- ✍️ Create/Edit/Delete Blog Posts (Admin only)
- 💬 Commenting System (Authenticated users)
- 🎨 Rich Text Editor (CKEditor for blog posts & comments)
- 📩 Contact Me Form (with email sending support)
- 🧑‍🎤 Gravatar Integration (Profile images via email)
- 🎨 Bootstrap5 Styling (via Flask-Bootstrap)
- 🔐 Password Hashing (via Werkzeug)
- 🗃️ SQLite Database (via SQLAlchemy)

---


## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Flask | Web framework |
| Flask-WTF | Form handling and validation |
| Flask-Login | User session management |
| Flask-Bootstrap | Bootstrap integration |
| Flask-CKEditor | Rich-text editor |
| Flask-Gravatar | User avatars in comments |
| SQLAlchemy | ORM for database |
| SQLite | Database (you can swap with PostgreSQL/MySQL) |

---

## 🧪 Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Harshit-Pundir/Blog-Website.git
cd Blog-Website

2. Create & Activate Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
4. Set Up Environment Variables
Create a .env file in the root directory:

ini
Copy
Edit
FLASK_KEY=your_secret_key
EMAIL_KEY=your_email@gmail.com
PASSWORD_KEY=your_app_password
DB_URI=sqlite:///posts.db
⚠️ Make sure to enable "Less secure apps" or use an App Password if using Gmail.

5. Run the App
bash
Copy
Edit
python main.py
Navigate to: http://localhost:5001

🔒 Admin Access
By default, the first user to register becomes Admin (ID = 1).
Only the admin can create, edit, or delete blog posts.

📁 Project Structure
css
Copy
Edit
.
├── templates/
│   ├── header.html
│   ├── footer.html
│   ├── index.html
│   ├── post.html
│   ├── login.html
│   ├── register.html
│   ├── make-post.html
│   ├── about.html
│   └── contact.html
├── static/
│   ├── css/
│   │   └── styles.css
│   └── assets/
│       └── img/
├── forms.py
├── main.py
├── requirements.txt
├── .env
└── README.md
📬 Contact
If you have any questions or suggestions, feel free to reach out.

🧠 Future Improvements
Add pagination

Profile page for users

Search and tags functionality

Image upload support

Admin dashboard

⭐️ Show Your Support
If you like this project, please ⭐️ the repo and share it!

