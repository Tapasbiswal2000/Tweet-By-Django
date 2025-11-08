# 🐦 Tweet-By-Django  
A full-stack **micro-blogging web application** built with **Django, Python, and SQLite**, inspired by Twitter.  
Users can create, edit, and delete tweets, follow other users, and view personalized timelines — all through a clean, responsive UI.

---

## 🚀 Features
- 👤 **User Authentication** – Register, Login, and Logout with Django’s built-in authentication system.  
- 📝 **Tweet Management** – Create, read, update, and delete tweets (CRUD operations).  
- 🧵 **User Feed** – Display tweets from all users in chronological order.  
- 📸 **Media Uploads** – Add images to tweets using Django’s File and Media management.  
- 💬 **Profile Pages** – View your own posts and other users’ profiles.  
- 📱 **Responsive UI** – Built with HTML5, CSS3, and Bootstrap for mobile and desktop.  
- ⚙️ **Optimized ORM Queries** – Efficient database interaction using Django ORM.  

---

## 🧰 Tech Stack
| Layer | Tools |
|-------|-------|
| **Backend** | Django (Python) |
| **Frontend** | HTML5, CSS3, Bootstrap |
| **Database** | SQLite |
| **Version Control** | Git & GitHub |
| **IDE** | VS Code |

---

## 📦 Installation & Setup

Follow these steps to set up the project locally:

```bash
# 1️⃣ Clone this repository
git clone https://github.com/Tapasbiswal2000/Tweet-By-Django.git
cd Tweet-By-Django

# 2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On macOS/Linux

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run migrations
python manage.py makemigrations
python manage.py migrate

# 5️⃣ Start the development server
python manage.py runserver
