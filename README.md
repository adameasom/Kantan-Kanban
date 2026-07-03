# Kantan Kanban

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-7-purple?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?logo=javascript)
![License](https://img.shields.io/badge/License-MIT-green)

A lightweight Kanban-style task management application built with **React** and **Vite**.

This project was created to strengthen my understanding of React component architecture, state management, drag-and-drop functionality, and browser storage while building a clean, responsive application with a focus on usability.

## 🌐 Live Demo

🔗 https://kantankanban.netlify.app/

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Skills Demonstrated](#-key-skills-demonstrated)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [What I Learned](#-what-i-learned)
- [Challenges](#-challenges)
- [Future Improvements](#-future-improvements)
- [Screenshots](#-screenshots)
- [Author](#-author)

---

## 📌 Overview

Kantan Kanban is a simple and intuitive task management application inspired by the Kanban workflow.

Users can create, edit, delete, and organise tasks by dragging them between workflow columns. Tasks are automatically saved using `localStorage`, allowing progress to persist between browser sessions.

Alongside the core functionality, I focused on creating a polished user experience by implementing responsive design, accessibility improvements, dark mode support, confirmation dialogs, and other small usability enhancements.

---

## 💪 Key Skills Demonstrated

- React component architecture
- State management using React Hooks
- Drag-and-drop implementation
- Browser data persistence with `localStorage`
- Responsive web design
- Accessibility best practices
- Component reusability
- User experience improvements

---

## ✨ Features

- ✅ Create new tasks
- ✅ Edit existing tasks
- ✅ Delete tasks with confirmation
- ✅ Drag and drop tasks between columns
- ✅ Automatically save tasks using `localStorage`
- ✅ Dark mode with saved user preference
- ✅ Responsive layout for desktop and mobile
- ✅ Task creation timestamps
- ✅ Tooltips for improved usability
- ✅ Accessibility improvements using ARIA labels
- ✅ Optional vibration feedback on supported mobile devices

---

## 🛠 Technologies Used

- React
- Vite
- JavaScript (ES6+)
- HTML5
- CSS3
- @hello-pangea/dnd
- React Icons
- React Tooltip

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/adameasom/Kantan-Kanban.git
```

### Navigate into the project

```bash
cd Kantan-Kanban
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

---

## 📁 Project Structure

```
src/
│
├── components/
├── hooks/
├── utils/
├── App.jsx
├── main.jsx
└── styles/
```

---

## 📚 What I Learned

Building this project helped me develop a stronger understanding of:

- Structuring React applications into reusable components
- Managing application state with React Hooks
- Integrating third-party libraries into a React project
- Persisting application data using `localStorage`
- Creating responsive layouts for different screen sizes
- Improving accessibility through semantic HTML and ARIA attributes
- Adding user-focused features that improve the overall experience

---

## 🧩 Challenges

One of the most interesting challenges was implementing drag-and-drop functionality while keeping the application state organised and ensuring task changes were correctly saved to `localStorage`.

Another challenge was adding features such as dark mode, tooltips, accessibility improvements, and confirmation dialogs without making the codebase difficult to maintain. This project helped me appreciate the importance of keeping components modular and responsibilities clearly separated.

---

## 🔮 Future Improvements

Possible future enhancements include:

- Task priorities
- Due dates and reminders
- Labels or categories
- Search and filtering
- Multiple Kanban boards
- User authentication
- Cloud data storage
- Keyboard shortcuts for improved accessibility

---

## 📷 Screenshots

### Desktop

> Add a screenshot here.

### Dark Mode

> Add a screenshot here.

### Mobile

> Add a screenshot here.

---

## 👤 Author

**Adam Measom**

GitHub: https://github.com/adameasom

---

If you have any feedback or suggestions, feel free to open an issue or reach out.
