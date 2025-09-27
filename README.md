# 💼 Jobby App - Job Search Platform

A modern, responsive job search application built with React that provides users with an intuitive interface to discover and explore career opportunities. This project features secure JWT authentication, advanced filtering capabilities, and comprehensive job details with similar job recommendations.

The application demonstrates professional React development practices including component-based architecture, protected routing, responsive design, and efficient state management. It showcases a complete job search platform with real-world features like employment type filtering, salary range selection, and detailed job insights.

## 🚀 Features

### Job Search & Filtering
- Advanced filters by employment type (Full Time, Part Time, Freelance, Internship)
- Salary range filtering (10 LPA to 40 LPA and above)
- Real-time search functionality
- Combined filter application

### Job Details & Insights
- Comprehensive job information with company profiles
- Required skills visualization
- Company culture and work environment details
- Similar job recommendations

### User Experience
- Secure JWT-based authentication
- Responsive mobile-first design
- Protected routes for authenticated pages
- Loading states and error handling

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

### 🔐 Authentication
All routes (except /login) are protected and require a valid JWT token stored in cookies. The application automatically handles token validation and redirects to login when necessary.


