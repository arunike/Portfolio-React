# Richie Zhou's Portfolio

A modern, interactive portfolio website showcasing my software engineering projects, skills, and professional journey. Built with React and featuring smooth animations, particle effects, and a clean, responsive design.

## 🌟 Features

- **Dynamic Home Section** - Eye-catching animated header with particle background and typewriter effect
- **Interactive Navigation** - Responsive navbar with smooth scrolling and hash-based routing
- **Modular Component Architecture** - Organized React components for maintainability and scalability
- **Projects Showcase** - Comprehensive gallery of personal, course, and game development projects with modals
- **Course Taken Page** - Detailed reviews of university courses with ratings, workload estimates, and descriptions
- **Skills Display** - Categorized tech stack including programming languages, frameworks, databases, and tools
- **Timeline Component** - Visual representation of education and professional experience
- **Contact Form** - Interactive form for project inquiries and collaboration
- **Resume Viewer** - PDF resume viewer with download capability
- **Particle Effects** - Interactive tsParticles background animations
- **Responsive Design** - Mobile-first design optimized for all screen sizes
- **GitHub Integration** - GitHub contribution calendar display

## 🚀 Getting Started

### Prerequisites

- Node.js (v20.0.0 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/arunike/Portfolio-React.git
   cd Portfolio-React
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**

   Navigate to the URL shown in your terminal (typically `http://localhost:5173`)

### Available Scripts

- `npm run dev` - Start the Vite development server
- `npm run build` - Build for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality
- `npm run lint:fix` - Automatically fix ESLint issues
- `npm run prettier` - Format all files with Prettier
- `npm run deploy` - Deploy to GitHub Pages

## 🛠️ Tech Stack

### Core Technologies

- **React 18** - UI library for building component-based interfaces
- **React Router DOM 6** - Client-side routing with hash-based navigation
- **Vite** - Fast build tool and development server
- **Bootstrap 5** - CSS framework for responsive design
- **React Bootstrap** - Bootstrap components as React components

### Key Libraries

- **react-tsparticles** - Particle animation effects
- **typewriter-effect** - Animated typing effect
- **react-icons** - Icon library (AI, CG, RI, MD, BS icons)
- **react-parallax-tilt** - 3D tilt hover effects
- **react-pdf** - PDF document viewer
- **react-modal** - Accessible modal dialogs
- **react-github-calendar** - GitHub contribution calendar visualization
- **react-vertical-timeline-component** - Vertical timeline UI
- **react-router-hash-link** - Smooth scrolling to hash links
- **react-tooltip** - Customizable tooltips
- **motion (Framer Motion)** - Animation library
- **react-error-boundary** - Error boundary components

### Development Tools

- **ESLint** - Code linting with React-specific rules
- **Prettier** - Code formatting
- **Husky** - Git hooks for pre-commit actions
- **lint-staged** - Run linters on staged files
- **gh-pages** - GitHub Pages deployment

## 📁 Project Structure

```
src/
├── App.jsx                # Main application component with routing
├── index.jsx              # Application entry point
├── style.css              # Global styles
├── App.css                # App-specific styles
├── components/            # Reusable UI components
│   ├── Navbar.jsx         # Navigation bar with routing links
│   ├── Footer.jsx         # Footer with social links
│   ├── Particle.jsx       # Particle background effect
│   ├── Pre.jsx            # Preloader component
│   ├── ScrollToTop.jsx    # Scroll to top on route change
│   ├── IndexHTML.jsx      # HTML content viewer for projects
│   └── IndexFolderHTML.jsx # Folder-based HTML viewer
├── pages/                 # Page components
│   ├── home/              # Home page
│   │   ├── HomePage.jsx   # Main home page layout
│   │   └── components/    # Home page sections
│   │       ├── Header.jsx # Hero section with typewriter
│   │       ├── PDFViewer.jsx # Resume PDF viewer
│   │       ├── Type.jsx   # Typewriter animation component
│   │       ├── sections/  # Main content sections
│   │       │   ├── AboutMe.jsx # About section
│   │       │   ├── Contact.jsx # Contact form
│   │       │   ├── Projects.jsx # Featured projects
│   │       │   ├── Skills.jsx # Tech stack display
│   │       │   └── Timeline.jsx # Experience timeline
│   │       ├── github/
│   │       │   └── Github.jsx # GitHub stats
│   │       └── skills/    # Skill category components
│   │           ├── ProgrammingLangStack.jsx
│   │           ├── FrameworkStack.jsx
│   │           ├── DatabaseStack.jsx
│   │           ├── WebDevStack.jsx
│   │           ├── ToolStack.jsx
│   │           └── OtherStack.jsx
│   ├── projects/          # Projects page
│   │   ├── Projects.jsx   # Projects gallery
│   │   ├── ProjectCards.jsx # Individual project cards
│   │   └── Modal.jsx      # Project detail modal
│   ├── course_takens/     # Courses page
│   │   └── Course_Taken.jsx # Course reviews
│   └── resume/            # Resume page
│       └── Resume.jsx  # Resume viewer
├── css/                   # Organized stylesheets
│   ├── components/        # Component-specific styles
│   │   ├── button.css
│   │   └── pdf_viewer.css
│   └── pages/             # Page-specific styles
│       ├── contact.css
│       ├── course_taken.css
│       ├── project.css
│       ├── skills.css
│       └── timeline.css
└── assets/                # Static assets
    ├── imgs/              # Images organized by type
    │   ├── courses/       # Course thumbnails
    │   ├── projects/      # Project screenshots
    │   ├── techstack/     # Technology icons
    │   └── timeline/      # Timeline images
    ├── video/             # Video demonstrations
    │   ├── cs571/         # Course videos
    │   ├── cs579/
    │   └── projects/
    ├── resume/            # Resume PDFs
    └── diploma/           # Certificates
```

## 🔧 Development

### Code Quality

This project maintains high code quality through:

- **ESLint Configuration**
  - React-specific linting rules
  - JSX accessibility checks
  - Import order validation
  - React Hooks rules
  - Prettier integration

- **Prettier Configuration**
  - Automatic code formatting
  - Consistent style across the codebase

- **Husky Git Hooks**
  - Pre-commit hooks for linting and formatting
  - Prevents committing code with errors

- **lint-staged**
  - Runs linters only on staged files
  - Formats JavaScript, JSX, JSON, CSS, and Markdown files

### Project Conventions

- **Component Organization**: Components are organized by feature and page
- **CSS Structure**: Separate CSS files for components and pages
- **Asset Management**: Images and videos organized by category
- **Naming Conventions**: PascalCase for components, camelCase for functions
- **Import Order**: External dependencies → Internal components → Styles → Assets

## 📦 Building for Production

```bash
npm run build
```

The optimized production build will be in the `dist/` directory. The build process:

- Minifies JavaScript and CSS
- Optimizes images and assets
- Generates source maps
- Creates a production-ready bundle

## 🚀 Deployment

### GitHub Pages

```bash
npm run deploy
```

This command:

1. Builds the production bundle
2. Deploys to the `gh-pages` branch
3. Makes the site available at your GitHub Pages URL

## 📄 License

This project is licensed under the MIT License.

## 👤 Author

**Richie Zhou**

- GitHub: [@arunike](https://github.com/arunike)
- LinkedIn: [richiezhou](https://www.linkedin.com/in/richiezhou)
- Portfolio: [arunike.github.io](https://arunike.github.io)

## 🙏 Acknowledgments

- University of Wisconsin-Madison Computer Sciences Department
- React and Vite communities for excellent documentation
- Open source contributors of all dependencies
- Bootstrap team for the responsive framework
- tsParticles for the particle effects library
