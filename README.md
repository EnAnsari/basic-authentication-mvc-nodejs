# Node.js MVC Authentication Project

This is a Node.js project implementing a Model-View-Controller (MVC) architecture with authentication operations. The project uses `Express` for the web framework, `Sequelize` for ORM with `SQLite3` as the database, and `Passport` with `bcryptjs` for authentication.

## Modules Used

- **Express**: Web framework for building the application.
- **Express-Session**: Middleware for session management.
- **Pug**: Templating engine for rendering views.
- **Sequelize**: ORM for database operations.
- **SQLite3**: Database engine.
- **Bcryptjs**: Library for hashing passwords.
- **Passport**: Authentication middleware.
- **Passport-Local**: Passport strategy for username and password authentication.

## Tutorial

This project is based on a tutorial from [LogRocket Blog](https://blog.logrocket.com/). 

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Installation

To get started with this project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/EnAnsari/basic-authentication-mvc-nodejs
    ```

2. **Navigate to the project directory:**

    ```bash
    cd basic-authentication-mvc-nodejs
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Create and configure the database:**

The project uses SQLite3. By default, a database file will be created in the root directory when you run the application.

5. **Create a `.env` file:**

Create a `.env` file in the root directory of your project and add the necessary environment variables. For example:

```env
SESSION_SECRET=your-session-secret
```

Adjust these settings according to your needs.

## Running the Application

To start the application, use the following command:

```bash
npm start
```

By default, the application will run on `http://localhost:8080`.

## Usage

+ **Authentication**: Users can register, log in, and manage their sessions.
+ **MVC Structure**: The application follows the MVC architecture.
    + **Model**: Defines the data structure and interacts with the database.
    + **View**: Renders the HTML using Pug templates.
    + **Controller**: Contains the logic for handling user requests and responses.


## Contributing

We welcome contributions to improve the project! If you'd like to contribute, please follow these steps:

1. **Fork the repository** on GitHub.
2. **Clone your fork**:
    ```bash
    git clone https://github.com/EnAnsari/basic-authentication-mvc-nodejs
    ```

3. **Create a new branch** for your feature or bugfix:
    ```bash
    git checkout -b feature/your-feature
    ```

4. **Make your changes** and commit them:
    ```bash
    git add .
    git commit -m "Add your message here"
    ```

5. **Push your changes** to your fork:
    ```bash
    git push origin feature/your-feature
    ```

6. **Submit a Pull Request** on GitHub, describing your changes and any relevant information.

## Contact

For any questions or feedback, please reach out to [Rahmat2022a@gmail.com](mailto:rahmat2022a@gmail.com).