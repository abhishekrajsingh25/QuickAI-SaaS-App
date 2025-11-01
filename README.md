# 🤖 AI SaaS Application with Six Powerful Features

This is a full-stack **AI SaaS web application** built using the **MERN stack** that provides six cutting-edge AI-powered tools. The app is designed for creators, professionals, and job seekers who want to generate and enhance content quickly and effectively. The application is fully authenticated using **Clerk** and deployed on **Vercel**.

---

## ✨ Features

### 1. Write Article
- Generate full-length, SEO-friendly articles using AI.  
- Option to choose tone and topic.  
- Edit and save your generated articles easily.  

### 2. Blog Title Generator
- Instantly create catchy and optimized blog titles.  
- Perfect for bloggers and content creators.  

### 3. Generate Image
- Create AI-generated images from text prompts.  
- Uses advanced image generation APIs for stunning results.  

### 4. Remove Object
- Upload an image and remove unwanted objects using AI.  
- Clean and realistic editing powered by ClipDrop API.  

### 5. Remove Background
- Automatically remove image backgrounds with high precision.  
- Download images in PNG format with transparent background.  

### 6. Resume Review
- Upload your resume and get instant feedback using AI.  
- Highlights areas of improvement, grammar, and formatting issues.  

## Tech Stack

### Frontend:
- React.js (with Vite)
- Tailwind CSS for styling
- Axios for API communication
- Clerk Authentication

### Backend:
- Node.js with Express.js
- PostgreSQL (via Neon.tech)
- Prisma ORM for database management
- Cloudinary for image storage
- AI APIs: Google Gemini & ClipDrop
- JWT for secure communication

### Deployment:
- Frontend & Backend hosted on **Vercel**
- Database hosted on **Neon.tech**

  
## Setup Instructions

### Prerequisites:

- Node.js and npm installed  
- PostgreSQL (or Neon.tech account)  
- Cloudinary account  
- Clerk account for authentication  
- Gemini and ClipDrop API keys  

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abhishekrajsingh25/QuickAI-SaaS-App.git
   cd QuickAI-SaaS-App
   ```

2. **Install Backend Dependencies**
   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../client
   npm install
   ```
   
   
5. **Environment Variables Setup**
   Create a .env file in the root directory of the backend with the following:
   ```bash
   DATABASE_URL=your_postgresql_connection_url
   CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   GEMINI_API_KEY=your_gemini_api_key
   CLIPDROP_API_KEY=your_clipdrop_api_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

6. **Environment Variables Setup**
   Create a .env file in the root directory of the frontend with the following:
   ```bash
   VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   VITE_BACKEND_URL=http://localhost:3000
   ```
   
   
### Running the Application

1. **Start the Backend Server**
   ```bash
   cd server
   npm run dev
   ```
   The backend server should now be running on `http://localhost:3000`.

2. **Start the Frontend**
   ```bash
   cd ../client
   npm run dev
   ```
   The frontend should now be running on `http://localhost:5173`.

## Deployment

- The frontend and backend can be deployed on Vercel.
- Database is hosted on Neon.tech (PostgreSQL).

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

---

Feel free to contribute, suggest features, or open issues.

---

Thank you for visiting. I hope you find my work interesting and valuable! To see the Website. 
- For Frontend, Click <a href="https://quick-ai-abhishek.vercel.app/" >Here</a>.
