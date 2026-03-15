# Todo App

A modern, beautiful todo application built with React, Vite, and TailwindCSS.

## Features

- ✨ Clean and modern UI with gradient backgrounds
- ✅ Add, complete, and delete todos
- 📊 Real-time statistics (total, pending, completed)
- 💾 Local storage persistence
- 🎨 Beautiful animations and transitions
- 📱 Responsive design
- 🌙 Dark mode support (via TailwindCSS)

## Tech Stack

- **React 18** - UI library
- **Vite** - Build tool and dev server
- **TailwindCSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **Local Storage** - Data persistence

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Navigate to the project directory:
```bash
cd /Users/abhi/CascadeProjects/todo-app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Project Structure

```
todo-app/
├── src/
│   ├── components/
│   │   ├── Button.jsx          # Reusable button component
│   │   ├── Card.jsx            # Card container components
│   │   ├── Input.jsx           # Input field component
│   │   ├── TodoInput.jsx       # Todo input form
│   │   ├── TodoItem.jsx        # Individual todo item
│   │   ├── TodoList.jsx        # List of todos
│   │   └── TodoStats.jsx       # Statistics display
│   ├── lib/
│   │   └── utils.js            # Utility functions
│   ├── App.jsx                 # Main app component
│   ├── main.jsx                # App entry point
│   └── index.css               # Global styles
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
└── postcss.config.js
```

## Usage

1. **Add a todo**: Type in the input field and click the plus button or press Enter
2. **Complete a todo**: Click the circle icon to mark as complete
3. **Delete a todo**: Hover over a todo and click the trash icon
4. **Clear completed**: Click "Clear Completed" to remove all completed todos

## Features in Detail

### Local Storage
All todos are automatically saved to browser local storage, so your data persists across sessions.

### Statistics
View real-time statistics showing:
- Total number of todos
- Pending todos
- Completed todos

### Modern UI
- Gradient backgrounds
- Smooth transitions and hover effects
- Icon-based interactions with Lucide icons
- Responsive design that works on all devices

## License

MIT

==============================================================