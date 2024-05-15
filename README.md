# Skincare-Routine-AI-Scraper

Welcome to Skincare-Routine-AI-Scraper! This project aims to help users find the best skincare products for their specific needs and integrate them into their skincare routines. The tool scrapes product data, analyzes it, and provides comprehensive information to help users make informed decisions.

## Features

- **Product Search**: Find skincare products based on specific criteria.
- **Comprehensive Information**: Detailed product descriptions including suitability for skin types, compatibility with other products, usage timing, and placement within a skincare routine.
- **Organize Products**: Save and organize products into personalized skincare routines.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Backend (Python)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Skincare-Routine-AI-Scraper.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Skincare-Routine-AI-Scraper
    ```
3. Set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Frontend (React)

1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```
2. Install the necessary dependencies:
    ```bash
    npm install
    ```

## Usage

### Run the Scraper

1. Navigate to the project directory:
    ```bash
    cd Skincare-Routine-AI-Scraper
    ```
2. Run the scraper to collect product data:
    ```bash
    python src/scraper.py
    ```

### Start the Backend Server

1. Navigate to the project directory (if not already there):
    ```bash
    cd Skincare-Routine-AI-Scraper
    ```
2. Start the Flask backend server:
    ```bash
    python src/app.py
    ```

### Start the Frontend Server

1. Navigate to the `frontend` directory:
    ```bash
    cd frontend
    ```
2. Start the React frontend server:
    ```bash
    npm start
    ```
3. Open your browser and navigate to `http://localhost:3000`.

### Example Search

1. Enter the product name or criteria in the search bar.
2. Browse through the list of products and click on a product to view detailed information.
3. Add products to your routine by clicking the "Add to Routine" button.


## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of your changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request.




