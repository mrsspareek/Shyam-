# Bambinos Chess Platform - Pro v2.0

Live interactive chess learning, puzzle solving, and coach analytics platform powered by Supabase Cloud Database & Realtime WebSockets.

## 🚀 Live Portals

- **`index.html`** - Master Platform & Portal Hub
- **`teacher.html`** - Teacher Dashboard (Live Student Tracking, 6-ply Move Accuracy, Red Alerts & Live Board Inspector)
- **`student.html`** - Student Portal (Classroom Join Modal, Unique Student ID & Interactive Solver)
- **`editor.html`** - Puzzle Creator & Cloud Database Library

## ☁️ Architecture

- **Database**: Supabase PostgreSQL (`chess_puzzles` table)
- **Live Sync**: Supabase Realtime Channels (`chess_room_<ROOM_ID>`) + Local Browser BroadcastChannel
- **Client-Side**: 100% Serverless HTML5, CSS3, ES6 JavaScript, Canvas Particles

## 🌐 Deploying to GitHub Pages

1. Go to your Repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, select `Deploy from a branch`.
3. Choose the `main` branch and `/ (root)` folder.
4. Click **Save** — Your platform is live at `https://mrsspareek.github.io/Shyam-/`!
