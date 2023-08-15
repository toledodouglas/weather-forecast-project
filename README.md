# Weather Forecast ~ ReactJS and Express 🌦️

Welcome to a ReactJS and Express Monorepo project based on OpenWeather API! This is a web application that allows you to search for your location and view the weather forecast using the OpenWeather API.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [API Key](#api-key)
- [Contributing](#contributing)
- [License](#license)

## Features

- Search for weather forecasts by location.
- Display current weather conditions including temperature, humidity, wind speed, and more.
- 5-day weather forecast.
- Responsive and user-friendly design.
- Monorepo structure with both ReactJS frontend and Express backend in a single repository.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- Node.js and npm (Node Package Manager) installed.
- OpenWeather API key. (See [API Key](#api-key) section)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/toledodouglas/weather-forecast-project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-forecast-project
   ```

3. Install dependencies for both frontend and backend:

   ```bash
   cd api
   npm install
   cd ..
   cd web
   npm install
   ```

## Project Structure

The project is organized as follows:

```
openweather-monorepo/
├── api/
│   ├── ...
│   ├── ...
├── web/
│   ├── ...
│   ├── ...
├── shared/
│   ├── ...
│   ├── ...
├── README.md
└── ...
```

- **api**: Express.js server code resides here.
- **web**: ReactJS frontend code is located here.
- **shared**: Shared code or utilities that can be used by both frontend and backend.

## Usage

To start the development server for both frontend and backend, use the following commands:

1. Navigate to the `backend` folder:

   ```bash
   cd api
   ```

2. Start the Express server:

   ```bash
   npm start
   ```

3. In a separate terminal, navigate to the `frontend` folder:

   ```bash
   cd web
   ```

4. Start the React development server:

   ```bash
   npm start
   ```

Once the servers are running, you can access the application by visiting `http://localhost:3000` in your browser.

## API Key

To fetch weather data from the OpenWeather API, you'll need to obtain an API key. Visit the [OpenWeather website](https://openweathermap.org/) and sign up to get your API key. Once you have the key, create a `.env` file in the `backend` folder and add the following line:

```plaintext
OPENWEATHER_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your actual API key.

## Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit pull requests. Please follow the coding style and conventions used in the project.

## License

This project is licensed under the [MIT License](https://github.com/toledodouglas/weather-forecast-project/blob/main/LICENSE.txt).

---

We hope you enjoy using our Weather Forecast ReactJS and Express Monorepo Project. If you have any questions or feedback, please don't hesitate to reach out.

Happy coding! 🌦️
