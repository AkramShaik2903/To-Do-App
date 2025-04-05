# To-Do List Application

A simple and interactive To-Do List application built using **Spring Boot** for the backend, **Thymeleaf** for templating, **Bootstrap** for responsive UI, and **PostgreSQL** for database persistence.

## Features

- **Add Task**: Allows users to add tasks.
- **Edit Task**: Edit existing tasks.
- **Delete Task**: Remove tasks.
- **Mark as Completed**: Toggle between completed and pending.
- **Task Persistence**: Saved in a PostgreSQL database.
- **Responsive UI**: Built with **Bootstrap**.

## Technologies Used

- **Backend**: Spring Boot, Thymeleaf, Spring Data JPA, PostgreSQL
- **Frontend**: HTML, CSS, Bootstrap

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AkramShaik2903/To-Do-App.git
    ```

2. Set up PostgreSQL:
    ```sql
    CREATE DATABASE todo_app;
    ```

3. Configure `application.properties` for database connection.

4. Build and run:
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

5. Access the app at `http://localhost:8080`.

## Usage

1. Add tasks, edit them, delete, and mark them as completed.
2. Persistent tasks using PostgreSQL.

## Contributing

1. Fork the repository.
2. Create a new branch.
3. Commit changes and create a pull request.

## License

MIT License - see LICENSE file.
