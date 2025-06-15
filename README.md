# Todo App API

A RESTful API for a Todo application built with Node.js, Express, and MongoDB.

## Features

- Create, read, update, and delete todos
- MongoDB database integration
- RESTful API endpoints
- CORS enabled
- Security headers included

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/todo-app.git
cd todo-app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following content:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/todo-app
```

## Running the Application

Development mode:
```bash
npm run dev
```

Production mode:
```bash
npm start
```

## API Endpoints

- `GET /api/todos` - Get all todos
- `POST /api/todos` - Create a new todo
- `PUT /api/todos/:id` - Update a todo
- `DELETE /api/todos/:id` - Delete a todo

## License

MIT 