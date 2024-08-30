npm install vite@latest

This will download the latest version of Vite.

# Setup React App
Now, let's set up our React app!

Run the following command:

npm create vite@latest

This will begin with a set of prompts that you'll need to fill out to create the app.

The first asks what you want to name your project. Maybe something like my-first-app?

Prompt to name Vite project

Next, you'll be asked what kind of app you want to make. Use the arrow keys to go to "React" and select with enter.

Prompt to select React

Note: With Vite, you can make more than just a React app. Even ones in Vue or Svelte!

You'll then be asked whether you want the React app set up with TypeScript or regular JavaScript. Let's go for just JavaScript.

Prompt to select JavaScript

But wait, what about this "SWC" thing? This stands for "Speedy Web Compiler" and it allows your code to get processed a little quicker. For this tutorial, it doesn't matter if you select it.

# Run React App
After this point, everything should be set and Vite will print directions for how to run your React app!

First, use the cd command to change into the new Vite folder you made:

cd my-first-app

Next, run the following npm command:

npm install

Just like how we are using Vite as a tool, Vite itself uses tools, or dependencies, to work as expected. Similar to booting up a game console, running npm install starts up these dependencies so that Vite can work.

Lastly, we will run this command:

npm run dev

Vite will now build up our app and then serve it with a localhost link, similar to this:

Served React app, as seen from terminal

If we copy/paste this link on a browser, we should see the following output:

Served React app, as seen from the browser

To copy/paste, here are the keyboard shortcuts:

For Mac:

Copy: cmd + c
Paste: cmd + v
Windows:

Copy: ctrl + c
Paste: ctrl + v
# Vite App Structure
When creating a new React project, Vite sets up all the files and folders usually needed. This way, we can get right to building.

If we open our my-first-app folder in an editor like VS Code, the following files and folders are usually found:

📂 src/
📄 App.jsx: The code for the <App> component, written in JavaScript Syntax Extension (JSX).
📄 index.css: The base styles for the React app.
📄 index.html: The place where the root of the React app (i.e., <div id="root"></div>).
📄 package.json: A list of the outside code used to make this app run, including react, react-dom, and vite.
📄 vite.config.js: The settings for our Vite React app.
Inside most Vite React apps, there is a src folder (short for "source") that contains all the source code, including .jsx files.

In the package.json file, we'll find:

"dependencies": {
  "react": "^18.0.0",
  "react-dom": "^18.0.0"
}

The "react" package lets you write React code.
The "react-dom" package lets you render that React code.
# Conclusion