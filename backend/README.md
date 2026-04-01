# Sharekaro.io

live:-  <https://fileshare247.netlify.app/>

Effortlessly Send & Receive Files - Secure🔐, Fast🚀, and Hassle-Free✨! file-sharing web application built with **React, Node.js, Cloudinary, and Multer**.

## 📌 Features

* Upload multiple files and share them easily
* Files are stored securely on Cloudinary
* Short links generated for quick file access
* Fully responsive UI built with React
* Backend powered by Node.js and Express
* Seamless integration with Cloudinary for file storage

## 🚀 Tech Stack

### Backend

- Node.js
* Express.js
* Multer (for file handling)
* Cloudinary (for file storage)
* Short Unique ID (for short links)

## 📥 Installation & Setup

1. **Clone the repository**

   ```sh
   git clone https://github.com/avinashvermaaa/fileshare.git
   cd fileshare
   ```

2. **Set up the backend**

   ```sh
   cd backend
   npm install --legacy-peer-deps
   ```

   Start the backend server:

   ```sh
   npm start
   ```

3. **set .env**

   ```
   MONGO_URI=
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   PORT=
   SERVER_URL=
   FIREBASE_SERVICE_ACCOUNT_KEY_PATH=
   FIREBASE_DATABASE_URL=
   FIREBASE_SERVICE_ACCOUNT=
   ```


## API Endpoints

- `POST /upload` → Uploads files to Cloudinary & returns a short link. `headers: { "Content-Type": "multipart/form-data" }`
- `GET /file/:shortId` → Retrieves the file from Cloudinary using the short link.


## 💙 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---
Made with 💙 by [Avinash Verma]

Happy sharing with **fileshare247.io**! 🎉


