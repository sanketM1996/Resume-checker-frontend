# 📄 Resume Analyzer

A web-based Resume Analyzer built using **HTML, CSS, and JavaScript** that allows users to upload their PDF resumes, analyzes the content, and provides feedback with a score, color-coded badge, and emoji-based rating system. It also features **light/dark mode toggle**, drag-and-drop file upload, and interactive UI.

## ✨ Features

- 🌓 **Light/Dark Mode Toggle** (with persistent theme via `localStorage`)
- 📂 **Drag-and-Drop Resume Upload**
- 📄 **PDF File Validation**
- 📊 **Resume Scoring with Feedback**
- 🌟 **Emoji-Based Rating System**
- 🔒 Secure File Upload via `fetch` and `FormData`
- ✅ Clean and responsive UI


## 🧠 How It Works

1. User uploads a resume (`.pdf`) via drag-and-drop or file input.
2. The app sends the file to the backend API (`/api/resume/upload`) via `fetch`.
3. Backend analyzes the resume and returns a **score** and **feedback**.
4. The frontend displays:
   - Resume Score (out of 100)
   - A color-coded badge (Green/Yellow/Red)
   - Emoji-based rating
   - Custom feedback message

> 🔧 Backend API must be running at `http://localhost:8080/api/resume/upload` and should accept `multipart/form-data`.

