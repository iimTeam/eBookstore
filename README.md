# eBookStore: Django Ecommerce Bookstore Project

An easy-to-use e-commerce platform with a modern user interface, PayPal and card support, and login/signup capabilities, developed with Django. 
This is an excellent beginning project for learning how to use Django to create scalable web applications.

## 🔗 Project Link

**GitHub Repo:**  
[https://github.com/iimTeam/eBookstore] (https://github.com/iimTeam/eBookstore)

---

# Whom is this intended?

This is for you.. if you're a total **newbie** but are keen to use Django and clone an existing project on your machine. You will be up and running in no time if you follow the instructions below. 🔥

---

## 🛠️ Tools You Need

| Tool      | Download Link                          | Purpose                          |
|-----------|----------------------------------------|----------------------------------|
| Python    | https://www.python.org/downloads/      | Runs Django                      |
| Git       | https://git-scm.com/downloads          | Clones project                   |
| VS Code   | https://code.visualstudio.com/         | Code editor                      |
| Chrome    | https://www.google.com/chrome/         | Browser to test project          |

---

## 🚀 Step-by-Step Setup (DIY Friendly)

### 1️⃣ Clone the Project

```bash
git clone https://github.com/iimTeam/eBookstore
cd ebookstore
```

---

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

- On **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- On **Mac/Linux**:
  ```bash
  source venv/bin/activate
  ```

---

### 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Set Up the Database

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 5️⃣ Create a Superuser (for admin panel)

```bash
python manage.py createsuperuser
```

Follow prompts for username, email, and password.

---

### 6️⃣ Run the Server

```bash
python manage.py runserver
```

Visit your site: [http://127.0.0.1:8000](http://127.0.0.1:8000)  
Admin panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## PayPal Sandbox Integration

1. Go to: [https://developer.paypal.com/](https://developer.paypal.com/)
2. Create a sandbox account + app
3. Add your credentials (`client_id`, `secret`) into your Django settings or `.env` file.

---

## 🐞 Common Issues & Fixes

| Problem                            | Solution                                |
|------------------------------------|-----------------------------------------|
| ModuleNotFoundError                | Run pip install <missing-package>       |
| Virtualenv not activating          | Use admin/PowerShell or check your path |
| Port already in use                | Use python manage.py runserver 8080     |

---

## 🙋 Need Help?

Raise a GitHub issue here:  
https://github.com/iimTeam/eBookstore/issues] (https://github.com/iimTeam/eBookstore/issues)

---

## ✨ Built With

- Django
- HTML / CSS / JS
- Bootstrap
- PayPal SDK (Optional if integration is done)

---
## Open-Source Project for Students
---

## 📜 License

This project is licensed under the MIT License — use it, remix it, launch your own!
