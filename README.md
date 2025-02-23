# Flask Usage App

## Overview
This Flask application demonstrates the use of forms, a database, and webhooks. It is a simple web application that allows users to register with their information and handles updates via webhooks.

## Project Structure
The project is organized into the following directories and files:

```
.
├── __pycache__
├── static
│   └── main.css
├── templates
│   └── register.html
├── forms.py
├── main.py
└── requirements.txt
```

- `__pycache__`: Contains compiled Python files.
- `static/main.css`: Contains the CSS styling for the application.
- `templates/register.html`: HTML template for the registration form.
- `forms.py`: Contains the form classes and validation logic.
- `main.py`: The main Flask application file where routes, database models, and webhook handling are defined.
- `requirements.txt`: List of dependencies required for the application.

## Getting Started

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/flask-usage-app.git
   cd flask-usage-app
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Running the Application
1. Start the Flask application:
   ```sh
   python main.py
   ```

2. Open your web browser and navigate to `http://127.0.0.1:5000` to access the application.


### Templates
The HTML templates are stored in the `templates` directory. The `register.html` file is an example template used for rendering forms.

### Static Files
The `static` directory contains the CSS files for styling the application. Update `main.css` to change the look and feel of the application.

## Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/my-new-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/my-new-feature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

