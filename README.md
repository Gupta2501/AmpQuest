

# ⚡ AmpQuest — Find. Charge. Go.

Welcome to **AmpQuest**, the smarter way to find EV chargers on the go!  
AmpQuest empowers electric vehicle drivers to easily discover nearby available chargers, receive real-time notifications, and plan smoother, greener journeys.

---

## 🚀 Key Features
- **Live Charger Discovery**: Search for available EV chargers near your location.
- **Real-time Alerts**: Get notified when a charger becomes free or when your vehicle battery reaches a set percentage.
- **Smart Reservations**: Reserve a charging slot in advance (future enhancement-ready).
- **Seamless Authentication**: Secure JWT-based user login and access control.
- **Admin Dashboard**: Manage charger stations and monitor platform activity.

---

## 🛠️ Tech Stack
- **Backend**: Java 17, Spring Boot, Spring Security, JPA
- **Frontend**: React.js (Coming soon / Connects externally)
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Containerization**: Docker & Docker Compose
- **API Documentation**: Swagger / OpenAPI 3.0

---

## 🏗️ System Architecture
```
[ React App ] ---> [ Spring Boot API ] ---> [ PostgreSQL DB ]
                     |                     |
                  [ Docker Containers for each Service ]
```
Everything is containerized for quick setup and deployment.

---

## ⚙️ Getting Started

### 1. Prerequisites
- Java 17+
- Docker and Docker Compose
- Maven
- PostgreSQL (optional, if running locally without Docker)

### 2. Clone the Repository
```bash
git clone https://github.com/Gupta2501/AmpQuest.git
cd ampquest
```

### 3. Build and Run with Docker
```bash
docker-compose up --build
```
This will spin up the backend API and PostgreSQL database automatically.

### 4. Access API
- Swagger UI: [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)

---

## 📖 API Overview
This project uses Swagger/OpenAPI to document all endpoints, including:
- User Registration & Login
- EV Charger Listings
- Reservation and Notifications
- Email Alerts

Explore the API easily through the Swagger UI once the backend is up!


## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---

## ✨ Credits
Built and enhanced with ❤️ for the EV community.

