<h1 align="center">Notion Clone</h1>
 
## 🚀 Overview
I am designing a Notion Clone called Haven - Second Brain. The purpose of creating a privacy focused solution to using Notion who steals my data using MERN stack (MongoDB, Express.js, React, Node.js).

## 🎨 UI/UX Design
- 

- 
## 🚀 Features
✅ Create database
✅ Dashboard Multiple Pages (Home, Dashboard, About, Contact)
✅ Authentication (JWT-based login & signup)
✅ Styled with Tailwind CSS
✅ API Integration Ready
✅ Environment Configurations & Security Best Practices

## 📁 File Structure
```
project-mvp-template/
│── backend/                # Express.js backend
│   ├── controllers/        # Business logic for each feature
│   ├── models/             # Mongoose data models
│   ├── routes/             # API endpoints
│   ├── middleware/         # Authentication & security
│   ├── config/             # Database & environment configs
│   ├── utils/              # Helper functions
│   ├── server.js           # Main server file
│   ├── package.json        # Backend dependencies
│
│── frontend/               # React.js frontend
│   ├── public/             # Static files (favicon, index.html)
│   │   ├── index.html      # Main HTML file
│   ├── src/                
│   │   ├── components/     # Reusable UI components (buttons, modals)
│   │   ├── pages/          # Main pages (home, dashboard, about, contact)
│   │   ├── hooks/          # Custom React hooks
│   │   ├── context/        # Global state management
│   │   ├── utils/          # Utility functions
│   │   ├── services/       # API calls (axios)
│   │   ├── styles/         # CSS files (global.css, theme.css)
│   │   ├── assets/         # Static assets (icons, images)
│   │   ├── scripts/        # JavaScript utility scripts
│   │   ├── App.js          # Main React component
│   │   ├── index.js        # Entry point
│   ├── package.json        # Frontend dependencies
│
│── database/               # MongoDB database setup
│   ├── seed.js             # Optional: Seed database with test data
│
│── .env                    # Environment variables
│── .gitignore               # Ignore node_modules, .env, etc.
│── README.md                # Project documentation
│── docker-compose.yml       # Optional: For running backend + database in Docker
```

## 🛠 Tech Stack
- Frontend: React, Vite, Tailwind CSS
- Backend: Node.js, Express.js, MongoDB, Mongoose
- Authentication: JWT, bcrypt.js
- State Management: Context API
- API Requests: Axios

## 🔧 Setup Instructions
1️⃣ Clone the Repository
```
git clone https://github.com/your-username/mvp-project.git
cd mvp-project
```
2️⃣ Setup Backend
```
cd backend
npm install
cp .env.example .env  # Configure environment variables
node server.js
```
3️⃣ Setup Frontend
```
cd ../frontend
npm install
npm run dev
```
4️⃣ Database Setup
- Use MongoDB Atlas or local MongoDB
- Configure MONGO_URI in .env

## 🛣️ Roadmap
- 
- 
- 

## 📜 License

MIT License. Use and modify freely!

---

Made with ❤️ by Melanie Laporte
