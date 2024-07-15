#  Intel Unnati-Project(Protecting User Password Keys at rest (on the Disk)



## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/project.git
    cd project
    ```

2. Set up a virtual environment (optional but recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up PostgreSQL:
    - Create a new PostgreSQL database.
    - Update `SQLALCHEMY_DATABASE_URI` in `config.py` with your database credentials.

5. Export the Flask app environment variable:
    ```bash
    export FLASK_APP=app.py
    ```

## Usage

1. Run the Flask application:
    ```bash
    flask run
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/` to access the application.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
