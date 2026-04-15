# Ektha - On-Demand Household Labor Marketplace

**Ektha** (meaning Unity) is a professional web application designed to bridge the gap between skilled laborers and households. Originally developed as a PHP-based portal, this 2.0 version is a complete re-engineering using **React.js** and **JWT-based authentication** to provide a secure, scalable, and modern user experience.

## 🚀 Key Features
* **Role-Based Access Control (RBAC):** Distinct portals for Admin, User, and Employee using JWT permissions.
* **Smart Service Matching:** Users can book experts in fields like Gardening, Plumbing, and Wiring.
* **Dynamic Fair List:** Real-time hourly rate calculations for transparent pricing.
* **Real-Time Status Updates:** Workers can manage their work lifecycle from `PENDING` to `COMPLETED`.

## 🛠️ Tech Stack
* **Frontend:** React.js (Vite), Tailwind CSS
* **Backend:** Python (FastAPI)
* **Authentication:** JSON Web Tokens (JWT)
* **Database:** Supabase (PostgreSQL) 
* **Deployment:** Vercel

## 🏗️ System Architecture
The project follows a modern decoupled architecture:
1. **The React Client:** Handles the interactive UI and role-based routing.
2. **The API Server:** Manages business logic and JWT issuance.
3. **The Data Layer:** Securely stores employee credentials and booking history.

## 📖 Project Evolution
This project is a redefined version of my undergraduate degree project. It evolves the original concept from a basic web portal into a high-performance marketplace, solving previous limitations in real-time coordination and security.
