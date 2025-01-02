# React Food App

This is a React application built with Vite, featuring a food menu with filtering options for different meal types (breakfast, lunch, dinner, etc.). The app uses a Node.js server to fetch food data.

## Features

- Display a list of food items
- Filter food items by meal type (All, Breakfast, Lunch, Dinner, etc.)
- Fetch food data from a Node.js server

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (version 14 or later)
- npm (usually comes with Node.js)

## Setup

1. Clone the repository:
   ```
   git clone  https://github.com/Mohan2345/Foody_Zone_App_React
   cd  Foody_Zone_App_React
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the Node.js server:
   ```
   npm run server
   ```

4. In a new terminal, start the React development server:
   ```
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`  

 

## Usage

1. When you open the app, you'll see a list of all food items.
2. Use the filter buttons (All, Breakfast, Lunch, Dinner, etc.) to filter the food items by meal type.
3. Click on the "All" button to show all food items again.

## API Endpoints

The Node.js server provides the following endpoint:

- GET `/api/foods`: Returns a list of all food items

## Contributing

If you'd like to contribute, please fork the repository and create a pull request. You can also simply open an issue with the tag "enhancement".

## License

This project is licensed under the [MIT License](LICENSE).
