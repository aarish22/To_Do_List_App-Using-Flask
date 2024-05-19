# To-Do List App Using Flask

This is a simple To-Do List application built using the Flask web framework. The application allows users to add, update, and delete tasks.

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- View all tasks

## Technologies Used

- **Flask (3.0.3)**: A micro web framework for Python.
- **Flask-SQLAlchemy (3.1.1)**: Adds SQLAlchemy support to Flask applications.
- **Flask-Scss (0.5)** and **pyScss (1.4.0)**: For compiling SCSS files to CSS.
- **SQLAlchemy (2.0.29)**: An SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **Jinja2 (3.1.3)**: A templating engine for Python used with Flask.
- **Werkzeug (3.0.2)**: A WSGI utility library for Python.
- **Other utilities**: `click`, `colorama`, `greenlet`, `itsdangerous`, `MarkupSafe`, `six`, `typing_extensions`.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/aarish22/To_Do_List_App-Using-Flask.git
    cd To_Do_List_App-Using-Flask
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:
    ```sh
    python main.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000`.

## File Structure

- `main.py`: The main Python file that runs the application.
- `templates/`: Directory containing HTML templates.
- `static/`: Directory containing static files (CSS, JS).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Acknowledgements

Special thanks to the open-source community for providing the tools and libraries that made this project possible.

