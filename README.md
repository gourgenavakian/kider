# 📌 MERN Stack Kindergarten Management App

## 📖  Overview
This is a full-stack web application built with the MERN (MongoDB, Express, React, Node.js) stack. It provides an online platform for parents to register their children for kindergarten classes, make appointments, and leave feedback.

## 🛠 Features
- **User Authentication** (Register/Login)
- **Appointment Booking** (Only for logged-in users)
- **Teacher Popularity Ranking** (Based on student registrations)
- **Feedback System** (Users can leave comments)
- **MongoDB Database** (Stores all user and appointment data)

## 🛠  Technologies Used
- **Frontend:** React.js (Redux)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Styling:** HTML5, CSS3 (SASS/SCSS)
- **Authentication:** JWT (JSON Web Tokens)
- **State Management:** Redux-Saga

## 📂 Project Structure
```
📦 project-root  
 ├── 📂 front (React Frontend)  
 │   ├── 📂 src  
 │   │   ├── 📂 components  
 │   │   ├── 📂 pages  
 │   │   ├── 📂 store  
 │   │   ├── App.js  
 │   │   ├── index.js  
 │   ├── package.json  
 │   ├── Dockerfile  
 ├── 📂 server (Node.js Backend)  
 │   ├── 📂 controllers  
 │   ├── 📂 models  
 │   ├── 📂 routes  
 │   ├── app.js  
 │   ├── package.json  
 │   ├── Dockerfile  
 ├── docker-compose.yml  
 ├── README.md  
```

### 1️⃣ Clone the Repository
```bash
git clone git@github.com:gourgenavakian/kider.git
cd kider.git
```

### 2️⃣ Run with Docker
```bash
docker-compose up --build
```

### 3️⃣ Run Manually
#### Install Dependencies
```bash
cd front && npm install  # Frontend
cd ../server && npm install  # Backend
```

#### Start Backend
```bash
cd server
npm start
```

#### Start Frontend
```bash
cd front
npm start
```

## 👨‍💻 Author
**Gourgen Avakian** - [GitHub](https://github.com/gourgenavakian) | [LinkedIn](https://www.linkedin.com/in/gourgen-avakian/)

## 📄  License
This project is licensed under the MIT License.

