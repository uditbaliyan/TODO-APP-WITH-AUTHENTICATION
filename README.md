

# TODO App with Authentication

A Django-based TODO application that allows users to manage their tasks with user authentication.

## Features

- User authentication: Sign up, log in, and log out.
- Create, read, update, and delete tasks.
- Mark tasks as complete or incomplete.
- User-specific task management.

## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x
- pip
- Django

### Clone the Repository

```bash
git clone https://github.com/uditbaliyan/TODO-APP-WITH-AUTHENTICATION.git
cd TODO-APP-WITH-AUTHENTICATION
```

### Set Up Virtual Environment

It's a good practice to use a virtual environment to manage dependencies. You can create one using `venv`.

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py migrate
```

### Create a Superuser

Create a superuser to access the admin panel.

```bash
python manage.py createsuperuser
```

### Run the Server

```bash
python manage.py runserver
```

Navigate to `http://127.0.0.1:8000` in your browser to see the application in action.

## Usage

1. Register or log in to manage your tasks.
2. Add new tasks by providing the required details.
3. View the list of all tasks.
4. Edit, delete, or mark tasks as complete/incomplete as needed.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Django](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/) for front-end design

