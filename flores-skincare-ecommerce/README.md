# Flores Skincare 🌸

> *"Skincare isn't just routine—it's self-care that heals."*

## About The Project 📖

Flores Skincare is a personal project born from a journey with hormonal acne and acne scars. For me, skincare became more than just products—it became a source of comfort, healing, and empowerment. 

As someone who spent countless hours browsing e-commerce platforms searching for solutions that worked, I wanted to create a space that understands the struggle. This project is my way of combining my personal experience with my passion for development, bringing together the world of skincare and modern technology.

## The Story Behind Flores 🌺

This isn't just another e-commerce site. It's a reflection of a personal transformation—from feeling defeated by skin issues to finding empowerment through self-care. Every product listed is a testament to the journey of finding what works, learning about ingredients, and embracing the process of healing.

The name "Flores" (meaning "flowers") represents growth, bloom, and the beauty that comes from nurturing yourself—inside and out.

## What's Built So Far 🏗️

### Frontend
- **React** with Vite for fast development
- Connected to backend via proxy configuration
- Real-time status monitoring for backend connectivity

### Backend
- **Express.js** server
- CORS configured for secure frontend-backend communication
- Health check endpoint (`/api/health`) to verify connection

### Tech Stack
```
Frontend: React + Vite
Backend: Node.js + Express
Development: Nodemon for auto-restart
Proxy: Vite proxy configuration for seamless API calls
```

## Current Progress ✅

The foundation is in place:
- ✅ Frontend and backend are talking to each other
- ✅ Development environment is set up with hot reloading
- ✅ API endpoint is active and returning responses
- ✅ Server runs smoothly on port 5000

## Images to show progress

<img width="1920" height="1020" alt="Screenshot 2026-07-23 211202" src="https://github.com/user-attachments/assets/7cadd2c4-6413-481f-95a5-edf2f79e04e1" />
<img width="1920" height="1020" alt="Screenshot 2026-07-19 133522" src="https://github.com/user-attachments/assets/b950dd34-0c64-4377-947f-698f91053c8b" />
<img width="1920" height="1020" alt="Screenshot 2026-07-19 133038" src="https://github.com/user-attachments/assets/d29320c2-bfb7-4849-889e-e30a4b759804" />
<img width="1920" height="1020" alt="Screenshot 2026-07-19 132954" src="https://github.com/user-attachments/assets/5284542e-84c9-42f0-998b-102ba26d8bf1" />
<img width="1866" height="683" alt="Static website hosting setup" src="https://github.com/user-attachments/assets/1f710b70-d303-4848-bad1-da416e9265d6" />
<img width="989" height="756" alt="Simulearn File Systems in the cloud" src="https://github.com/user-attachments/assets/1c84c8a4-fe42-46e9-a0f5-1cb9cbb0c803" />
<img width="1916" height="1016" alt="Screenshot 2026-08-25 003016" src="https://github.com/user-attachments/assets/4fb4dfb3-d30a-42da-a248-37ad235425c1" />
<img width="1916" height="965" alt="Screenshot 2026-08-25 002958" src="https://github.com/user-attachments/assets/eecf73b6-e2dc-4841-8702-61bdea1d5004" />
<img width="1899" height="468" alt="Screenshot 2026-08-25 002444" src="https://github.com/user-attachments/assets/0b8fc6e6-fd20-4faa-9952-3d746e56f768" />
<img width="1903" height="914" alt="Screenshot 2026-08-24 235131" src="https://github.com/user-attachments/assets/33c7937e-b258-4ba4-9ce1-bbee31d3c041" />
<img width="1920" height="1020" alt="Screenshot 2026-08-24 232527" src="https://github.com/user-attachments/assets/c4e0fe65-4a89-4b09-88ec-3960bbcf672c" />
<img width="1920" height="1020" alt="Screenshot 2026-08-23 150250" src="https://github.com/user-attachments/assets/b06bec68-dfe2-4081-808c-a773017ccb25" />
<img width="745" height="449" alt="Screenshot 2026-08-21 230453" src="https://github.com/user-attachments/assets/5c126eaa-4c8b-40a7-bc5c-1ef1fa23680c" />
<img width="960" height="1020" alt="Screenshot 2026-08-21 230400" src="https://github.com/user-attachments/assets/256eeb0a-f8a5-49a5-9bf6-13007e9ce107" />
<img width="960" height="1020" alt="Screenshot 2026-08-21 230307" src="https://github.com/user-attachments/assets/36beddf9-dc7d-47f5-acb0-6e68d3631ff0" />
<img width="1920" height="1080" alt="Screenshot 2026-08-21 224209" src="https://github.com/user-attachments/assets/ee2be9d8-01be-401a-83bb-176cb68b98d4" />
<img width="976" height="190" alt="Screenshot 2026-08-01 221658" src="https://github.com/user-attachments/assets/721938fd-8d0d-4840-aec9-94b5b0d19906" />




## How It Works 🔧

The frontend fetches data from the backend through a Vite proxy:

```javascript
// Frontend connects to backend health check
fetch("/api/health")
  .then(response => response.json())
  .then(data => console.log("Connected!", data.message));
```

The backend responds with:

```json
{
  "success": true,
  "message": "Flores backend is connected 🌸"
}
```

## Getting Started 🚀

### Prerequisites
- Node.js
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/flores-skincare.git
```

2. Install dependencies
```bash
# Frontend
npm install

# Backend
cd backend
npm install
```

3. Run the development servers
```bash
# Backend (from backend directory)
npm run dev

# Frontend (from root directory)
npm run dev
```

The backend will run on `http://localhost:5000` and the frontend on `http://localhost:5173`.

## Future Vision 🔮

While I'm proud of what's been built, the vision for Flores Skincare is much bigger:

- **AWS Integration** - Moving to the cloud for scalability
- **Product Database** - Curated skincare products
- **User Authentication** - Secure user accounts
- **Shopping Cart** - Seamless e-commerce experience
- **Skin Care Education** - Ingredient guides and skin health resources
- **Community Features** - Reviews and shared experiences

## Why This Matters 💜

This project represents:
- **Personal Healing** - Turning struggle into strength
- **Technical Growth** - Learning full-stack development
- **Empathy in Design** - Building for others who share similar experiences
- **Diversity in Tech** - Showing that tech can be personal and meaningful

## Connect With The Project 🌐

This is a work in progress, and every step forward is meaningful. Whether you're here to learn, to contribute, or just because you relate to the story—welcome.

---

*"Flores" - because even through the struggle, we bloom.* 🌸
