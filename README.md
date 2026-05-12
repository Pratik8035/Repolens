# 🔍 RepoLens (CodeAtlas AI)

RepoLens is an advanced AI-powered repository analysis platform designed to help developers navigate, visualize, and understand complex codebases instantly. By combining interactive dependency graphs with large language models, RepoLens turns static code into a dynamic, searchable map.

---

## ✨ Key Features

- 🌐 Interactive 2D/3D Architecture Graphs  
  Visualize your project's structure and dependencies in real-time.

- 🤖 AI Chat Assistant  
  Ask questions about your codebase, find bugs, or get onboarding guidance.

- 📂 Smart File Manifest  
  Deep inspection of project files with automated metadata extraction.

- 🔗 Configuration Mapping  
  Automatically detects and connects config files (`package.json`, `tsconfig`, etc.) to their respective modules.

- ⚡ High Performance  
  Built on the MERN stack for speed and scalability.

---

# 🛠️ Tech Stack

## Frontend
- React.js (Vite)
- Tailwind CSS / Vanilla CSS
- Force-graph (2D/3D)
- React Hooks / Context API

## Backend
- Node.js
- Express.js
- MongoDB
- Madge (Dependency Analysis)
- OpenAI / Gemini API

---

# 📁 Project Structure

RepoLens/
│
├── backend/          # Backend server and APIs
├── frontend/         # React frontend application
├── cloned-repos/     # Cloned repositories for analysis
├── scratch/          # Temporary analysis files
├── README.md
└── .gitignore

---

# 🚀 Getting Started

## 📋 Prerequisites

Before running the project, make sure the following are installed:

- Node.js (v18 or higher)
- MongoDB (Local or MongoDB Atlas)
- Git
- npm

---

# ⚙️ Installation Guide

## 1️⃣ Clone the Repository

git clone https://github.com/Pratik8035/Repolens.git

cd Repolens

---

## 2️⃣ Install Backend Dependencies

cd backend

npm install

---

## 3️⃣ Configure Environment Variables

Create a `.env` file inside the `backend` folder and add:

MONGO_URI=your_mongodb_connection_string

API_KEY=your_openai_or_gemini_api_key

PORT=5000

---

## 4️⃣ Start Backend Server

npm run dev

Backend will start on:

http://localhost:5000

---

## 5️⃣ Install Frontend Dependencies

Open another terminal:

cd frontend

npm install

---

## 6️⃣ Start Frontend Server

npm run dev

Frontend will start on:

http://localhost:5173

---

# 🌍 Open in Browser

Visit the following URL in your browser:

http://localhost:5173

---

# 🤖 AI Capabilities

RepoLens uses AI models to:

- Analyze repository structure
- Explain project architecture
- Detect dependency relationships
- Answer codebase-related questions
- Help developers onboard faster

---

# 📊 Visualization Features

- Interactive dependency graphs
- Real-time project mapping
- 2D and 3D visualization support
- Dynamic module linking

---

# ⚡ Performance

- Fast rendering using Vite
- Scalable backend architecture
- Optimized dependency analysis
- Lightweight frontend experience

---

# 🤝 Contributing

Contributions are welcome!

If you would like to improve RepoLens:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

Developed by Pratik Bugade
