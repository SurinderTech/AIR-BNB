# Airbnb-Inspired Full-Stack Web Application 🏡✨

<p align="center">
  <b>👀 Visitor Count</b>
  <br>
  <a href="Rakhisan">
  <img src="https://profile-counter.glitch.me/Airbnb--Project/count.svg" />
  </a>
</p>

---

## 🧭 Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Setup & Installation](#setup--installation)
- [Environment Variables](#environment-variables)
- [Run the Project](#run-the-project)
- [Project Structure](#project-structure)
- [Challenges](#challenges)
- [Contributing](#contributing)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

---

### 📝 Overview
A scalable, dynamic, and feature-rich full-stack web app inspired by **Airbnb**, built using **MongoDB, Express.js, Node.js, and EJS**, supporting email & social authentication with interactive maps and cloud media storage.

---

## 🧰 Tech Stack
**Backend:** MongoDB, Express.js, Node.js, Mongoose  
**Auth:** Passport.js (Local, Google OAuth 2.0, Facebook) + session storage  
**Media:** Cloudinary + Multer  
**Maps:** Mapbox  
**Validation:** Joi  
**Frontend:** EJS + Bootstrap/CSS  
**Config:** dotenv, cookie-parser, connect-flash, connect-mongo  

---

## ⚡ Features
- Secure user authentication (Email, Google, Facebook)
- Listings with full **CRUD**
- Review & rating system
- Password hashing + encryption
- Map-based location visualization
- Session persistence with MongoDB
- Cloud image storage
- Flash notifications
- Profile + account management

---

## 🛠 Setup & Installation

1. **Clone the repository**

```
git clone <project_repo_link>
```
```
cd <project_folder_name>
```
<h1>Install dependencies</h1>


bash
Copy code
```
npm install
```
Setup MongoDB

Make sure MongoDB is running locally or use MongoDB Atlas.

Start the development server

bash
Copy code
```
npm start
```
# or
nodemon app.js
### 🔐 Environment Variables

Create a .env file in the root directory and add:


PORT=8080<br>
MONGO_URI=your_mongodb_connection_string


CLOUDINARY_CLOUD_NAME=your_cloudinary_name<br>


CLOUDINARY_API_KEY=your_api_key


CLOUDINARY_API_SECRET=your_api_secret


MAPBOX_TOKEN=your_mapbox_token


GOOGLE_CLIENT_ID=your_google_client_id


GOOGLE_CLIENT_SECRET=your_google_client_secret


FACEBOOK_CLIENT_ID=your_facebook_client_id


FACEBOOK_CLIENT_SECRET=your_facebook_client_secret


SESSION_SECRET=your_session_secret


▶ Run the Project
```
npm run dev  
```
### development mode
```
npm start      
```

Then open in browser:

arduino
Copy code
http://localhost:8080
📁 Project Structure (Example)
bash
Copy code
Airbnb-Project/
│── models/           # MongoDB schemas
│── views/            # EJS frontend pages
│── public/           # CSS, JS, images
│── routes/           # App routes
│── controllers/      # Core business logic
│── app.js            # Main server file
│── .env              # Config file
│── package.json
🚧 Challenges
Handled data scalability, optimized backend architecture, and resolved complex data relationships using Mongoose & session storage, ensuring smooth social authentication and fast map rendering.

🤝 Contributing
Contributions are welcome!

Fork the project

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m "Add feature")

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

👨‍💻 Author
Surinder Kumar
📧 Email: surinderkumar3182@gmail.com
🔗 LinkedIn: surinder-kumar-948343321/

🙏 Acknowledgements
Special thanks to Shradha Khapra didi & Aman Dhattarwal bhaiya from #ApnaCollege for mentorship and guidance that helped shape this project.

⭐ If you like this project, consider giving it a Star!
Thanks for visiting! 😊
Happy Coding & Building 🚀♟️

yaml
Copy code
