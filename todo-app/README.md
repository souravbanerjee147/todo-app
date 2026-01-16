# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.











# To-Do List Application - React

A beautiful, feature-rich To-Do List application built with React and Vite. This application allows users to manage their tasks efficiently with a modern, responsive design and theme toggle functionality.

![React](https://img.shields.io/badge/React-18.2-blue)
![Vite](https://img.shields.io/badge/Vite-4.5-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- **Add, Edit, Delete Tasks** - Full CRUD functionality
- **Mark Tasks as Completed** - Toggle completion status
- **Persistent Storage** - Tasks saved in localStorage
- **Dark/Light Mode** - Theme toggle with system preference detection
- **Fully Responsive** - Works on all screen sizes
- **Task Statistics** - Real-time counters for total, completed, and pending tasks
- **Clean UI** - Modern design with smooth animations
- **Input Validation** - Character limits and empty checks
- **Clear All/Completed** - Bulk delete functionality
- **Auto-Save** - Tasks automatically saved


## 🛠️ Tech Stack

- **React** - Frontend library
- **Vite** - Build tool and development server
- **CSS3** - Custom styling with CSS variables
- **LocalStorage** - Client-side data persistence
- **ES6+** - Modern JavaScript features

## 📁 Project Structure

```
todo-app/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── ToDoList.jsx
│   │   ├── ToDoItem.jsx
│   │   ├── AddTodo.jsx
│   │   └── ThemeToggle.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── App.css
├── public/
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🔧 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/your-username/todo-app.git
cd todo-app
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev

```

4. **Open your browser**
Navigate to `http://localhost:5173`

## 📦 Build for Production

```bash
npm run build

```

To preview the production build:
```bash
npm run preview

```

## 🎮 How to Use

### Adding a Task
1. Type the task in the input field
2. Press "Enter" or click "Add Task"
3. Maximum 100 characters allowed

### Managing Tasks
- **Complete Task**: Click the checkbox
- **Edit Task**: Click "Edit", modify text, click "Save"
- **Delete Task**: Click "Delete"
- **Clear Completed**: Click "Clear Completed Tasks"
- **Clear All**: Click "Clear All Tasks"

### Theme Toggle
- Click the theme toggle button (🌙/☀️) in the top-right corner
- Theme preference is saved automatically
- Respects system preference on first visit

## 📊 Features in Detail

### 1. Task Management
- Add new tasks with character validation
- Mark tasks as complete/incomplete
- Edit existing tasks inline
- Delete individual tasks
- Bulk clear options

### 2. Data Persistence
- All tasks saved to localStorage
- Theme preference saved
- Data persists across browser sessions
- Auto-save on every change

### 3. Responsive Design
- Mobile-first approach
- Adaptive layout for all screen sizes
- Touch-friendly buttons on mobile
- Print-friendly styles

### 4. Theme System
- Light and dark modes
- Smooth transitions
- System preference detection
- Manual override option

## 🔗 API Reference (LocalStorage)

The app uses localStorage with the following keys:

- `todos`: Array of task objects
- `theme`: Current theme ('light' or 'dark')

Task object structure:
```javascript
{
  id: number,          // Unique timestamp ID
  text: string,        // Task description
  completed: boolean,  // Completion status
  createdAt: string    // ISO date string
}
```

## 🧪 Testing

### Manual Testing Checklist
- Add new tasks
- Mark tasks as completed
- Edit existing tasks
- Delete tasks
- Toggle theme
- Refresh page (data persistence)
- Responsive layout
- Input validation
- Clear all/completed buttons

## 🚀 Deployment

### Deploy to Vercel
```bash
npm install -g vercel
vercel
```

### Deploy to Netlify
1. Push to GitHub
2. Connect repository on Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`


## 🎯 Extra Features (Beyond Requirements)

- **Theme Toggle** (Dark/Light mode)
- **LocalStorage Persistence**
- **Task Statistics**
- **Input Validation & Character Counter**
- **Bulk Delete Options**
- **Responsive Design**
- **Smooth Animations**
- **Print Styles**

## 🐛 Known Issues & Limitations

1. **No Backend**: Tasks are stored locally only
2. **No User Authentication**: Single-user only
3. **No Due Dates**: Basic task management only
4. **No Categories/Tags**: Simple list structure

## 🔮 Future Enhancements

- Due dates and reminders
- Task categories/tags
- Drag-and-drop reordering
- Search and filter functionality
- Export/Import tasks
- Sync with cloud storage
- PWA capabilities
- Unit tests

## 👥 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- [React Documentation](https://reactjs.org/)
- [Vite Documentation](https://vitejs.dev/)
- [Inter Font](https://rsms.me/inter/)
- [Color Palettes](https://tailwindcss.com/docs/customizing-colors)

## 📧 Contact

Your Name - Sourav Banerjee 

Project Link: https://github.com/souravbanerjee147/todo-app

## ⭐ Show your support

Give a ⭐️ if this project helped you!

---

*Built with ❤️ using React + Vite*