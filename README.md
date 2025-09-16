# MERN Backend Starter

A simple backend setup for a MERN stack application using **Express**, **MongoDB (Mongoose)**, and **dotenv**.

---

## Getting Started

# Prerequisites:
- Node.js 18+ and npm installed
- A MongoDB connection string (Atlas or local)
- Terminal with curl available (Windows 10+ includes curl)

# 0) Verify prerequisites (optional)
node -v
npm -v

# 1) Clone the repository and enter it
git clone <YOUR_REPO_URL>.git
cd <YOUR_PROJECT_FOLDER>

# 2) Install dependencies (uses lockfile if present)
npm install

# 3) Create a .env file
Option A: create a new file and name it .env and add {
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/mydb
}
# MONGO_URI needs to be equal to a real mongodb url

# 4) Start the server
Dev mode (auto-reload via nodemon):
npm run dev
