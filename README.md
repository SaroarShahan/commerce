# 🛒 Commerce Learning Project

A comprehensive e-commerce platform built with Next.js, featuring separate admin and frontend applications for learning modern web development practices.

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Projects Navigation](#-projects-navigation)
- [Tech Stack](#-tech-stack)
- [Quick Start](#-quick-start)
- [Development](#-development)
- [Project Structure](#-project-structure)
- [Features](#-features)
- [Contributing](#-contributing)
- [License](#-license)

## 🌟 Project Overview

This repository contains two main applications:

1. **Commerce Admin** - Administrative dashboard for managing products, orders, and customers
2. **Commerce Frontend** - Customer-facing e-commerce application

Both applications are built with modern technologies including Next.js 15, React 19, TypeScript, and TailwindCSS.

## 🚀 Projects Navigation

### 📊 [Commerce Admin](/commerce_admin)
> Administrative dashboard for managing the e-commerce platform

**Quick Actions:**
- 🔧 [Setup Instructions](/commerce_admin/README.md#setup)
- 💻 [Development Guide](/commerce_admin/README.md#development)
- 📚 [API Documentation](/commerce_admin/README.md#api)

**Start Development:**
```bash
cd commerce_admin
npm install
npm run dev
```
**Access:** [http://localhost:3000](http://localhost:3000)

---

### 🛍️ [Commerce Frontend](/commerce_frontend)
> Customer-facing e-commerce application

**Quick Actions:**
- 🔧 [Setup Instructions](/commerce_frontend/README.md#setup)
- 💻 [Development Guide](/commerce_frontend/README.md#development)
- 🎨 [UI Components](/commerce_frontend/README.md#components)

**Start Development:**
```bash
cd commerce_frontend
npm install
npm run dev
```
**Access:** [http://localhost:3001](http://localhost:3001)

---

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **Next.js** | 15.5.4 | React framework with SSR/SSG |
| **React** | 19.1.0 | UI library |
| **TypeScript** | ^5 | Type safety |
| **TailwindCSS** | ^4 | Utility-first CSS framework |
| **ESLint** | ^9 | Code linting |
| **Turbopack** | - | Fast bundler (Next.js) |

## ⚡ Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Git

### Clone and Setup
```bash
# Clone the repository
git clone https://github.com/SaroarShahan/commerce.git
cd commerce

# Install dependencies for both projects
npm run install:all  # If you have a root package.json
# OR install individually:
cd commerce_admin && npm install && cd ..
cd commerce_frontend && npm install && cd ..
```

### Run Both Applications
```bash
# Terminal 1 - Admin Dashboard
cd commerce_admin
npm run dev

# Terminal 2 - Frontend Store  
cd commerce_frontend
npm run dev -- --port 3001
```

## 🏗️ Development

### Available Scripts

Each project includes the following npm scripts:

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with Turbopack |
| `npm run build` | Build for production with Turbopack |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint code analysis |

### Development Workflow

1. **Feature Development**
   ```bash
   git checkout -b feature/your-feature-name
   # Make your changes
   git commit -m "feat: add your feature"
   git push origin feature/your-feature-name
   ```

2. **Code Quality**
   ```bash
   npm run lint          # Check code style
   npm run build         # Verify build works
   ```

## 📁 Project Structure

```
commerce/
├── README.md                 # This file
├── commerce_admin/          # Admin dashboard
│   ├── src/
│   │   └── app/
│   │       ├── layout.tsx   # Admin layout
│   │       ├── page.tsx     # Admin homepage
│   │       └── globals.css  # Global styles
│   ├── public/             # Static assets
│   ├── package.json        # Admin dependencies
│   └── README.md          # Admin documentation
├── commerce_frontend/      # Customer frontend
│   ├── src/
│   │   └── app/
│   │       ├── layout.tsx   # Frontend layout
│   │       ├── page.tsx     # Frontend homepage
│   │       └── globals.css  # Global styles
│   ├── public/             # Static assets
│   ├── package.json        # Frontend dependencies
│   └── README.md          # Frontend documentation
```

## ✨ Features

### Commerce Admin
- [ ] Dashboard overview
- [ ] Product management
- [ ] Order management
- [ ] Customer management
- [ ] Analytics and reports
- [ ] User authentication
- [ ] Role-based access control

### Commerce Frontend
- [ ] Product catalog
- [ ] Shopping cart
- [ ] User authentication
- [ ] Checkout process
- [ ] Order history
- [ ] Product search and filtering
- [ ] Responsive design

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Commit Convention
- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `style:` - Code style changes
- `refactor:` - Code refactoring
- `test:` - Adding tests
- `chore:` - Maintenance tasks

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Support & Resources

- 📧 **Issues:** [GitHub Issues](https://github.com/SaroarShahan/commerce/issues)
- 📖 **Documentation:** Check individual project READMEs
- 🎯 **Project Goals:** Learning modern e-commerce development

---

**Happy Coding! 🚀**