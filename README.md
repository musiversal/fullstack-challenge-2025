# 🎵 Fullstack Challenge — Mini Song Library

Welcome to the Musiversal Fullstack Challenge!  
This test is designed to assess your skills with **ReactJS**, **NodeJS**, **TypeScript**, and basic **TailwindCSS** styling.

You are expected to complete this challenge in **4 hours or less**. Please manage your time accordingly and focus on delivering a clean, functional solution.

---

## 📚 Challenge Description

You will build a simple application to manage a list of **songs**, including:

- Listing existing songs.
- Adding new songs with an uploaded **album cover image**.
- Deleting songs.

You must build:

- A **backend API** with NodeJS and TypeScript.
- A **frontend** with ReactJS and TypeScript.
- Styling using **TailwindCSS**.

---

## 🛠️ Technical Requirements

### Backend (NodeJS + TypeScript)

- Create a NodeJS server using **Express**, **Fastify**, or similar.
- Endpoints required:
  - `GET /songs` → Return the list of songs.
  - `POST /songs` → Add a new song (accepts an image file upload).
  - `DELETE /songs/:id` → Delete a song by ID.
- Each song must contain:
  - `id: string`
  - `name: string`
  - `artist: string`
  - `imageUrl: string` (path to the uploaded album cover)
- Images must be:
  - Uploaded and saved **locally** (e.g., `/uploads` folder).
  - Served statically via the API.
- Data can be stored **in memory** (no database needed).
- Handle **basic errors** properly.
- Use proper **TypeScript typing** throughout the backend.

🔹 **Hint**: You may use libraries like `multer` for file uploads.

---

### Frontend (ReactJS + TypeScript)

- Fetch and display the list of songs:
  - Show song name, artist name, and album cover image.
- Create a form to add a new song:
  - Inputs: song name (text), artist name (text), album cover image (file upload).
- Add a delete button to remove songs.
- Integrate and use **TailwindCSS** for basic layout and styling.
- Ensure basic loading indicators and error handling.
- Use **React functional components** and **hooks**.

💡 We trust you will come up with something that works in terms of UI.  
We also want to assess your **creativity**!

---

## ⭐ Extra Credit (Optional)

- Add **form validation** (e.g., all fields required, max image size 2MB).
- Allow **editing** a song (optional `PUT /songs/:id` endpoint).
- Add **API documentation** (e.g., Swagger).
- Include **some basic tests** to show confidence in your code.
- **Deploy** the working version (e.g., Vercel, Render) and share the live link.

---

Good luck! 🎶
