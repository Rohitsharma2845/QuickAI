🚀 QuickAI

QuickAI is an AI-powered web application that provides multiple productivity and creativity tools in one place. From generating articles and blog titles to creating images, removing backgrounds/objects, and even reviewing resumes—QuickAI helps you get things done faster with the power of AI.

✨ Features

📝 Write Articles – Generate well-structured articles using AI.

📰 Blog Titles – Instantly create engaging and SEO-friendly blog titles.

🌐 Community – Share and explore AI-generated content.

🖼️ Generate Images – Create stunning AI-generated visuals.

🎨 Remove Background – Cleanly remove image backgrounds.

✂️ Remove Objects – Erase unwanted objects from images.

📄 Review Resume – Get AI-powered feedback on resumes.

🛠️ Tech Stack

Frontend Framework: React 19
 + Vite

Routing: React Router v7

Authentication: Clerk

Styling: Tailwind CSS

UI & Icons: Lucide React

Notifications: React Hot Toast

Getting Started
1. Clone the Repository
git clone https://github.com/Rohitsharma2845/QuickAI.git

cd QuickAI

2. Install Dependencies
npm install

3. Run the Development Server
npm run dev


The app will be running at:
👉 http://localhost:5173

🚀 Live Demo
https://quick-ai-one-beta.vercel.app/

🔑 Environment Variables

Create a .env.local file in the root directory and add:

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=your_backend_api_endpoint


(Adjust variable names as per your backend config.)

📂 Project Structure
QuickAI/
│── src/
│   ├── pages/          # App pages (Home, Dashboard, WriteArticle, etc.)
│   ├── components/     # UI components
│   ├── App.jsx         # Main app with routes
│   └── main.jsx        # Entry point
│── package.json
│── vite.config.js
│── tailwind.config.js

🚀 Deployment

You can deploy QuickAI easily on platforms like:

Vercel

Netlify

Build for production:

npm run build

🤝 Contributing

Contributions are welcome! Feel free to open issues and pull requests.

📜 License

This project is licensed under the MIT License.
Markdown Rendering: React Markdown

API Requests: Axios
