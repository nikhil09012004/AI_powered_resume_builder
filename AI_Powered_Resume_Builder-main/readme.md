# 1️⃣ Initialize Node.js project
npm init -y

# 2️⃣ Install frontend dependencies (React, Parcel)
npm install react react-dom parcel @babel/preset-react

# 3️⃣ Install backend dependencies (Express, CORS, Axios, dotenv)
npm install express cors dotenv body-parser axios

# 4️⃣ (Optional) Install nodemon for automatic server restarts
npm install --save-dev nodemon

in package.json remove "main" key and value


Now to run the code
For frontend
1: Go to root directory
    cmd:  npx parcel index.html

to stop the server
    press: ctrl + c