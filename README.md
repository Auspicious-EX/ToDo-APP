# Todo App

This repository contains a simple Todo app built using React and Tailwind CSS. The app allows users to manage their tasks by adding, editing, marking as completed, and deleting them. The tasks persist even after reloading the browser, thanks to local storage.

## Features

- **Add Todos**: Easily add new tasks to your list.
- **Edit Todos**: Modify existing tasks as needed.
- **Mark as Completed**: Check off tasks that you've completed.
- **Delete Todos**: Remove tasks that are no longer relevant.
- **Data Persistence**: All tasks are saved locally, so they persist even after a page reload.

## Tech Stack

- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling the app.
- **React Icons**: A collection of popular icons for React.
- **UUID**: A library to generate unique IDs for each todo item.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js (v14 or later)
- npm (v6 or later) or Yarn

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Run the Development Server:**

   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

### Important Commands

Before running the app, make sure to execute the following commands:

1. **Vite React:**

   ```bash
   npm create vite@latest todo-app --template react
   ```

2. **Tailwind CSS:**

   ```bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   ```

   Configure `tailwind.config.js`:

   ```javascript
   module.exports = {
     content: ['./src/**/*.{js,jsx,ts,tsx}', './public/index.html'],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

   Include Tailwind in your CSS:

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

3. **React Icons:**

   ```bash
   npm install react-icons --save
   ```

4. **UUID:**

   ```bash
   npm install uuid
   ```

### Folder Structure

```plaintext
todo-app/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── TodoItem.js
│   │   └── TodoList.js
│   │
│   ├── App.js
│   ├── index.js
│   └── styles/
│       └── index.css
│
├── tailwind.config.js
└── package.json
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Contact

For more projects, visit my [GitHub](https://github.com/Auspicious-EX).
Check out my portfolio at [auspicious.me](https://auspicious.me).

