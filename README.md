# MERN Stack Example Application

This is a simple MERN (MongoDB, Express, React, Node.js) stack application that allows users to add, view, and delete notes.

## Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (Node package manager)
- [MongoDB](https://www.mongodb.com/) (v4 or later)


## Getting Started

Follow these steps to set up and run the application.

### Clone the Repository

```sh
git clone https://github.com/NatnaeAssefa/mern-example.git
cd mern-example
```
### Set Up the Backend

Install Backend Dependencies

```sh
npm install
```

### Start MongoDB

Make sure MongoDB is installed and running on your local machine. You can start MongoDB using the following command:

```sh
mongod
```

This will start MongoDB on the default port 27017.

### Start the Backend Server

Use the following command to start the backend server:

```sh
npm start
```

This will start the server on http://localhost:5000.

### Set Up the Frontend

1. Navigate to the client Directory

```sh
cd client
```

2. Install Frontend Dependencies

```sh
npm install
```

3. Start the Frontend Development Server

Use the following command to start the React development server:

```sh
npm start
```

This will start the frontend on http://localhost:3000.

### Using the Application

1. Open the Application in Your Browser

Navigate to http://localhost:3000 in your web browser.

2. Add, View, and Delete Notes

- To add a note, enter a title and content in the input fields and click "Add Note".
- To view notes, simply open the application; all notes will be displayed.
- To delete a note, click the "Delete" button next to the note you want to remove.

## Project Structure

- index.js: The main entry point for the backend server.
- models/: Contains the Mongoose model for the notes.
- routes/: Contains the API routes for the notes.
- client/: Contains the React frontend application.
- src/App.js: The main React component.


## Troubleshooting

- MongoDB Connection Issues

If you encounter issues connecting to MongoDB, ensure that MongoDB is running on your machine and is accessible on the default port 27017. You can verify this by running mongo in a separate terminal window.

- Port Conflicts

If there are port conflicts, you can change the ports in the backend and frontend configurations. For the backend, update the PORT variable in index.js. For the frontend, update the package.json script to use a different port.


## Acknowledgements

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [React](https://reactjs.org/)
