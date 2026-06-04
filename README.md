# CampusFlow 🚀

CampusFlow is a comprehensive, full-stack campus management portal designed to streamline university operations for students and administrators. Featuring a stunning Apple-inspired UI, real-time data sync, and Gemini-powered AI integration, CampusFlow unifies everything from placement tracking to mess menus into one beautiful platform.

## 🌟 Key Features

*   **Context-Aware Campus AI:** A highly tuned Gemini 2.5 integration that understands dynamic campus data (like the weekly mess menu) and provides real-time, context-accurate answers to students.
*   **Dynamic Next Meal Tracker:** Automatically fetches the live mess menu and cross-references the user's real-time device clock to display the exact upcoming meal (Breakfast, Lunch, or Dinner).
*   **Premium Light/Dark Theming:** Features a custom-built semantic CSS engine that flawlessly transitions between a sleek Midnight Dark Mode and a professional, high-contrast Apple-inspired Light Mode (Icy Blue / Indigo).
*   **Role-Based Access Control (RBAC):** Secure JWT authentication protecting specific administrative routes, allowing admins to instantly update menus, post announcements, and moderate study materials.
*   **Cloud-Native Database:** Seamlessly integrated with Aiven MySQL cloud hosting to provide real-time data persistence across devices.

## 🛠️ Technology Stack

**Frontend (`/frontend`)**
*   React 18 + Vite
*   TailwindCSS (Custom Semantic Design System)
*   Lucide React Icons
*   Axios

**Backend (`/backend`)**
*   Node.js + Express
*   MySQL2 (with Aiven Cloud integration)
*   Google Gemini AI SDK (v2.5-flash)
*   JSON Web Tokens (JWT) & bcryptjs
*   Multer (for file uploads)

## 🚀 Running Locally

1. Clone this repository.
2. Navigate to the `backend` directory, run `npm install`, add your `.env` variables (Database, JWT, Gemini), and run `npm run dev`.
3. Navigate to the `frontend` directory, run `npm install`, add your `VITE_API_URL` to the `.env`, and run `npm run dev`.

## 📈 Deployment
*   **Frontend:** Vercel
*   **Backend:** Render
*   **Database:** Aiven MySQL
