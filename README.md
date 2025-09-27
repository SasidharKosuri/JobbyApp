# 💼 Jobby App - Job Search Platform

A modern, responsive job search application built with React that provides users with an intuitive interface to discover and explore career opportunities. This project features secure JWT authentication, advanced filtering capabilities, and comprehensive job details with similar job recommendations.

The application demonstrates professional React development practices including component-based architecture, protected routing, responsive design, and efficient state management. It showcases a complete job search platform with real-world features like employment type filtering, salary range selection, and detailed job insights.

---

## 🚀 Features
- ✅ User Authentication with JWT Tokens
- ✅ Advanced Job Filtering by Employment Type and Salary
- ✅ Comprehensive Job Details with Company Profiles
- ✅ Similar Job Recommendations
- ✅ Responsive Design for Mobile and Desktop
- ✅ Protected Routes and Secure Access
- ✅ Real-time Search Functionality
- ✅ Skills Visualization and Company Insights

---

## 🛠️ Tech Stack

### Frontend
- **React.js** - Main framework
- **React Router DOM** - Client-side routing
- **React Icons** - Icon library

### Styling & UI
- **CSS3** - Custom styling with responsive design
- **Flexbox/Grid** - Layout management

### Authentication
- **JWT Tokens** - Secure authentication
- **js-cookie** - Token management

### API Integration
- **Fetch API** - HTTP requests
- **RESTful APIs** - Backend communication

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation Steps
```bash
# Clone the repository
git clone <repository-url>
cd jobby-app

# Install dependencies
npm install

# Start development server
npm start
```

## 🏗️ Project Structure
<img width="749" height="489" alt="image" src="https://github.com/user-attachments/assets/75b8e03f-c162-40f8-adf2-c68652e7f973" />

## 🔐 Authentication
All routes (except /login) are protected and require a valid JWT token stored in cookies. The application automatically handles token validation and redirects to login when necessary.

## 📑 Component Overview
<img width="460" height="457" alt="image" src="https://github.com/user-attachments/assets/6021d526-dbb1-4456-8ff9-74a5d7f2a6e6" />

## 🎯 Key Features Breakdown
### Authentication & Security
- JWT-based user authentication
- Protected routes for authenticated access
- Automatic token management with cookies
- Secure API calls with authorization headers

### Job Search & Filtering
- Employment Type Filters: Full Time, Part Time, Freelance, Internship
- Salary Range Filters: 10 LPA to 40 LPA and above
- Real-time Search: Instant job search functionality
- Combined Filtering: Multiple filter criteria support

### Job Details & Insights
- Company information and logos
- Detailed job descriptions and requirements
- Skills visualization with icons
- Company culture and work environment
- Similar job recommendations
- Direct company website links

### User Experience
- Responsive design for all devices
- Loading states and error handling
- Intuitive navigation and clean UI
- Mobile-optimized interface

## 🌐 API Integration
The application integrates with a job search API providing:
- User authentication endpoints
- Job listings with pagination
- Detailed job information
- User profile data

## 📱 Responsive Design
- Mobile: Optimized for screens < 768px
- Tablet: Adaptive layout for 768px - 1024px
- Desktop: Full-featured experience > 1024px




