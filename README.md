# EduHub V3 📚

EduHub V3 is a MERN Stack based educational platform developed for managing and sharing study materials digitally. The platform allows students to access educational resources online while administrators can upload, edit, delete, and manage study materials securely through an admin dashboard.

---

# 🚀 Features

## User Features

* User Registration
* Secure Login Authentication
* Google Login Integration
* Search Study Materials
* Download Study Materials
* Responsive User Interface
* Protected Routes

## Admin Features

* Admin Dashboard
* Upload Materials
* Edit Materials
* Delete Materials
* Manage Users
* Role-Based Access Control

---

# 🛠 Technologies Used

## Frontend

* React.js
* Tailwind CSS
* React Router DOM
* Axios
* Context API

## Backend

* Node.js
* Express.js
* JWT Authentication
* bcryptjs
* Multer Middleware

## Database

* MongoDB
* Mongoose

---

# 📂 Project Structure

```bash
eduhubv3/
│
├── client/          # React Frontend
├── server/          # Node.js Backend
├── uploads/         # Uploaded Files
├── package.json
└── README.md
```

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/eduhubv3.git
```

---

## 2. Navigate to Project Folder

```bash
cd eduhubv3
```

---

## 3. Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd client
npm install
```

---

# 🔐 Environment Variables

Create a `.env` file inside the server folder.

## Development Environment

```env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/eduhub
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

---

# ▶️ Run the Project

## Start Backend Server

```bash
cd server
npm run dev
```

## Start Frontend

```bash
cd client
npm run dev
```

---

# 🌐 API Endpoints

## Authentication APIs

```http
POST /api/auth/register
POST /api/auth/login
POST /api/auth/google-login
GET /api/auth/user
```

## Material APIs

```http
POST /api/material/upload
GET /api/materials
GET /api/material/search
PUT /api/material/update/:id
DELETE /api/material/delete/:id
```

## Admin APIs

```http
GET /api/admin/users
GET /api/admin/dashboard
```

---

# 🔒 Security Features

* JWT Authentication
* Password Encryption using bcryptjs
* Protected Routes
* Role-Based Access Control
* Admin Authentication

---

# 📥 File Upload System

The project uses Multer middleware for handling file uploads.

Uploaded files are stored in:

```bash
server/uploads/
```

MongoDB stores:

* File metadata
* Material details
* User information

---

# 📱 Responsive Design

EduHub V3 is fully responsive and works on:

* Desktop
* Laptop
* Tablet
* Mobile Devices

---

# 📈 Future Improvements

* Cloud Storage Integration
* AI-Based Recommendations
* Analytics Dashboard
* Mobile Application
* Real-Time Notifications
* Advanced Security Features

---

# 🎯 Learning Outcomes

This project helped in learning:

* MERN Stack Development
* REST API Development
* Authentication Systems
* MongoDB Database Management
* Frontend-Backend Integration
* File Handling Systems
* Responsive UI Design

---

# 👨‍💻 Author

Developed as a MERN Stack Educational Platform Project for learning full-stack web development concepts.

---

# 📄 License

This project is developed for educational and learning purposes.

