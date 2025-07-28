# AI SaaS Project

A full-stack AI-powered SaaS platform with a React + Vite frontend and an Express.js backend. The platform provides AI content generation, image processing, and resume review features, with authentication and premium subscription support.

---

## Tech Stack

### Frontend
- **React**: UI library for building interactive user interfaces
- **Vite**: Fast build tool and development server
- **Tailwind CSS**: Utility-first CSS framework for styling
- **React Router DOM**: Client-side routing
- **Clerk**: Authentication and user management
- **Axios**: HTTP client for API requests
- **Lucide React**: Icon library
- **React Hot Toast**: Toast notifications
- **React Markdown**: Render markdown content

### Backend
- **Node.js & Express.js**: REST API server
- **Clerk**: Authentication middleware
- **OpenAI & Gemini API**: AI content and image generation
- **Cloudinary**: Image upload and transformation
- **Multer**: File upload middleware
- **Neon Database**: Serverless Postgres database
- **PDF-Parse**: PDF file parsing for resume review
- **CORS**: Cross-origin resource sharing
- **Dotenv**: Environment variable management

---

## Features
- **AI Article & Blog Title Generation**
- **AI Image Generation**
- **Remove Image Background/Object**
- **Resume Review with AI**
- **User Authentication & Authorization (Clerk)**
- **Premium Subscription Support**
- **User Creations Management (like, publish, view)**

---

## Project Structure

```
client/           # Frontend (React + Vite)
  src/
    components/   # Reusable UI components
    pages/        # Application pages
    assets/       # Images, icons, and static assets
  public/         # Static files
  ...

server/           # Backend (Express.js)
  configs/        # Configuration files (Cloudinary, DB, Multer)
  controllers/    # Route controllers (AI, User)
  middlewares/    # Custom middleware (auth)
  routes/         # API route definitions
  ...
```

---

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- npm or yarn

### Setup

1. **Clone the repository**
   ```sh
   git clone https://github.com/bmaarianto/ai-saas-project.git
   cd ai-saas-project
   ```

2. **Install dependencies**
   ```sh
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Configure environment variables**
   - Create a `.env` file in the `server/` directory with your API keys and database credentials.

4. **Run the development servers**
   - **Frontend**:
     ```sh
     cd client
     npm run dev
     ```
   - **Backend**:
     ```sh
     cd server
     npm run server
     ```

---
