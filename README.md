# 📰 WordPress + MySQL | 2-Tier Dockerized CMS Deployment

![Docker](https://img.shields.io/badge/docker-compose-blue)
![WordPress](https://img.shields.io/badge/wordpress-CMS-orange)
![MySQL](https://img.shields.io/badge/mysql-5.7-blue)
![License](https://img.shields.io/badge/license-MIT-brightgreen)

A simple and production-style 2-tier project that launches **WordPress** and **MySQL** using **Docker Compose**. Ideal for DevOps and Web development learning and interviews!

---

## 📌 What is This Project?

This is a **Docker-based CMS deployment** using:
- 🖥️ **WordPress** as the frontend/content management system
- 🗄️ **MySQL** as the backend database
- ⚙️ **Docker Compose** for orchestration

---

## 🧱 Project Structure

wordpress-mysql/
├── docker-compose.yml
├── .env
└── README.md


---

## 🔧 Technologies Used

| Layer       | Tech           |
|-------------|----------------|
| Frontend / CMS | WordPress   |
| Backend / DB   | MySQL 5.7   |
| Orchestration  | Docker Compose |
| Networking     | Docker Bridge Network |
| Persistence    | Docker Volumes |

---

## 🚀 How to Run

> Make sure you have Docker + Docker Compose installed on your system.

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/wordpress-mysql.git
cd wordpress-mysql

2️⃣ Create a .env File
# .env
MYSQL_ROOT_PASSWORD=rootpassword
MYSQL_DATABASE=wordpress
MYSQL_USER=wpuser
MYSQL_PASSWORD=wppassword

WORDPRESS_DB_HOST=mysql
WORDPRESS_DB_USER=wpuser
WORDPRESS_DB_PASSWORD=wppassword
WORDPRESS_DB_NAME=wordpress

3️⃣ Start the Services
docker-compose up -d
✅ Visit: http://localhost:8080

docker-compose down
docker-compose down -v

📜 License
This project is licensed under the MIT License.


