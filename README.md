# SwiftHire 🚀💼 

SwiftHire is a modern job-matching platform that bridges the gap between employers and job seekers for short-term gigs. With an intuitive design and a powerful backend, it streamlines job postings and applications effortlessly.

---

## 🌟 Key Features
- **👨‍💼 Employer Dashboard**: Easily post, manage, and track job listings.
- **🧑‍💻 Job Seeker Portal**: Create profiles, browse jobs, and apply effortlessly.
- **🔐 Secure Authentication**: Role-based access with strong security protocols.
- **📱 Fully Responsive**: Optimized for both desktop and mobile devices.

---

## 🛠️ Tech Stack

### 🎨 Frontend
- **⚛️ React** – Interactive and dynamic UI.
- **🎨 Tailwind CSS** – Modern utility-first styling.
- **🔄 Redux** – Efficient state management.
- **⚡ Vite** – Fast and optimized build tool.
- **📜 JavaScript/JSX** – Core logic and structure.

### 🏗️ Backend
- **☕ Java** – The backbone of the backend.
- **🚀 Spring Boot** – High-performance RESTful API framework.
- **🗄️ MySQL** – Reliable data storage solution.

---

## 📁 Project Structure

### 🔙 Backend
```bash
backend/
├── .gitignore               # Ignored files for version control
├── .idea/                   # IDE-specific configurations
├── .mvn/                    # Maven wrapper scripts
├── mvnw                     # Maven wrapper for UNIX
├── mvnw.cmd                 # Maven wrapper for Windows
├── pom.xml                  # Maven build configuration
├── src/                     # Source code
│   ├── main/
│   │   ├── java/com/example/Swifthire/ # Core backend logic & APIs
│   │   └── resources/                  # Configuration files
│   └── test/                           # Unit tests
└── target/                  # Compiled build artifacts
```

### 🎭 Frontend
```bash
frontend/
├── .contentlayer/           # Static content assets
├── .eslintrc.cjs            # Linting rules
├── .gitignore               # Git ignored files
├── index.html               # App entry point
├── node_modules/            # Dependencies
├── package.json             # Project metadata
├── postcss.config.js        # PostCSS setup
├── public/                  # Public assets
├── src/                     # Source code
│   ├── API/                 # API utility functions
│   ├── App.jsx              # Root component
│   ├── auth/                # Authentication logic
│   ├── components/          # Reusable UI components
│   ├── customHooks/         # Custom hooks
│   ├── globals.css          # Global styles
│   ├── localStorage.js      # Local storage helpers
│   ├── main.jsx             # React entry point
│   ├── pages/               # Page components
│   ├── redux/               # State management setup
│   ├── types.js             # Type definitions
│   └── validations/         # Form validation logic
├── tailwind.config.js       # Tailwind setup
└── vite.config.js           # Vite configuration
```

---

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- **Node.js** & **npm** (for frontend)
- **Java 17+** (for backend)
- **MySQL** (for database)

### 🏗️ Installation & Setup

#### 1. Clone the Repository
```bash
git clone https://github.com/your-username/SwiftHire--A-Job-Marketplace-Platform.git
cd SwiftHire--A-Job-Marketplace-Platform
```

#### 2. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd SwiftHire_backend
   ```
2. Install dependencies and run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

#### 3. Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../SwiftHire_frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### 🎯 Usage
- Access the frontend at **`http://localhost:5173`**
- Backend runs on **`http://localhost:8080`**
