# CRUD-1-Read

## About
This project is a simple CRUD (Create, Read, Update, Delete) application built using Node.js and Express. It serves as a basic template to set up a server, create routes, and handle GET requests.

![image](https://github.com/pujaroy280/CRUD-1-Read/assets/62675121/0e504f60-14ac-4c03-9fa3-f5149e087f4a)

## Technologies
- Node.js
- Express
- Nodemon (for development)

**IDE/Editor:** [Visual Studio Code]

**Terminal:** [Git Bash]

## Getting Started
The project is designed to help you set up a basic server and create a GET endpoint. Follow the steps below to get started:

### Step 1 - Set up your server
1. Create a project folder.
2. Run `npm init` to initiate a Node project and generate a `package.json`.
3. Create a `server.js` file and add the provided code.
4. Install Express using `npm install express --save`.
5. Run `node server.js` to test the server at [localhost:3000](http://localhost:3000).

### Step 2 - Create your GET endpoint
1. Add a GET endpoint in `server.js` to handle requests to the root path `/`.
2. Send a basic text file or HTML file as the response.

### Step 3 - Create your index.html
1. Create an `index.html` file in your project.
2. Add your HTML content to `index.html`.
3. Point to the HTML file in `server.js` using `res.sendFile(__dirname + '/index.html')`.

### Step 4 - Configure Nodemon
1. Install Nodemon using `npm install nodemon --save-dev`.
2. Add `"dev": "nodemon server.js"` to the `scripts` property in `package.json`.
3. Run `npm run dev` to use Nodemon for automatic server restart during development.

## Installation
To install and run the project, follow these steps:
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project folder: `cd <project-folder>`
3. Install dependencies: `npm install`
4. Run the server: `npm run dev`

Make sure to save your files after each major change and enjoy developing your CRUD application!
