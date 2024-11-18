# Weather Forecast Prototype

A sleek and responsive weather forecast application that provides real-time weather information for any city. Built with vanilla JavaScript, HTML, and CSS, this application leverages the OpenWeatherMap API to deliver accurate weather data with a beautiful user interface.

![Weather Forecast App](wallhaven-47xjpo_1920x1080.png)

## Features

- **Real-time Weather Data**: Fetches current weather information using the OpenWeatherMap API
- **Dynamic Background**: Changes background image based on the searched city
- **Responsive Design**: Works seamlessly across different screen sizes
- **Interactive UI Elements**: 
  - Animated search bar
  - Hover effects on the weather card
  - Loading state indicators
- **Weather Information Displayed**:
  - Temperature in Celsius
  - Weather description with icons
  - Humidity percentage
  - Wind speed in km/h

## Technologies Used

- HTML5
- CSS3 
- JavaScript 
- OpenWeatherMap API
- Unsplash API (for dynamic backgrounds)

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashish0ct/Weather_Forecast_Prototype.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Weather_Forecast_Prototype
   ```

3. Open `index.html` in your preferred web browser

## Usage

1. Enter a city name in the search bar
2. Press Enter or click the search button
3. View the current weather information for the specified city
4. The background will automatically update to show an image related to the searched city

## API Configuration

The application uses the OpenWeatherMap API. To use your own API key:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api)
2. Replace the `apiKey` value in `script.js`:
   ```javascript
   let weather = {
       "apiKey": "YOUR_API_KEY_HERE",
       // ...
   }
   ```

## Project Structure

- `index.html`: Main HTML structure
- `style.css`: Styling and animations
- `script.js`: Weather API integration and functionality
- `faviconICON/`: Contains favicon files

## Features Breakdown

### HTML Structure
- Responsive layout with flexbox
- Search input with button
- Weather information display card
- SVG icons for search functionality

### CSS Features
- Flexbox layout system
- Animated card borders
- Responsive design
- Custom button and input styling
- Loading state animations
- Dynamic background images

### JavaScript Functionality
- API integration with OpenWeatherMap
- Dynamic data fetching and display
- Event listeners for search functionality
- Background image updates using Unsplash API
- Error handling for API requests
