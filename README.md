




https://github.com/user-attachments/assets/c916cac8-be48-4aaa-afec-22e94ed21c4a


# 🌍 WeatherWorld Website

📝 **Contents**
- [🌟 Introduction](#-introduction)
- [💻 Technologies Used](#-technologies-used)
- [✨ Key Features](#-key-features)
- [🗂️ Project Structure](#️-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🔑 API Key Management](#-api-key-management)
- [🤝 Contributing](#-contributing)
- [📧 Contact Information](#-contact-information)

## 🌟 Introduction
Welcome to the **WeatherWorld Website**, a modern, web-based application that provides 🌦️ real-time weather updates and 📅 forecasts for various locations across the globe. Built on the Developer Plan of the OpenWeatherMap API, this application offers users comprehensive weather data through a clean and intuitive interface.

## 💻 Technologies Used
- **🐍 Python**: Core language for backend development.
- **🌐 Flask**: A minimalistic web framework for Python, powering the backend.
- **🎨 Bootstrap 5**: A front-end framework for designing responsive and mobile-first websites.
- **🗄️ SQLite**: A lightweight, file-based database system used to store user data and application settings.
- **⚙️ Flask-Migrate**: Facilitates database migrations in the Flask application.
- **🛠️ Flask-SQLAlchemy**: Adds SQLAlchemy ORM support to Flask, enabling seamless database interactions.
- **📡 Requests**: Handles HTTP requests, enabling API communication.

## ✨ Key Features
- **📡 Live Weather Data**: Get current weather information for any location.
- **📅 Forecasts**: Hourly and weekly weather forecasts are available.
- **🎛️ Intuitive Design**: User-friendly and responsive UI for easy navigation.
- **🌞 Environmental Insights**: Provides additional data like the UV index to promote environmental awareness.

## 🗂️ Project Structure
- **`app.py`**: The main Flask application file, containing all the routes and application logic.
- **`models.py`**: Defines the data models for the application.
- **`templates/`**: Directory housing all HTML templates for the web pages.
- **`static/`**: Contains static assets such as CSS, JavaScript, and images.
- **`requirements.txt`**: Lists all Python dependencies required for the project.

## 🚀 Getting Started
To run the project locally, follow these steps:

1. **📥 Clone the repository:**
    ```bash
    git clone [https://github.com/OKihichak/weather_world_website.git]
    cd weather-world_website
    ```

2. **⚙️ Create and activate a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # For Windows use venv\Scripts\activate
    ```

3. **📦 Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **🔧 Configure environment variables:** Set the `SECRET_KEY` and `OPENWEATHERMAP_API_KEY` in your environment.
    ```bash
    export SECRET_KEY='your_secret_key_here'
    export OPENWEATHERMAP_API_KEY='your_openweathermap_api_key_here'
    ```

5. **▶️ Run the application:**
    ```bash
    python app.py
    ```

6. **🌐 Access the application:** Open your web browser and go to `http://localhost:5000`.

## 🔑 API Key Management
To keep your API keys secure, they should be stored in environment variables rather than hardcoded in your source code. Here’s how to do it:

- **💻 On Unix/Linux/macOS:**
    ```bash
    export SECRET_KEY='your_secret_key_here'
    export OPENWEATHERMAP_API_KEY='your_openweathermap_api_key_here'
    ```

- **🪟 On Windows:**
    ```bash
    set SECRET_KEY=your_secret_key_here
    set OPENWEATHERMAP_API_KEY=your_openweathermap_api_key_here
    ```

Always ensure that these keys are excluded from your version control system. 🔒

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

1. **🍴 Fork the repository.**
2. **🌿 Create a new branch:**
    ```bash
    git checkout -b feature/YourFeatureName
    ```
3. **💻 Make your changes and commit them:**
    ```bash
    git commit -m 'Add YourFeatureName'
    ```
4. **🚀 Push to the branch:**
    ```bash
    git push origin feature/YourFeatureName
    ```
5. **🔄 Open a pull request.**

## 📧 Contact Information
- **✉️ Email**: oleg15062005@gmail.com
- **💻 GitHub**: [Oleh Kihichak](https://github.com/OKihichak)
