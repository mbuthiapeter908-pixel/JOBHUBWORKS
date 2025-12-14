# 🚀 JobHub - Youth Career Platform

<div align="center">

![JobHub](https://img.shields.io/badge/JobHub-Youth%20Jobs-brightgreen)
![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue)
![SDG 8](https://img.shields.io/badge/Aligned-SDG%208-yellow)
![Live](https://img.shields.io/badge/Live-Deployment-success)

**Connecting talented youth with amazing career opportunities** ✨

[🌐 Live Demo](https://jobhub-works.vercel.app) • [🚀 API Documentation](https://backenddeployment-1-wwzi.onrender.com/api) • [💼 Explore Jobs](https://jobhub-works.vercel.app/jobs)

</div>

## 📖 Table of Contents
- [🌟 Features](#-features)
- [🚀 Live Deployment](#-live-deployment)
- [🛠️ Tech Stack](#️-tech-stack)
- [🎯 Project Overview](#-project-overview)
- [📁 Project Structure](#-project-structure)
- [⚡ Quick Start](#-quick-start)
- [🔧 API Endpoints](#-api-endpoints)
- [🎨 UI Components](#-ui-components)
- [📈 Future Enhancements](#-future-enhancements)
- [🤝 Contributing](#-contributing)
- [👨‍💻 Author](#-author)

## 🌟 Features

### 🎯 For Job Seekers
- **🔍 Smart Job Search** - Advanced filtering by category, location, and job type
- **⚡ Quick Apply** - One-click applications with beautiful modals
- **📱 Responsive Design** - Perfect experience on all devices
- **🔐 Secure Authentication** - Powered by Clerk
- **💼 Career Dashboard** - Track applications and saved jobs
- **🎨 Beautiful UI** - Modern design with Tailwind CSS

### 🏢 For Employers
- **🚀 Easy Job Posting** - Simple and intuitive job creation
- **👥 Candidate Management** - View and manage applications
- **🏆 Company Profiles** - Showcase your brand
- **📊 Analytics** - Track application metrics
- **⚡ Fast Deployment** - Get your jobs live in minutes

## 🚀 Live Deployment

<div align="center">

### 🌐 Frontend - Vercel
[![Vercel](https://img.shields.io/badge/Vercel-Deployed-black?style=for-the-badge&logo=vercel)](https://jobhub-works.vercel.app)

**URL:** https://jobhub-works.vercel.app

### 🔧 Backend - Render
[![Render](https://img.shields.io/badge/Render-Deployed-blue?style=for-the-badge&logo=render)](https://backenddeployment-1-wwzi.onrender.com)

**URL:** https://backenddeployment-1-wwzi.onrender.com

### 🗄️ Database - MongoDB Atlas
[![MongoDB](https://img.shields.io/badge/MongoDB-Cloud-green?style=for-the-badge&logo=mongodb)](https://cloud.mongodb.com)

### 🔐 Authentication - Clerk
[![Clerk](https://img.shields.io/badge/Clerk-Authentication-purple?style=for-the-badge)](https://clerk.com)

</div>

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-4.5.0-646CFF?logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-38B2AC?logo=tailwind-css)
![React Router](https://img.shields.io/badge/React_Router-6.20-CA4245?logo=react-router)
![Clerk](https://img.shields.io/badge/Clerk-Auth-6C47FF)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-18.0-339933?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-4.18-000000?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-8.0-47A248?logo=mongodb)
![Mongoose](https://img.shields.io/badge/Mongoose-8.0-880000?logo=mongoose)

### Deployment & Services
![Vercel](https://img.shields.io/badge/Vercel-Frontend-000000?logo=vercel)
![Render](https://img.shields.io/badge/Render-Backend-46E3B7?logo=render)
![MongoDB Atlas](https://img.shields.io/badge/MongoDB_Atlas-Database-47A248?logo=mongodb)

## 🎯 Project Overview

JobHub is a modern, full-stack job platform specifically designed for youth employment and the whole people in large, aligned with **UN Sustainable Development Goal 8: Decent Work and Economic Growth**. The platform bridges the gap between young talent and forward-thinking companies.

### 🌟 Key Achievements
- ✅ **Full-stack MERN application** deployed and live
- ✅ **Real-time job applications** with secure authentication
- ✅ **Responsive, beautiful UI** with modern design principles
- ✅ **Scalable architecture** with cloud deployment
- ✅ **Production-ready** with error handling and validation

## 📁 Project Structure

```
jobhub/
├── 🌐 frontend/ (Vercel)
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── services/      # API services
│   │   └── styles/        # Global styles
│   └── package.json
├── 🔧 backend/ (Render)
│   ├── models/           # MongoDB models
│   ├── routes/           # API routes
│   ├── controllers/      # Route controllers
│   ├── config/           # Configuration files
│   └── package.json
└── 📚 README.md
```

## ⚡ Quick Start

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local or Atlas)
- Clerk account

### Local Development

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/jobhub.git
cd jobhub
```

2. **Setup Backend**
```bash
cd backend
npm install
cp .env.example .env
# Add your environment variables
npm run dev
```

3. **Setup Frontend**
```bash
cd frontend
npm install
cp .env.example .env
# Add your environment variables
npm run dev
```

4. **Access the application**
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 🔧 API Endpoints

### Jobs
- `GET /api/jobs` - Get all jobs with filtering
- `GET /api/jobs/:id` - Get single job details
- `POST /api/jobs` - Create new job (employers)
- `POST /api/applications/apply` - Apply for a job

### Applications
- `GET /api/applications/user/:userId` - Get user's applications
- `GET /api/applications/job/:jobId` - Get job applications (employer)

### Employers
- `GET /api/employers` - Get all employers
- `POST /api/employers` - Create employer profile

### Health & Status
- `GET /api/health` - API health check
- `GET /api` - API information

## 🎨 UI Components

### Core Components
- **JobCard** 📄 - Beautiful job listings with apply functionality
- **JobSearch** 🔍 - Advanced search with filters
- **ApplyModal** ✉️ - Elegant application interface
- **Navbar** 🧭 - Responsive navigation with auth
- **Footer** 📞 - Professional footer with links

### Pages
- **Home** 🏠 - Captivating landing page with hero section
- **Jobs** 💼 - Job listings with search and filters
- **JobDetails** 📋 - Detailed job view with application
- **Employers** 🏢 - Employer information and registration
- **Dashboard** 📊 - User dashboard (authenticated)

## 📈 Future Enhancements

<div align="center">

### 🚀 Coming Soon Features

</div>

### 1. 🤖 AI-Powered Job Matching
![AI](https://img.shields.io/badge/AI-Matching-FF6B6B)
- **Smart recommendations** based on user skills and preferences
- **Resume parsing** and automatic skill extraction
- **Personalized job alerts** with machine learning
- **Career path suggestions** based on market trends

### 2. 💬 Real-time Chat & Notifications
![Real-time](https://img.shields.io/badge/Real--time-Chat-4ECDC4)
- **Instant messaging** between employers and candidates
- **Push notifications** for application updates
- **Interview scheduling** with calendar integration
- **Status tracking** with real-time updates

### 3. 📊 Advanced Analytics Dashboard
![Analytics](https://img.shields.io/badge/Analytics-Dashboard-45B7D1)
- **Employer analytics** - application metrics and insights
- **Candidate analytics** - job search performance
- **Market trends** - salary insights and demand patterns
- **Performance reports** - detailed application analytics

## 🎯 SDG Alignment

This project directly supports **UN Sustainable Development Goal 8**:
- ✅ **Promote sustained economic growth**
- ✅ **Productive employment and decent work for all**
- ✅ **Equal pay for work of equal value**
- ✅ **Safe and secure working environments**

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues and enhancement requests.

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Standards
- Use meaningful commit messages
- Follow existing code style
- Add comments for complex logic
- Test thoroughly before submitting

## 👨‍💻 Author

<div align="center">

### **Developed by Mbuthia Peter**

[![Portfolio](https://img.shields.io/badge/Portfolio-Mbuthia-FF6B6B?style=for-the-badge)](https://your-portfolio.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/
peter-mbuthia-1818Pixel
)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/mbuthiapeter908-pixel)

</div>

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Support

If you find this project helpful, please give it a ⭐️ on GitHub!

---

<div align="center">

### **Ready to start your career journey?** 🚀

[Visit JobHub](https://jobhub-works.vercel.app) • [Explore Jobs](https://jobhub-works.vercel.app/jobs) • [For Employers](https://jobhub-works.vercel.app/employers)

*Building the future of youth employment worldwide, one connection at a time* 💫

</div>