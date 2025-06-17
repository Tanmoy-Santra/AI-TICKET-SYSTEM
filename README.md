
# 🎟️ AI Ticket Assistance System

An intelligent support ticketing system powered by the MERN stack (MongoDB, Express.js, React, Node.js) and integrated with AI to assist users in resolving their queries efficiently.

## 🚀 Features

- 🔐 **User Authentication** (Register/Login)
- 🧠 **AI Assistant** for ticket suggestions or resolutions
- 📝 **Create, View, and Manage Support Tickets**
- 📂 **Role-based Access** (Admin & Users)
- 💬 **Commenting System** on tickets
- 📊 **Dashboard** with ticket stats
- 📦 **Mongoose & MongoDB** for scalable data storage
- 🎨 **Responsive UI** with React and TailwindCSS
- ⚙️ **RESTful APIs** using Express.js

## 🛠️ Tech Stack

- **Frontend:** React, TailwindCSS, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Authentication:** JWT, bcrypt
- **AI Integration:** OpenAI or custom ML model (as applicable)
- **Hosting:** Vercel (Frontend), Vercel/Render (Backend)

## 📁 Folder Structure

```
ai-ticket-system/
├── ai-ticket-frontend/     # React frontend
├── ai-ticket-backend/      # Node/Express backend
└── README.md
```

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-ticket-system.git
cd ai-ticket-system
```

### 2. Install Frontend Dependencies

```bash
cd ai-ticket-frontend
npm install
```

### 3. Install Backend Dependencies

```bash
cd ../ai-ticket-backend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside both `ai-ticket-frontend` and `ai-ticket-backend` folders.

#### Backend `.env` example:

```env
PORT=6969
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

#### Frontend `.env` example:

```env
VITE_API_BASE_URL=http://localhost:6969/api
```

### 5. Run the Project

#### Start Backend

```bash
cd ai-ticket-backend
npm run dev
```

#### Start Frontend

```bash
cd ../ai-ticket-frontend
npm run dev
```

## 🧪 Testing

Use Postman or your frontend to test:
- `POST /api/users/login`
- `POST /api/tickets`
- `GET /api/tickets`

## 🙋‍♂️ Author

**Tanmoy Santra**  
[LinkedIn](https://www.linkedin.com/in/tanmoy-santra) • [GitHub](https://github.com/yourusername)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
