# Ummay Saima Portfolio

Live portfolio: [https://ummaysaima.vercel.app/](https://ummaysaima.vercel.app/)

This repository contains the full source for a portfolio platform with:
- a public-facing React portfolio
- an admin dashboard for managing content without code changes
- an Express and MongoDB backend API
- an AI assistant named `SUAI` whose knowledge is controlled from the admin panel

## Screenshots

### Hero Section
![Portfolio hero](frontend/public/ss/portfolio%20first%20section.png)

### Introduction Section
![Portfolio introduction](frontend/public/ss/portfolio%20intro%20section.png)

### Contact Section
![Portfolio contact](frontend/public/ss/portfolio%20contact%20section.png)

## Highlights

- Admin-controlled hero, introduction, education, experience, research, projects, certificates, skills, hobbies, and AI knowledge
- Dedicated certifications page with category-based preview on the landing page
- Cloudinary-backed project image uploads
- JWT-protected admin dashboard
- Contact form and recruiter message inbox
- Gemini-powered chatbot with admin-managed knowledge base
- Responsive UI with subtle motion and polished dark-cyan visual system

## Tech Stack

| Layer | Stack |
| --- | --- |
| Frontend | React, Vite, Tailwind CSS, Framer Motion, Axios |
| Backend | Node.js, Express, Mongoose, JWT, Nodemailer |
| AI | Google Gemini |
| Media | Cloudinary |
| Database | MongoDB |
| Deployment | Vercel (frontend), Render (backend) |

## Project Structure

```text
Portfolio_Saima/
|-- frontend/
|   |-- public/
|   |   `-- ss/
|   |-- src/
|   |   |-- api/
|   |   |-- components/
|   |   `-- pages/
|   `-- README.md
|-- backend/
|   |-- config/
|   |-- controllers/
|   |-- middleware/
|   |-- models/
|   |-- routes/
|   |-- .env.sample
|   `-- README.md
`-- README.md
```

## Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/Saima535/portfolio_saima.git
cd portfolio_saima
```

### 2. Start the backend

```bash
cd backend
npm install
copy .env.sample .env
npm run dev
```

### 3. Start the frontend

```bash
cd ../frontend
npm install
npm run dev
```

## Environment Notes

The backend environment template is available in [backend/.env.sample](backend/.env.sample).

It includes configuration for:
- server port
- MongoDB connection
- Gemini API key
- email service credentials
- frontend URL
- admin bootstrap credentials
- Cloudinary media storage

## Documentation

- Frontend setup: [frontend/README.md](frontend/README.md)
- Backend setup: [backend/README.md](backend/README.md)

## Author

Ummay Saima
Full-Stack Engineer | AI Enthusiast | Researcher

- Email: [ummay1351@gmail.com](mailto:ummay1351@gmail.com)
- GitHub: [Ummay Saima](https://github.com/Saima535)
- LinkedIn: [Ummay Saima](https://www.linkedin.com/in/ummay-saima/)
- Kaggle: [Ummay Saima](https://www.kaggle.com/ummaysaima)
