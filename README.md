

# Social Media Feed Backend – ProDev BE

A real-world backend case study that prepares engineers to build **scalable and interactive systems** like modern social media platforms.

---

## 📌 Overview

This project focuses on developing a backend service to manage posts and user interactions for a social media feed.
It emphasizes:

* **GraphQL API development** for flexible data fetching
* **Real-time interactions** (likes, comments, shares)
* **Scalable database design** for high-traffic applications

---

## 🎯 Project Goals

* **Post Management**: Create, fetch, and manage posts via well-structured APIs
* **Flexible Querying**: Implement GraphQL for advanced and efficient queries
* **Scalability**: Design a database schema that performs well under heavy user activity

---

## 🛠️ Technologies

* **Django** – Backend framework
* **PostgreSQL** – Relational database
* **GraphQL (Graphene)** – Flexible data queries
* **GraphQL Playground** – Interactive API testing

---

## ✨ Key Features

1. **GraphQL APIs**

   * Flexible querying of posts and interactions
   * Resolvers for creating, fetching, and managing content

2. **Interaction Management**

   * Like, comment, and share functionality
   * Tracks interactions for analytics and feedback

3. **API Testing**

   * Hosted GraphQL Playground for seamless testing

---

## 🚀 Implementation Highlights

**Git Commit Workflow**

```
feat: set up Django project with PostgreSQL  
feat: create models for posts, comments, and interactions  
feat: implement GraphQL API for querying posts and interactions  
feat: integrate and publish GraphQL Playground  
perf: optimize database queries for interactions  
docs: update README with API usage  
```

---

## 📤 Deployment

* **API & Playground**: Hosted deployment with GraphQL Playground for live testing.
* Replace this line with your actual deployment URL once it’s live.

---



## 🧑‍💻 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/social-media-feed-backend.git
   cd social-media-feed-backend
   ```
2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
3. **Run migrations**

   ```bash
   python manage.py migrate
   ```
4. **Start the development server**

   ```bash
   python manage.py runserver
   ```
5. Access GraphQL Playground at `http://localhost:8000/graphql/`

---

## 📄 License

Specify your license here (e.g., MIT, Apache 2.0).

---

**Happy coding and scaling!** 🚀

---

Would you like me to include example GraphQL queries or mutations for quick testing?
