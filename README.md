# Belifull App

## Features

- **New Restaurant Suggestions**: Discover newly opened restaurants and similar options based on your favorites for a personalized dining experience.
- **Simple UI**: Enjoy an intuitive interface designed for effortless navigation, making it easy to find what to eat.
- **Location-Based Alerts**: Receive notifications for nearby dining options at meal times, ensuring you always know what’s around you.
- **Bookmarking**: Save your favorite restaurants for quick access, simplifying your decision-making process.

## Tech Stack

- **Frontend**: React Native for a smooth and engaging mobile experience.
- **Backend**: Node.js with Express for efficient API management and user data handling.
- **Database**: MongoDB for storing user preferences, restaurant data, and saved favorites.
- **APIs**: Zomato and Google Places for real-time restaurant information and recommendations.
- **Geolocation**: Utilized for proximity alerts to enhance user convenience.
- **Authentication**: JWT for secure user login and data protection.
- **Deployment**: Docker for consistent development and production environments.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Belifull.git
   cd Belifull

2. **Install dependencies:**
   npm install
   cd backend
   pip install -r requirements.txt

3. **Set up environment variables:**
-  Create a .env file in the root directory with the following variables:

   REACT_APP_ZOMATO_API_KEY=your_zomato_api_key
   REACT_APP_GOOGLE_PLACES_API_KEY=your_google_places_api_key
   JWT_SECRET=your_jwt_secret


