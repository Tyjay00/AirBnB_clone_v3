# Flask Web Application API

## Overview
This repository contains a Flask web application API.

## Features
- Flask web application with RESTful API endpoints.
- Integration with CORS for cross-origin resource sharing.
- Error handling for 404 and 400 HTTP error codes.
- Usage of Flask blueprints for modular organization.

## Getting Started
### Prerequisites
- Python 3.x
- Flask
- Flask-CORS

### Installation
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`

### Usage
1. Run the application: `python3 your_app_file.py`
2. Access the API at `http://localhost:5000/`

## API Endpoints
- The API exposes endpoints for various functionalities. Refer to the code in the `api/v1/views` directory for details.

## Configuration
- The application is configurable using environment variables.
  - `HBNB_API_HOST`: Host for the Flask application (default is `0.0.0.0`).
  - `HBNB_API_PORT`: Port for the Flask application (default is `5000`).

## Error Handling
- The application handles 404 and 400 HTTP error codes with appropriate error messages.

## Contributing
- Feel free to contribute by opening issues or submitting pull requests.

