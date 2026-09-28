# 🏡 WanderLust — Full-Stack Travel & Property Booking Platform

WanderLust is a full-stack web application for discovering, creating, and managing property listings. Users can explore accommodations, view detailed property information, create their own listings, and interact with the platform through reviews and ratings.

This project helped me gain practical experience building a complete web application using **Node.js, Express.js, MongoDB, Mongoose, EJS, and RESTful routing**.

---

## 🚀 Features

- 🔐 User authentication and authorization
- 🏡 Create and manage property listings
- 🔎 Browse available listings
- 📄 View detailed property information
- ✏️ Edit existing listings
- 🗑️ Delete listings
- ⭐ Review and rating functionality
- 🖼️ Property image uploads
- ☁️ Cloud-based image storage
- 🛡️ Server-side validation
- 📱 Responsive web interface
- 🗄️ MongoDB database integration

---

## 🛠️ Tech Stack

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- RESTful APIs
- MVC Architecture

### Frontend

- EJS
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Additional Tools & Services

- Cloudinary
- Passport.js
- Express Session
- Method Override
- Joi
- Git & GitHub

---

## 🏗️ Application Architecture

The application follows an MVC-oriented architecture:

```text
                    ┌───────────────┐
                    │     User      │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │     Routes    │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Controllers  │
                    └───────┬───────┘
                            │
                    ┌───────┴───────┐
                    ▼               ▼
              ┌───────────┐   ┌───────────┐
              │  Models   │   │   Utils   │
              └─────┬─────┘   └───────────┘
                    │
                    ▼
              ┌─────────────┐
              │   MongoDB   │
              └─────────────┘
```

---

## 📁 Project Structure

```text
WanderLust/
│
├── controllers/
│
├── models/
│
├── routes/
│
├── views/
│
├── public/
│
├── utils/
│
├── init/
│
├── classroom/
│
├── app.js
├── cloudConfig.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/adityaasinghhh/wanderlust.git
```

Navigate into the project:

```bash
cd wanderlust
```

### 2. Install Dependencies

Install all required Node.js packages:

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root.

Example:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
```

> ⚠️ **Never upload your `.env` file or real credentials to GitHub.**

### 4. Start the Application

Run:

```bash
node app.js
```

For development with Nodemon:

```bash
nodemon app.js
```

The application will be available at the local address displayed in your terminal.

---

## 🗄️ Database

The application uses **MongoDB** with **Mongoose** for database management and data modeling.

The main entities include:

```text
User
 │
 ├── Listings
 │
 └── Reviews

Listing
 │
 └── Reviews
```

Mongoose schemas are used to define and validate the application's data models.

---

## 🔐 Authentication & Authorization

The application implements authentication and authorization for protected operations.

Users can:

- Register an account
- Log in and log out
- Create property listings
- Edit their own listings
- Delete their own listings
- Add reviews
- Manage their own content

Protected routes ensure that users can only perform actions they are authorized to perform.

---

## ☁️ Image Management

Property images can be uploaded and stored using **Cloudinary**.

Cloud-based image storage allows the application to manage property images without storing large image files directly on the application server.

---

## 📚 What I Learned

Through this project, I gained practical experience with:

- Full-stack JavaScript development
- Node.js backend development
- Express.js
- MongoDB and Mongoose
- MVC architecture
- RESTful routing
- Authentication and authorization
- Express middleware
- CRUD operations
- Server-side validation
- EJS templating
- Cloud-based image storage
- Git and GitHub

---

## 🚀 Future Improvements

Potential improvements include:

- 🔎 Advanced property search and filtering
- 📍 Location and map integration
- 💳 Online booking and payment processing
- 💬 Real-time user messaging
- 🤖 Personalized property recommendations
- 🧪 Automated unit and integration testing
- 🐳 Docker-based deployment
- 📊 Analytics dashboard
- 🔔 Booking and notification system
- ☁️ Production-ready cloud deployment

---

## 👨‍💻 Author

### Aditya Singh

Computer Science Engineering

Interested in:

- Full-Stack Development
- Backend Engineering
- Machine Learning
- Data Analytics

GitHub:

https://github.com/adityaasinghhh

---

## 📌 Disclaimer

This project was developed for educational and portfolio purposes.