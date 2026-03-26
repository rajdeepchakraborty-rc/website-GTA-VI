# 🎮 GTA VI Inspired Website

A fully animated, modern web experience inspired by Grand Theft Auto VI, built with React JS and GSAP ScrollTrigger. This project showcases advanced scroll animations, smooth transitions, masking effects, and cutting-edge web animation techniques commonly found in award-winning websites.

![GTA VI Website Preview](https://via.placeholder.com/800x400/1a1a1a/ffffff?text=GTA+VI+Inspired+Website)

## 📋 Table of Contents

- [✨ Features](#-features)
- [🛠️ Technologies Used](#%EF%B8%8F-technologies-used)
- [📋 Prerequisites](#-prerequisites)
- [🚀 Installation](#-installation)
- [💻 Usage](#-usage)
- [🏗️ Project Structure](#%EF%B8%8F-project-structure)
- [📜 Scripts](#-scripts)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

## ✨ Features

- **🎬 Advanced Scroll Animations**: Leveraging GSAP ScrollTrigger for smooth, performance-optimized scroll-based animations
- **🎭 Masking Effects**: Creative masking techniques for dynamic visual transitions
- **📱 Responsive Design**: Fully responsive layout that works seamlessly across all devices
- **⚡ Modern React**: Built with React 19 and modern hooks for optimal performance
- **🎨 Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **🔧 Vite Build Tool**: Lightning-fast development server and optimized production builds
- **📹 Video Integration**: Seamless video playback with custom controls and animations
- **🎯 Interactive Elements**: Hover effects, transitions, and micro-interactions throughout

## 🛠️ Technologies Used

### Core Technologies
- **React 19** - Modern JavaScript library for building user interfaces
- **GSAP 3.14** - Professional-grade animation library for the web
- **Tailwind CSS 4.2** - Utility-first CSS framework
- **Vite 8.0** - Next-generation frontend tooling

### Development Tools
- **ESLint** - Code linting and formatting
- **Vite Plugin React** - React integration for Vite
- **Tailwind Vite Plugin** - Tailwind CSS integration

### Libraries
- **@gsap/react** - React bindings for GSAP
- **react-responsive** - Media query hooks for React

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager
- **Git** for version control

You can check your Node.js version by running:
```bash
node --version
npm --version
```

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/website-GTA-VI.git
   cd website-GTA-VI
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

   Navigate to `http://localhost:5173` to view the website.

## 💻 Usage

### Development
```bash
npm run dev
```
Starts the Vite development server with hot module replacement.

### Production Build
```bash
npm run build
```
Creates an optimized production build in the `dist` folder.

### Preview Production Build
```bash
npm run preview
```
Serves the production build locally for testing.

### Code Linting
```bash
npm run lint
```
Runs ESLint to check for code quality issues.

## 🏗️ Project Structure

```
website-GTA-VI/
├── public/
│   ├── images/          # Static images
│   └── videos/          # Video files
├── src/
│   ├── assets/          # Additional assets
│   ├── sections/        # React components for different sections
│   │   ├── ComingSoon.jsx
│   │   ├── Final.jsx
│   │   ├── FirstVideo.jsx
│   │   ├── Hero.jsx
│   │   ├── Jason.jsx
│   │   ├── Lucia.jsx
│   │   ├── Navbar.jsx
│   │   ├── Outro.jsx
│   │   ├── PostCard.jsx
│   │   ├── SecondVideo.jsx
│   ├── App.css          # Main application styles
│   ├── App.jsx          # Main application component
│   ├── index.css        # Global styles
│   └── main.jsx         # Application entry point
├── constants/           # Application constants
├── eslint.config.js     # ESLint configuration
├── index.html           # HTML template
├── package.json         # Project dependencies and scripts
├── README.md            # Project documentation
└── vite.config.js       # Vite configuration
```

## 📜 Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines
- Follow the existing code style
- Run `npm run lint` before committing
- Test your changes thoroughly
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Rockstar Games** for the inspiration from Grand Theft Auto VI
- **GSAP** for the incredible animation library
- **React** community for the amazing framework
- **Tailwind CSS** for the utility-first approach

---

**Note**: This project is for educational purposes and is not affiliated with Rockstar Games or Grand Theft Auto VI in any way.

Made with ❤️ and lots of ☕
