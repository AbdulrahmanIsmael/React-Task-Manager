# React Task Manager

A simple task management app built with React, Redux, and Vite. Create, edit, filter, and manage tasks with persistent local storage.

## Features

- ✅ Create and delete tasks
- 🎯 Priority levels (Low, Medium, High)
- 🔍 Search and filter tasks
- ✓ Mark tasks as complete
- 💾 Auto-save to local storage

## Tech Stack

- React 19
- Redux Toolkit
- Vite
- Lucide React (icons)
- Sonner (notifications)

## Installation

```bash
npm install
npm run dev
```

The app will run at `http://localhost:5173`

## Usage

1. **Add Task** - Enter a title, select priority, and click "Add Task"
2. **Search** - Use the search bar to find tasks
3. **Filter** - Select a priority level to filter tasks
4. **Complete** - Click the checkbox to mark a task as done
5. **Edit** - Click the edit icon to modify a task
6. **Delete** - Click the trash icon to remove a task

Tasks are automatically saved to browser local storage.

## Project Structure

```
src/
├── components/       # React components (FilterBar, TaskCard, TaskInput, TaskList, Header)
├── redux/           # Redux store and tasksSlice
├── App.jsx          # Main app component
└── index.jsx        # Entry point
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build
