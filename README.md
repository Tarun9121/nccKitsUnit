Here's a complete `README.md` file that combines both your frontend and backend repos for the **KITS NCC Unit Management System**. You can use this in a new parent GitHub repo or directly on your portfolio/work sample:

---

````markdown
# KITS NCC Unit Management System

This is a full-stack web application developed to streamline the operations of the NCC (National Cadet Corps) unit at KITS College. The system allows cadets to manage their profiles, stock items, and camp registrations, while the ANO (Associate NCC Officer) can monitor cadet activities, manage inventory, and send announcements.

## 🔗 Repositories

- **Frontend** (React.js): [nccKitsUnit-frontend](https://github.com/Tarun9121/nccKitsUnit-frontend)
- **Backend** (Spring Boot): [nccKitsUnit-backend](https://github.com/Tarun9121/nccKitsUnit-backend)

## 🎯 Features

### 👨‍🎓 Cadet Features
- View assigned stocks and their return status (returned/pending/overdue).
- Register for upcoming camps.
- Receive email notifications for Regimental IDs and ANO announcements.

### 👮 ANO Features
- Accept or reject camp registrations.
- Track cadet-issued stocks and return deadlines.
- Send announcements to individual cadets or all cadets.
- View lists of cadets with pending or overdue returns.

## 🛠️ Tech Stack

### Frontend
- **React.js** – UI framework
- **React Router DOM** – Routing
- **Tailwind CSS** – Styling and responsiveness
- **Axios** – API integration

### Backend
- **Spring Boot** – REST API and business logic
- **MySQL** – Relational database
- **Spring Security** – Authentication and role-based access
- **Java Mail Sender** – Email functionality
- **Lombok & JPA** – Model and data handling

## 🧑‍🏫 Role and Contribution

This project was built by final-year students at KITS College under the guidance of **Tarun Swaroop**.  
As a **technical mentor**, Tarun provided:
- Guidance on system design and API structuring
- Support for full-stack development with React and Spring Boot
- Code reviews and debugging
- Best practices for deployment, authentication, and state management

## 🚀 How to Run

### Prerequisites
- Node.js (>=12.x)
- Java (>=17.x)
- MySQL
- Maven

### Frontend Setup
```bash
git clone https://github.com/Tarun9121/nccKitsUnit-frontend.git
cd nccKitsUnit-frontend
npm install
npm run dev
````

### Backend Setup

```bash
git clone https://github.com/Tarun9121/nccKitsUnit-backend.git
cd nccKitsUnit-backend
# Configure application.properties for DB
mvn spring-boot:run
```

## 📸 Screenshots

### Home Page - ANO Dashboard
![image](https://github.com/user-attachments/assets/21ea085a-e5f6-46dc-a944-aaf3f4dec192)


## 📬 Contact

**Tarun Swaroop**
Project Guide and Full Stack Developer
Email: [tarunswaroop199@gmail.com](mailto:tarunswaroop199@gmail.com)
GitHub: [@tarun](https://github.com/Tarun9121)
