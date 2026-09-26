Web Development Mini Project 3: React To-Do & Notes Suite

A full-fledged productivity web application built using React.js and modern ES6+ JavaScript. It features both a Task Management (To-Do) application and a Notes Application styled with Tailwind CSS.

🌟 Features Implemented

1. To-Do App

Task Management: Add, edit (inline), toggle completion, and delete tasks.

Status Indicators: Visual badges indicating whether a task is Completed or Pending.

Due Dates: Attach completion target dates to tasks.

Filtering: Filter tasks by status (All, Pending, Completed).

Persistence: Synchronizes state with localStorage so tasks persist across page refreshes.

2. Notes App

Note Operations: Create, edit, and delete notes.

Timestamps: Automatic timestamp generation when notes are created or updated.

Categorization: Classify notes into categories (General, Work, Study, Personal).

Live Search & Filter: Instant search filter by keywords and category filtering.

Responsive Grid Layout: Auto-adjusting multi-column grid layout for desktop and mobile views.

Persistence: Synchronizes notes with localStorage.

⚛️ React & JavaScript Concepts Applied

React Core Concepts

Functional Components: Component architecture breaking down UI sections.

State Management (useState): Local state for form inputs, lists, edit tracking, and active tabs.

Side Effects (useEffect): Automatic synchronization with browser LocalStorage upon state change.

Props & Event Handling: Handling user interaction events (onSubmit, onClick, onChange).

Conditional Rendering: Dynamically swapping components and rendering fallback empty-state UI.

List Rendering: Dynamic list rendering using JavaScript .map() with React key bindings.

ES6+ JavaScript Concepts

Arrow Functions: Concise functions for handling callbacks and event listeners.

Destructuring: Extracting state values and component parameters.

Spread Operator (...): Immutable state updates when adding items or modifying arrays.

Array Methods: .map(), .filter(), and .find() for filtering, editing, and listing data.

Template Literals: Formatted strings for dates and class concatenation.

📁 Suggested Modular Component File Structure (for Vite/CRA)

If modularizing this single-file implementation into a conventional React project structure:

src/
├── assets/
│   └── logo.svg
├── components/
│   ├── TodoApp.jsx
│   ├── TodoItem.jsx
│   ├── NotesApp.jsx
│   └── NoteCard.jsx
├── App.jsx
├── main.jsx
└── index.css


🚀 Setup Instructions

Standalone Execution:

Open index.html directly in any web browser. No npm or build system required.

Run in React Development Server (Optional):

Initialize a new project: npm create vite@latest my-app -- --template react

Copy the React code into src/App.jsx.

Run npm install and npm run dev.
