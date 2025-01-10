# Postly

Postly is a social media web application built using the Django framework. It leverages Django's powerful features to provide user authentication, tweet creation, editing, and deletion functionalities. Users can register, log in, and manage their posts seamlessly. The project also includes media handling for user-uploaded files and static file management for efficient content delivery.

## Features

- User registration and authentication
- Create, edit, and delete tweets
- Media handling for user-uploaded files
- Static file management

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/postly.git
    cd postly
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv myenv
    myenv\Scripts\activate  # On Windows
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```bash
    python manage.py runserver
    ```

7. Open your browser and go to `http://127.0.0.1:8000/` to see the application.

## Usage

- Register a new user account.
- Log in with your credentials.
- Create, edit, and delete tweets.
- Upload media files with your tweets.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
