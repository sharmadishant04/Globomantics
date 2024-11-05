# Globomantics

Globomantics is a web application built with Flask that allows users to manage items for sale, including adding, editing, and deleting items. It features image uploads, category management, and user comments.

## Features

- User-friendly interface for item management.
- Image upload functionality with validation.
- Categorization of items into categories and subcategories.
- Commenting system for user interaction.
- Filtering options for item searches.
- Secure handling of user input with CSRF protection.

## Requirements

To run this application, you need:

- Python 3.x
- Flask
- Flask-WTF
- SQLite
- A web browser

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/globomantics.git
   cd globomantics
   ```

2. **Install required packages:**

   You can install the required packages using pip:

   ```bash
   pip install Flask Flask-WTF
   ```

3. **Set up the database:**

   Create a SQLite database file named `globomantics.db` in a directory called `db`, and set up the necessary tables as per your application’s requirements.

4. **Configure environment variables:**

   Set up your environment variables in a `.env` file or directly in your application code as needed.

## Usage

1. **Run the application:**

   You can start the Flask server by running:

   ```bash
   python app.py
   ```

2. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:5000/` to access the Globomantics application.

## Application Structure

The main components of the application include:

- **Flask Forms:** Used for handling user input securely.
- **Database Management:** SQLite is used to manage data persistence.
- **Image Uploads:** Users can upload images associated with items for sale.
- **Routing:** The application defines various routes for different functionalities such as viewing items, adding new items, editing existing items, and deleting items.

## Notes

- Ensure that you handle sensitive information securely and validate user inputs properly to prevent security vulnerabilities.
- Adjust image upload settings and limits as necessary based on your requirements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Dishant Sharma](https://github.com/sharmadishant04)
