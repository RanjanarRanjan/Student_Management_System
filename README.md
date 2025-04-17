# 🎓 Student Management System (Admin)

## 📱 Project Overview

The **Student Management System** is a mobile application built specifically for administrators to manage student data efficiently. Accessible via mobile devices, this app allows the admin to **log in**, **add**, **update**, **delete**, and **view** student records. It's a simple and powerful tool to manage student data on the go.

---

## 🧩 Features

### 👨‍💼 Admin Capabilities
- 🔐 Admin Login
- ➕ Add Student
- 📝 Update Student Details
- ❌ Delete Student
- 👀 View All Students

---

## 🛠 Technologies Used

| Layer         | Technology          |
|---------------|---------------------|
| Frontend      | React Native (Expo) |
| Backend       | NestJS (TypeScript) |
| Database      | MongoDB             |
| Styling       | CSS                 |

---

## 🔧 Other Tools & Libraries

- **Expo Go** 📲 (Mobile development & testing)
- **JWT** 🔐 (Authentication)
- **Multer** 📤 (For handling file uploads, if any)
- **Mongoose** 🧠 (MongoDB ODM)
- **dotenv** 🔒 (Environment variable management)

> 🔑 **Note:** Passwords and sensitive data are stored securely using environment variables via a `.env` file.

---

## 🛠️ Project Setup

### 🔁 1. Clone the Repository

```bash
git clone <repository-url>
cd student-management-system


Setup Backend (NestJS)

```bash
cd backend
npm install
npm run start:dev
⚙️ Create .env file in backend/
Eg:
PORT=5000
MONGO_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key
ADMIN_USERNAME=admin
ADMIN_PASSWORD=123


Setup Frontend (React Native with Expo)
```bash
cd ../frontend
npm install
npx expo start