# BC-summitassessment-04-17-25--08-51

This repository contains a minimal full-stack example prepared for deployment on IIS.

## Structure
- `backend/` – Node/Express API that also serves the frontend
- `frontend/` – React client loaded from CDN

## Setup
1. Install [Node.js](https://nodejs.org/) on Windows.
2. From the `backend` directory run:
   ```
   npm install
   npm start
   ```
3. Configure IIS with [iisnode](https://github.com/tjanczuk/iisnode) or a reverse proxy to `backend/server.js`.

Open `http://localhost:3001` to see the app. The backend provides `/api/hello`.
