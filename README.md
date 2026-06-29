# E-Learning Platform

A React-based e-learning platform with course management CRUD, video streaming UI, progress tracking, and certificate generation using `json-server` as a backend.

## Features
- Course management: create, read, update, delete.
- Video player page for course lessons.
- Track progress with a slider and progress bar.
- Certificate generation when progress reaches 100%.

## Run locally
1. Open a terminal in `elearning-platform`.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the app and json-server together:
   ```bash
   npm run dev
   ```
4. Open the browser at `http://localhost:3000`.

## Backend
The mock backend runs on `http://localhost:5000` and uses `db.json`.

## Deploy
For deployment on Vercel:
1. Push the repository to GitHub.
2. Create a Vercel project from the repository.
3. Set the build command to `npm run build` and output directory to `dist`.

> Note: `json-server` is a local mock backend, so for full deployment you should replace the backend with a hosted REST API.
