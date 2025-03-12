# Travel Recommendations API

A web API that helps users discover travel destinations in Mexico based on their preferences and requirements. This project provides tailored travel recommendations by matching user specifications with a database of Mexican destinations.

## Features

- **Personalized Recommendations**: Receive destination suggestions based on your specific preferences
- **Detailed Information**: View comprehensive details about each recommended location
- **Visual Gallery**: Browse through high-quality images of destinations
- **Interactive Maps**: Explore the recommended locations using integrated Mapbox maps to know where are located

## Technology Stack

- **Backend**: Flask (Python)
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Maps Integration**: Mapbox API
- **Visualization**: Mapkick.js for data visualization

## Getting Started


### Installation

1. Clone the repository

2. Set up the database

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

5. Open your browser and navigate to `http://localhost:9000`

## Usage

1. Visit the home page and fill out the preference form
2. Specify your travel preferences (budget, activities, climate, etc.)
3. Browse the recommended destinations that match your criteria
4. Click on individual locations to view detailed information and maps

## API Endpoints

- `GET /`: Home page with preference form
- `GET /search`: Returns destinations matching search criteria
- `GET /place/<id>`: Detailed information about a specific place
- `GET /gallery`: Browse all available destinations
