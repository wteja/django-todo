# Todo Project

## Description
This is a simple Todo application that helps you manage your tasks efficiently.

## Features
- Add new tasks
- Mark tasks as completed
- Delete tasks
- View all tasks

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/wteja/todo_project.git
    ```
2. Navigate to the project directory:
    ```sh
    cd todo_project
    ```
3. Create a virtual environment:
    ```sh
    python -m venv env
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source env/bin/activate
        ```
5. Install dependencies:
    ```sh
    pip install django
    ```

## Usage
1. Apply migrations:
    ```sh
    python manage.py migrate
    ```
2. Start the development server:
    ```sh
    python manage.py runserver
    ```
3. Open your browser and go to `http://localhost:8000`

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License
This project is licensed under the MIT License.
