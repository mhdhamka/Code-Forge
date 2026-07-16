# 🚀 VertexCode

> A modern, browser-based code editor built with Next.js, TypeScript, and Monaco Editor.

VertexCode is a lightweight online code editor inspired by Visual Studio Code. It provides a clean development experience with syntax highlighting, multiple programming languages, customizable editor themes, and real-time code editing directly in the browser.

> **⚠️ Project Status:** This project is currently under active development. Features and documentation may change as development continues.

---

## ✨ Features

- 💻 Monaco Editor (VS Code Editor)
- 🎨 Multiple Editor Themes
- 🌐 Support for Multiple Programming Languages
- ⚡ Fast UI built with Next.js 15
- 🔥 TypeScript Support
- 🌙 Dark Mode
- 📱 Responsive Design
- 🔒 Authentication with Clerk *(if enabled)*
- ☁️ Backend powered by Convex *(if enabled)*
- 📝 Auto-saving *(planned)*
- ▶️ Online Code Execution *(currently being updated due to Piston API changes)*

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Next.js | React Framework |
| React | UI Development |
| TypeScript | Type Safety |
| Tailwind CSS | Styling |
| Monaco Editor | Code Editor |
| Clerk | Authentication |
| Convex | Backend & Database |
| Framer Motion | Animations |
| Zustand | State Management *(if used)* |

---

## 📁 Project Structure

```
vertexcode/
│
├── app/
├── components/
├── hooks/
├── lib/
├── providers/
├── public/
├── types/
├── utils/
├── convex/
├── middleware.ts
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/vertexcode.git
```

### 2. Navigate into the project

```bash
cd vertexcode
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file and add the required environment variables.

Example:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CONVEX_URL=
```

> Never commit your actual `.env.local` file to GitHub.

### 5. Run the development server

```bash
npm run dev
```

Visit

```
http://localhost:3000
```

---

## 📸 Screenshots

> Screenshots will be added once the project reaches a stable release.

---

## 🗺️ Roadmap

- [x] Monaco Editor Integration
- [x] Theme Switching
- [x] Multi-language Support
- [x] Clerk Authentication
- [x] Convex Backend
- [ ] Code Execution API
- [ ] File Explorer
- [ ] Terminal
- [ ] GitHub Integration
- [ ] AI Code Assistant
- [ ] Collaboration Mode

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is intended for educational and portfolio purposes.

---

## 📊 Project Status

![Next.js](https://img.shields.io/badge/Next.js-15-black)
![React](https://img.shields.io/badge/React-19-61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8)
![Monaco](https://img.shields.io/badge/Editor-Monaco-007ACC)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![License](https://img.shields.io/badge/License-Educational-lightgrey)
