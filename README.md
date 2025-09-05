# Tasks App

A simple task management application built with [Vue 3](https://vuejs.org/) and [TypeScript](https://www.typescriptlang.org/).  
This app lets you add, filter, complete, and remove tasks in a clean, responsive UI.

## Features

- **Add Tasks:** Quickly add new tasks using the input form.
- **Mark as Done:** Toggle tasks as completed or not.
- **Remove Tasks:** Delete tasks from your list.
- **Filter Tasks:** View all, completed, or pending tasks.
- **Animated List:** Smooth transitions for adding/removing tasks.
- **Accessible UI:** Built with [Pico CSS](https://picocss.com/) for a modern look.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)

### Installation

```sh
npm install
```

### Development

Start the development server:

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

To build for production:

```sh
npm run build
```

### Preview

To preview the production build:

```sh
npm run preview
```

## Project Structure

```
tasks-app/
├── public/              # Static assets
├── src/
│   ├── components/      # Vue components (TaskForm, TaskList, FilterButton)
│   ├── App.vue          # Main app component
│   ├── main.ts          # App entry point
│   ├── types.ts         # TypeScript types
│   └── style.css        # Global styles
├── index.html           # HTML entry point
├── package.json         # Project metadata & scripts
├── vite.config.ts       # Vite configuration
└── tsconfig.*.json      # TypeScript configs
```

## Attribution

This project is based on the tutorial from [w3cj/vue-tasks-app](https://github.com/w3cj/vue-tasks-app).

## Contributing

Pull requests and issues are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

---

Made with ❤️ using Vue