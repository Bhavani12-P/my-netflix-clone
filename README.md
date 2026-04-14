# 🎬 Microservices-based Content Streaming & AI Recommendation Platform

A high-performance Netflix clone built with a decoupled architecture. This project demonstrates the integration of **Java (Spring Boot)** for business logic, **Python (FastAPI)** for machine learning, and **React** for a seamless user experience.

## 🏗️ System Architecture
The application is designed using a **Microservices Architecture** to ensure scalability and fault tolerance:

1.  **Frontend (React):** A responsive UI utilizing Hooks and Axios for real-time data fetching.
2.  **User Service (Java/Spring Boot):** Manages user authentication (JWT), SQL database interactions, and subscription logic.
3.  **AI Engine (Python/FastAPI):** A dedicated service for content recommendation using Scikit-Learn.
4.  **Database (PostgreSQL):** Relational schema for storing movie metadata and user profiles.

## 🧠 Smart Features & AI Logic
* **Content-Based Filtering:** The Python service calculates **Cosine Similarity** between movie vectors (genres, descriptions) to suggest relevant content.
* **Real-time Streaming UI:** Implemented a custom video player interface with dynamic category rows.
* **Global State Management:** Managed user sessions and playback states using React Context API.

## 🛠️ Tech Stack
* **Frontend:** React.js, Tailwind CSS, Axios
* **Backend:** Java 17, Spring Boot, Spring Security, Hibernate
* **AI/ML:** Python 3.x, FastAPI, Pandas, Scikit-Learn
* **DevOps:** Git, Docker, GitHub Actions

## 🚦 Getting Started
1. **Clone the Project:** `git clone https://github.com/Bhavani12-P/my-netflix-clone.git`
2. **Setup AI Service:** `cd backend-ai && pip install -r requirements.txt && uvicorn main:app`
3. **Setup Java Backend:** `cd backend-java && mvn spring-boot:run`
4. **Start Frontend:** `cd frontend && npm install && npm start`

---
**Contact:** Bhavani Chandrika | CSE-AI Graduate
