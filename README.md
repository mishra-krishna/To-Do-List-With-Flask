# Flask Todo List App

This is a simple todo list web application built using Flask, SQLAlchemy, and SQLite.

## Description

The Flask Todo List App allows users to:

- Add new todo items with a title and description.
- View all existing todo items.
- Delete todo items.
- Update todo items.

The application uses SQLAlchemy to interact with a SQLite database to store todo items.

## Usage

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Install Dependencies**: Ensure you have Python installed. You can install Flask and SQLAlchemy using pip:

3. **Run the App**: Navigate to the project directory and run the app using the following command:

4. **Access the App**: Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to access the todo list app.

5. **Interact with the App**: You can add, view, update, and delete todo items using the provided web interface.

## Files

- `app.py`: Main Flask application script containing routes and database models.
- `templates/`: Directory containing HTML templates for the web pages.
- `home.html`: Template for the todo list homepage.
- `update.html`: Template for updating a todo item.

## Database

The application uses a SQLite database named `todo.db` located in the `instance/` directory. SQLAlchemy is used to interact with the database.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

