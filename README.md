# AiImageGenerator
This is a full-stack AI Image Generator web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) integrated with OpenAI’s DALL·E API to generate images from text prompts. It allows users to enter a creative prompt and generate stunning AI-powered images instantly.
This is a full-stack AI Image Generator web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) integrated with OpenAI’s DALL·E API to generate images from text prompts. It allows users to enter a creative prompt and generate stunning AI-powered images instantly.

🚀 Tech Stack:
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

AI Service: OpenAI DALL·E Image Generation API

Database: MongoDB Atlas (cloud-based)

Image Hosting: Cloudinary (for secure image uploads and access)

💡 Key Features:
Text-to-image generation using OpenAI

Modern and responsive UI using React + Tailwind CSS

Cloud image storage using Cloudinary

Stores generated images and prompts in MongoDB

Option to share generated images with the community

Download or view generated images directly

🔐 Environment Variables (in .env)
env
Copy
Edit
OPENAI_API_KEY=your_openai_key
MONGO_URI=your_mongodb_connection
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
🧠 How It Works:
Enter a text prompt (e.g., “a robot playing guitar on Mars”)

The prompt is sent to the backend server

Backend communicates with OpenAI’s API and gets the image

The image is uploaded to Cloudinary

MongoDB stores the prompt and image URL

Image is displayed to the user with sharing and download options



🛠️ Setup Instructions (optional section):
You can also add setup steps in your README.md like:

Clone the repo

Install dependencies (npm install)

Add .env file

Run frontend and backend (npm run dev etc.)

👩‍💻 Author
Nisha Yadav
B.Tech CSE | Full stack developer
