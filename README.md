# 🎬 Dharma Productions Movie Management System

A Python + MySQL-based backend system to manage movies produced by Dharma Productions, covering entities such as movies, producers, directors, actors, and crew members.

This system is ideal for managing movie metadata and relationships in a structured and scalable way using relational databases.

---

## ⚙️ Tech Stack

| Layer     | Technology            |
|-----------|------------------------|
| Backend   | Python 3.x             |
| Database  | MySQL                  |
| ORM       | SQLAlchemy (optional)  |
| Tools     | Flask (optional), pymysql or mysql-connector-python |

---

## 🧩 ER Diagram
![er](https://github.com/user-attachments/assets/eb357fb9-9eb2-4f8e-8971-ccb23b5569c8)



> Replace with actual relative path to the image

---

## 📦 Features

- Manage Movie Catalogs (title, genre, budget, etc.)
- Manage Producer, Director, Actor, and Crew details
- Establish many-to-many relationships for actors and crew
- Easily extendable with awards, music, and streaming data

---



## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/dharma-movie-system.git
cd dharma-movie-system



python3 -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
