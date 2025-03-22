# MERN Stack Kindergarten Management App

## Overview
This is a full-stack web application built with the MERN (MongoDB, Express, React, Node.js) stack. It provides an online platform for parents to register their children for kindergarten classes, make appointments, and leave feedback.

## Features
- **User Authentication** (Register/Login)
- **Appointment Booking** (Only for logged-in users)
- **Teacher Popularity Ranking** (Based on student registrations)
- **Feedback System** (Users can leave comments)
- **MongoDB Database** (Stores all user and appointment data)

## Technologies Used
- **Frontend:** React.js (Redux)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Styling:** HTML5, CSS3 (SASS/SCSS)
- **Authentication:** JWT (JSON Web Tokens)
- **State Management:** Redux-Saga

## Project Structure
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

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
   ```sh
   cd front && npm install
   cd ../server && npm install
   ```

3. Run the application:
    - Start the frontend: `cd front && npm start`
    - Start the backend: `cd server && npm run dev`

## License
This project is licensed under the MIT License.

