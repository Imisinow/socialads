# 🧲 SocialAds - Django Social Network for Ads & Earnings

**SocialAds** is a Django-powered social media platform where users earn money by **posting, liking, and sharing ads**. Admins can approve withdrawal requests and manage everything from a custom dashboard.

![screenshot](https://via.placeholder.com/1000x400.png?text=SocialAds+Demo)

---

## 🔑 Features

- 👥 User registration & login
- 📸 Post ads with media (Dropbox storage)
- 👍 Like & 🔄 Share ads to earn
- 💰 Track user earnings
- 🧾 Request withdrawals (Paystack manual processing)
- 🛠️ Admin dashboard with transaction controls

---

## 🚀 Live Demo

🌐 Coming Soon (hosted on PythonAnywhere)  
📧 Admin Login: `admin@example.com` / `adminpassword`  
👤 Test User: `test@example.com` / `testuser123`

---

## ⚙️ Tech Stack

- Django (Python)
- MySQL
- Dropbox API (media storage)
- Paystack (manual withdrawal)
- PythonAnywhere (hosting)
- Bootstrap (frontend)

---

## 📦 Setup Instructions

```bash
git clone https://github.com/yourusername/socialads.git
cd socialads
pip install -r requirements.txt

# Set up .env or edit settings.py directly for:
# - MySQL DB
# - Dropbox token
# - Paystack Secret Key

python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
