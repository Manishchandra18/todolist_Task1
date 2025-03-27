# MERN To-Do List App

A simple To-Do List application built using the MERN (MongoDB, Express, React, Node.js) stack. This application allows users to add, update,mark and delete tasks  while also providing a theme-switching toggle for a better user experience.

## Features
- Add a new To-Do
- Update existing To-Dos
- Delete To-Dos
- Toggle between Light and Dark mode
- Responsive UI

## Technologies Used
### Frontend:
- React.js
- Tailwind CSS / CSS Modules (for styling)
- Axios (for API requests)

### Backend:
- Node.js
- Express.js
- MongoDB (with Mongoose ORM)

## Installation and Setup
### Prerequisites
Make sure you have the following installed on your system:
- Node.js
- MongoDB


### Frontend Setup
```sh
cd ../frontend
npm install
```

#### Start the Frontend
```sh
npm start
```

The frontend will run on `http://localhost:3000` and the backend on `http://localhost:8000`.

## API Routes
### Base URL: `http://localhost:8000/api/todos`
- **GET** `/` - Fetch all todos
- **POST** `/` - Add a new todo (requires `{ title: "task name" }` in the request body)
- **PUT** `/:id` - Update a todo
- **DELETE** `/:id` - Delete a todo


## Contributing
Contributions are welcome! Feel free to submit a pull request.

## License
This project is licensed under the MIT License.



