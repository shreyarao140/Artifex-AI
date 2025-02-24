# Artifex-AI
Full Stack MERN AI Image Generation App using OpenAI DALL-E model ⚛
# DALL-E Community

DALL-E Community is a web application that allows users to create imaginative and visually stunning images using OpenAI's DALL-E model. Users can generate images from text prompts and share them with the community. This project is built using the MERN stack (MongoDB, Express, React, Node.js) along with TailwindCSS for styling and Cloudinary for cloud-based image storage.

---

## :sparkles: Features
- Generate images from text prompts using OpenAI's DALL-E model.
- Share created images with the community.
- Randomized prompt suggestions for creative inspiration.
- Download images directly to your device.
- Responsive UI built with TailwindCSS.

---

## :file_folder: Folder Structure

```
DALL-E-MERN-App/
|- client/
  |-- src/
    |-- assets/         # Static assets and images
    |-- components/     # Reusable UI components (Card, FormField, Loader)
    |-- constants/      # Constant data (e.g., prompt suggestions)
    |-- pages/          # Application pages (Home, CreatePost)
    |-- utils/          # Utility functions (e.g., getRandomPrompt, downloadImage)
  |-- App.jsx           # Main React component
|- server/
  |-- mongodb/
    |-- models/         # Mongoose models (Post.js)
    |-- connect.js      # MongoDB connection configuration
  |-- routes/
    |-- dalleRoutes.js  # Route for handling DALL-E API requests
    |-- postRoutes.js   # Route for managing posts (create, get)
  |-- index.js          # Server setup with Express.js
```

---

## :wrench: Tech Stack
- **Frontend:** React, TailwindCSS, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **APIs & Services:** OpenAI API, Cloudinary

---

## :key: Environment Variables
To run this project, you will need to add the following environment variables to your `.env` file in the `server` folder:

```
MONGODB_URL=<Your MongoDB URL>
OPENAI_API_KEY=<Your OpenAI API Key>
CLOUDINARY_CLOUD_NAME=<Your Cloudinary Cloud Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
```

You can obtain these by creating accounts on:
- [OpenAI](https://openai.com/api)
- [Cloudinary](https://cloudinary.com)

---

## :rocket: Getting Started

### Prerequisites
Make sure you have Node.js and npm installed:
```bash
node -v
npm -v
```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shreyarao140/Artifex-AI
   cd Artifex-AI
   ```

2. Install dependencies for client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Create a `.env` file in the `server` folder and add your environment variables.

### Running the App

1. Start the server:
   ```bash
   cd server
   npm start
   ```

2. Start the client:
   ```bash
   cd client
   npm run dev
   ```

The application will be available at `http://localhost:5173`.

## :gem: Acknowledgements
- [OpenAI API](https://openai.com/api)
- [Cloudinary](https://cloudinary.com)
- [JSMastery](https://jsmastery.pro)

