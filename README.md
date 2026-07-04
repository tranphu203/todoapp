# Todo App

A full-stack Todo application built with **React**, **Node.js**, **Express**, and **MongoDB**. The project includes secure authentication, Google Sign-In, AI assistant, group chat, avatar management, and an admin dashboard.

## Features

- ✅ Email & Password Authentication
- ✅ Google Sign-In
- ✅ JWT Authentication
- ✅ User-specific Todo Management
- ✅ Admin Dashboard
- ✅ AI Assistant
- ✅ Group Chat
- ✅ User Avatar Upload (Cloudinary)
- ✅ Welcome Email
- ✅ Responsive UI

## Tech Stack

### Frontend
- React
- Vite
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Nodemailer
- Cloudinary
- Multer

## Project Structure

```text
todoapp/
├── frontend-todoapp/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
│
├── backend-todoapp/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── package.json
│   └── README.md
│
└── README.md
```

## Getting Started

### Clone the repository

```bash
git clone https://github.com/tranphu203/todoapp.git
cd todoapp
```

### Backend

```bash
cd backend-todoapp
npm install
npm run dev
```

### Frontend

```bash
cd frontend-todoapp
npm install
npm run dev
```

## Environment Variables

Each project requires its own `.env` file.

### Backend

```env
PORT=
MONGO_URI=
JWT_SECRET=

GOOGLE_CLIENT_ID=

SMTP_HOST=
SMTP_PORT=
SMTP_SECURE=
SMTP_USER=
SMTP_PASS=
MAIL_FROM=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

### Frontend

```env
VITE_API_URL=
VITE_GOOGLE_CLIENT_ID=
```

> Never commit your `.env` files to GitHub.

## Deployment

- **Frontend:** Vercel
- **Backend:** Render
- **Database:** MongoDB Atlas
- **Image Storage:** Cloudinary

## Screenshots

Screenshots will be added after deployment.

## License

This project is developed for learning, portfolio, and personal practice.
