# 🚀 Portfolio Website

A modern, interactive portfolio website showcasing software engineering projects, skills, and professional journey. Built with React and featuring smooth animations, particle effects, and a clean, responsive design.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Development](#-development)
- [Deployment](#-deployment)
- [License](#-license)
- [Author](#-author)

## 🌟 Overview

A dynamic portfolio website built with modern web technologies to showcase professional software engineering work. Features interactive animations, responsive design, and seamless navigation for an engaging user experience.

**Key Capabilities:**

- 🎨 **Interactive UI**: Particle effects and smooth animations create an engaging experience
- 📱 **Fully Responsive**: Mobile-first design optimized for all screen sizes
- 🖼️ **Project Showcase**: Comprehensive gallery with detailed project modals
- 📊 **GitHub Integration**: Live contribution calendar and stats display
- 📄 **Resume Viewer**: Built-in PDF viewer with download capability
- 🎓 **Course Reviews**: Detailed university course reviews with ratings and workload estimates
- ⚡ **Fast Performance**: Optimized with Vite for lightning-fast load times

## ✨ Features

### 🏗️ Core Pages

- **Home Section**: Animated header with particle background and typewriter effect
- **Projects Gallery**: Comprehensive showcase of personal, course, and game development projects with modals
- **Course Reviews**: Detailed reviews of university courses with ratings and workload estimates
- **Resume Page**: PDF resume viewer with download capability

### 🎨 Interactive Components

- **Dynamic Navigation**: Responsive navbar with smooth scrolling and hash-based routing
- **Timeline Component**: Visual representation of education and professional experience
- **Contact Form**: Interactive form for project inquiries and collaboration
- **GitHub Calendar**: Real-time contribution activity visualization

### 🛠️ Advanced Features

- **Particle Effects**: Interactive tsParticles background animations
- **Skills Display**: Categorized tech stack including languages, frameworks, databases, and tools
- **3D Tilt Effects**: Interactive hover animations on project cards
- **Error Boundaries**: Graceful error handling throughout the application

## 🛠 Tech Stack

### Core Framework

- **React 18** - UI library
- **Vite** - Blazing fast build tool
- **React Router DOM 6** - Client-side routing

### UI Components & Styling

- **Bootstrap 5** - CSS framework for responsive design
- **React Bootstrap** - Bootstrap components as React
- **Framer Motion** - Smooth animations
- **Lucide React** & **React Icons** - Beautiful icon libraries

### Specialized Libraries

- **react-tsparticles** - Particle animation effects
- **typewriter-effect** - Animated typing effect
- **react-parallax-tilt** - 3D tilt hover effects
- **react-pdf** - PDF document viewer
- **react-modal** - Accessible modal dialogs
- **react-github-calendar** - GitHub contribution visualization
- **react-vertical-timeline-component** - Timeline UI
- **react-router-hash-link** - Smooth scrolling navigation
- **react-tooltip** - Customizable tooltips
- **react-error-boundary** - Error handling

### Development Tools

- **ESLint** - Code linting with React-specific rules
- **Prettier** - Code formatting
- **Husky** - Git hooks for pre-commit actions
- **lint-staged** - Run linters on staged files
- **gh-pages** - GitHub Pages deployment

## � Getting Started

### Prerequisites

- Node.js (v20.0+ recommended)
- npm

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/arunike/Portfolio-React.git
   ```

2. **Navigate to project directory**

   ```bash
   cd Portfolio-React
   ```

3. **Install Dependencies**

   ```bash
   npm install
   ```

4. **Start the Development Server**

   ```bash
   npm run dev
   ```

5. **Open Your Browser**
   Navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start the Vite development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality
- `npm run lint:fix` - Automatically fix ESLint issues
- `npm run prettier` - Format all files with Prettier
- `npm run deploy` - Deploy to GitHub Pages

## 📁 Project Structure

```
src/
├── App.jsx                # Main application component with routing
├── index.jsx              # Application entry point
├── components/            # Reusable UI components
│   ├── Navbar.jsx         # Navigation bar
│   ├── Footer.jsx         # Footer with social links
│   ├── Particle.jsx       # Particle background effect
│   ├── Pre.jsx            # Preloader component
│   ├── ScrollToTop.jsx    # Scroll to top on route change
│   ├── IndexHTML.jsx      # HTML content viewer
│   └── IndexFolderHTML.jsx # Folder-based HTML viewer
├── pages/                 # Page components
│   ├── home/              # Home page
│   │   ├── HomePage.jsx   # Main home layout
│   │   └── components/    # Home sections
│   │       ├── Header.jsx # Hero section
│   │       ├── PDFViewer.jsx # Resume viewer
│   │       ├── Type.jsx   # Typewriter animation
│   │       ├── sections/  # Main content sections
│   │       │   ├── AboutMe.jsx
│   │       │   ├── Contact.jsx
│   │       │   ├── Projects.jsx
│   │       │   ├── Skills.jsx
│   │       │   └── Timeline.jsx
│   │       ├── github/
│   │       │   └── Github.jsx # GitHub stats
│   │       └── skills/    # Skill category components
│   ├── projects/          # Projects page
│   │   ├── Projects.jsx   # Projects gallery
│   │   ├── ProjectCards.jsx
│   │   └── Modal.jsx      # Project detail modal
│   ├── course_takens/     # Courses page
│   │   └── Course_Taken.jsx
│   └── resume/            # Resume page
│       └── Resume.jsx
├── css/                   # Stylesheets
│   ├── components/        # Component-specific styles
│   └── pages/             # Page-specific styles
└── assets/                # Static assets (images, videos, PDFs)
    ├── imgs/              # Images organized by category
    ├── video/             # Video demonstrations
    ├── resume/            # Resume PDFs
    └── diploma/           # Certificates
```

## 🔧 Development

### Code Quality

This project maintains high code quality through:

- **ESLint**: React-specific linting rules, JSX accessibility checks, and React Hooks rules
- **Prettier**: Automatic code formatting for consistent style
- **Husky Git Hooks**: Pre-commit hooks for linting and formatting
- **lint-staged**: Runs linters only on staged files

### Project Conventions

- Component Organization: Organized by feature and page
- CSS Structure: Separate files for components and pages
- Asset Management: Images and videos organized by category
- Naming Conventions: PascalCase for components, camelCase for functions
- Import Order: External dependencies → Internal components → Styles → Assets

## � Deployment

### GitHub Pages

```bash
npm run deploy
```

This command builds the production bundle and deploys to the `gh-pages` branch, making the site available at your GitHub Pages URL.

### Building for Production

```bash
npm run build
```

The optimized production build will be in the `dist/` directory with minified JavaScript/CSS, optimized assets, and source maps.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## 👤 Author

**Richie Zhou**

- GitHub: [@arunike](https://github.com/arunike)
- LinkedIn: [richiezhou](https://www.linkedin.com/in/richiezhou)
- Portfolio: [arunike.github.io](https://arunike.github.io)
