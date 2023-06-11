<div align="center">
  <h1><b>Little Lemon API</b></h1>
</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
  - [Key Features](#key-features)
  - [Project Structure](#project-structure)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show Your Support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

# 📖 Little Lemon API <a name="about-project"></a>

Little Lemon API is a fully functioning API project for the Little Lemon restaurant. It provides endpoints for managing menu items, placing orders, and assigning delivery crew to orders.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

- Django
- Django REST Framework
- PostgreSQL
- SQLlite3

### Key Features <a name="key-features"></a>

- **Menu Items Management**: Allows users to browse, add, edit, and delete menu items.
- **Order Management**: Enables users to place orders and browse order history.
- **Delivery Crew Management**: Supports assignment of delivery crew to orders.

### Project Structure <a name="project-structure"></a>

The Little Lemon API project follows the following structure:

- `LittleLemonAPI/`: Django project root directory.
  - `api/`: Django app directory for the API implementation.
    - `migrations/`: Database migration files.
    - `views.py`: Contains the API views and endpoints.
    - `models.py`: Defines the database models.
  - `littlelemonapi/`: Django app settings and configurations.
  - `requirements.txt`: Lists the project dependencies.
  - `manage.py`: Django management script.

# 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

## Prerequisites <a name="prerequisites"></a>

- Python (3.8 or higher)
- SQLite3 database

## Installation <a name="installation"></a>

1. Clone this repository:

   ```sh
   git clone https://github.com/your-username/little-lemon-api.git
   ```

2. Navigate to the project directory:

   ```sh
   cd little-lemon-api
   ```

3. Install the project dependencies:

   ```sh
   pip install -r requirements.txt
   ```

4. Set up the PostgreSQL database and configure the database settings in `littlelemonapi/settings.py`.

5. Apply the database migrations:

   ```sh
   python manage.py migrate
   ```

## Usage <a name="usage"></a>

1. Start the development server:

```sh
   python manage.py runserver
   ```

2. The API will now be accessible at `http://localhost:8000/`. You can use tools like cURL, Postman, or your web browser to make requests to the API endpoints.

## Testing <a name="testing"></a>

To run the tests for the Little Lemon API, execute the following command:

```sh
python manage.py test
```

This will run the test suite and display the test results.

## Deployment <a name="deployment"></a>

To deploy the Little Lemon API to a production environment, follow these general steps:

1. Set up a production server with the necessary infrastructure (e.g., a cloud server, containerization platform, etc.).

2. Configure the production server environment variables, including database settings and any required secret keys.

3. Set up a web server (e.g., Nginx, Apache) to handle incoming requests and forward them to the API.

4. Configure the web server to serve the static files and proxy the API requests to the appropriate port (e.g., 8000).

5. Set up a process manager (e.g., Supervisor, systemd) to keep the API process running and handle process management.

6. Configure any necessary security measures, such as SSL certificates for HTTPS.

7. Deploy the codebase to the production server and start the API process.

8. Monitor the API for any issues and ensure that backups and security measures are in place.

# 👥 Authors <a name="authors"></a>

- Evans Kupour - [@evanskupour](https://github.com/Doheera-kosi/)


# 🔭 Future Features <a name="future-features"></a>

- Add support for user authentication and authorization.
- Implement email notifications for order updates.
- Integrate with a payment gateway for online payments.
- Implement real-time order tracking using websockets.

# 🤝 Contributing <a name="contributing"></a>

Contributions are welcome! To contribute to the Little Lemon API project, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and commit them with descriptive commit messages.

4. Push your changes to your forked repository.

5. Submit a pull request detailing your changes and why they should be merged.

6. Wait for the maintainers to review and provide feedback on your pull request.

# ⭐️ Show Your Support <a name="support"></a>

If you find the Little Lemon API project helpful or interesting, please consider giving it a star on [GitHub](https://github.com/your-username/little-lemon-api). Your support is greatly appreciated!

# 🙏 Acknowledgements <a name="acknowledgements"></a>

- Hat tip to anyone whose code was used as inspiration.
- Thanks to the Little Lemon team for their valuable feedback and contributions.

# 📝 License <a name="license"></a>

This project is licensed under the [MIT License](LICENSE).
```
