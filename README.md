
## Docs

- https://thepythoncode.com/article/fullstack-notes-app-with-fastapi-and-reactjs

# Backend

- https://github.com/menard-codes/NotesAppBackend-FastAPI-React

## React + Vite


React is a popular JavaScript library for building user interfaces, particularly single-page applications. Vite, on the other hand, is a modern build tool that aims to provide a faster and leaner development experience for modern web projects. It leverages native ES modules and esbuild to offer extremely fast Hot Module Replacement (HMR) and efficient builds. Using React with Vite can significantly improve the development experience by providing instant feedback and quick build times.

Setting up a React project with Vite
To get started with a React project using Vite, you can follow these steps:

Install Node.js: Ensure you have Node.js installed on your machine. Vite requires Node.js (version 12.0.0 or higher).

Create a new project: Use the Vite CLI to create a new project. If you haven't installed the Vite CLI globally, you can do so or use npx to run the command without installing it globally. To create a new React project, run:

```bash
npm create vite@latest my-react-app -- --template react
```

or if you prefer Yarn:

```bash
yarn create vite my-react-app --template react
```

Replace my-react-app with your project name.

Navigate to your project directory:

```bash
cd my-react-app
```

Install dependencies: If your project setup doesn't automatically install dependencies, you can do so by running:

```bash
npm install
```

or if you are using Yarn:

```bash
yarn
```
Run the development server:

```bash
npm run dev
```

or with Yarn:
```bash
yarn dev
```

This command will start the development server, typically available at http://localhost:3000. You can now edit your project files, and the changes will be reflected in real-time in your browser.

Advantages of Using Vite with React
Fast HMR: Vite provides extremely fast Hot Module Replacement, which makes the development experience smoother by updating the modules in the browser as you make changes to the code without a full page reload.
Efficient Builds: Vite uses Rollup for its final production builds, which results in optimized and efficient bundling.
Out-of-the-box TypeScript, JSX, CSS Support: Vite comes with built-in support for TypeScript, JSX, and CSS, among other web technologies, without the need for additional setup.
Easier Configuration: Vite aims to provide sensible defaults while also being highly configurable through its vite.config.js file. This can make setting up and customizing your build process simpler compared to other build tools.
Next Steps
After setting up your project, you might want to explore:

Adding CSS pre-processors like Sass or Less, which Vite supports out of the box.
Configuring vite.config.js to customize the build process, proxy API requests during development, or integrate additional plugins.
Adding routing to your React application using React Router.
Integrating state management solutions like Redux or Zustand.
Vite's ecosystem is growing, and its simplicity, speed, and the developer-friendly approach make it an excellent choice for modern web development projects, including those using React.


  

  
