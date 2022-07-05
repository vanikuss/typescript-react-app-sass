Creating a TypeScript app
You can start a new TypeScript app using templates. To use our provided TypeScript template, append --template typescript to the creation command.

npx create-react-app my-app --template typescript
If you already have a project and would like to add TypeScript, see our Adding TypeScript documentation.

Selecting a package manager
When you create a new app, the CLI will use npm or Yarn to install dependencies, depending on which tool you use to run create-react-app. For example:

# Run this to use npm
npx create-react-app my-app
# Or run this to use yarn
yarn create react-app my-app
Output
Running any of these commands will create a directory called my-app inside the current folder. Inside that directory, it will generate the initial project structure and install the transitive dependencies:

my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── serviceWorker.js
    └── setupTests.js
No configuration or complicated folder structures, only the files you need to build your app. Once the installation is done, you can open your project folder:

cd my-app
Scripts
Inside the newly created project, you can run some built-in commands:

npm start
