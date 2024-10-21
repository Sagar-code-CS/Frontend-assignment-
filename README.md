Cryptocurrency Market Data App

This project is a real-time cryptocurrency market data visualization application that connects to the Binance WebSocket API to display live candlestick data for selected cryptocurrency pairs. The app allows users to toggle between different cryptocurrencies (ETH/USDT, BNB/USDT, DOT/USDT) and time intervals (1 minute, 3 minutes, 5 minutes). The data is visualized using Chart.js as a line chart, showing the price changes over time.

Features
Real-time data: Fetches live cryptocurrency market data using Binance’s WebSocket API. Interactive UI: Users can select different cryptocurrency pairs and time intervals to view live data. Dynamic line chart: Visualizes close prices using a responsive, real-time line chart. Responsive design: Works well on both desktop and mobile devices.

Table of Contents
Features

Demo

Technologies

Installation

Usage

Future Enhancements

Contributing

Technologies
JavaScript (ES6): For WebSocket handling and dynamic data updates. HTML5 & CSS3: For structuring and styling the user interface. Chart.js: Used for real-time chart rendering. Binance WebSocket API: For fetching live cryptocurrency market data.

Installation
To run this project locally, follow these steps:

Clone the repository:

bash Copy code git clone https://github.com/yourusername/cryptocurrency-market-data-app.git Navigate to the project directory:

bash Copy code cd cryptocurrency-market-data-app Open index.html in your browser:

You can open the file directly in your browser or serve it using a local server (e.g., with VSCode Live Server or a tool like http-server).

Usage
Upon loading the app, you’ll see a line chart with real-time price data for ETH/USDT on a 1-minute interval. Use the dropdown menus to: Switch between cryptocurrencies (ETH/USDT, BNB/USDT, DOT/USDT). Change the candlestick time interval (1 minute, 3 minutes, or 5 minutes). The chart will automatically update as new data comes in through the WebSocket connection.

Example usage
Here’s a simple example of how the data is visualized in the app:

Select BNB/USDT and a 3-minute interval. The chart will show real-time price updates for the selected pair and time interval.

Future Enhancements
Candlestick chart: Switch from line chart to candlestick chart for better financial data representation. Data caching: Store data in local storage or a database to view historical data when switching back to previously selected coins. Add more cryptocurrencies: Allow users to select from a larger pool of cryptocurrencies. Dark mode: Add a theme toggle to switch between light and dark modes.

Contributing
Contributions are welcome! If you have any ideas or improvements, feel free to fork the repository and submit a pull request. Here’s how you can contribute:

Fork the repository. Create a feature branch (git checkout -b feature-branch). Commit your changes (git commit -m 'Add feature'). Push to the branch (git push origin feature-branch). Open a pull request.
