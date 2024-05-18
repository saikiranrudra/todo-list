## Todos API
Todos REST API with Node.js, Express.js, and MongoDB

## Endpoints:

    - **`GET /todos`**: Retrieve all todos, you can pass a limit and page to perform the pagination with notes list **`GET /notes?limit=Limit&page=PAGE`**.
    
    - **`POST /todos`**: Add a new todo.
    
    - **`DELETE /todos/:id`**: Delete a specific todo using its ID.
    
    - **`PUT /todos/:id`**: Update a specific todo using its ID.
    
    - **`GET /todos?title=TITLE`**: Search notes by their title or content, search as startWith function.
    
 ## Libraries Used

In this project, I've used the following libraries:

- **dotenv:** A zero-dependency module that loads environment variables from a `.env` file into `process.env`. [dotenv](https://www.npmjs.com/package/dotenv)
- **Express:** A fast, unopinionated, minimalist web framework for Node.js. [Express](https://expressjs.com/)
- **Mongoose:** A MongoDB object modeling tool designed to work in an asynchronous environment. [Mongoose](https://mongoosejs.com/)
- **Nodemon:** A utility that monitors for any changes in your source and automatically restarts your server. [Nodemon](https://nodemon.io/)

Please refer to the documentation of each library for more information on how to use them.

   
