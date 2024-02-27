# OptionViz

OptionViz is a web application designed to visually demonstrate the Black-Scholes-Merton formula, a fundamental concept in finance for pricing options. This app allows users to input parameters such as stock price, strike price, volatility, risk-free rate, and time to expiration to calculate and visualize the option's theoretical price and Greeks.

## Features

- **Option Pricing**: Calculate the theoretical price of a call or put option using the Black-Scholes-Merton formula.

- **Graphical Visualization**: View how changes in input parameters affect the option's price and Greeks through interactive graphs.

- **Input Flexibility**: Adjust stock price, strike price, volatility, risk-free rate, and time to expiration to see real-time calculations and visualizations.

- **Responsive Design**: Access the app on any device, with a design that adjusts for the best viewing experience.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
git clone git@github.com:lukebellis/OptionViz.git

2. Navigate to the project directory:

cd optionviz


3. Install dependencies:
npm install


4. Serve the app with hot reloads for development:
npm run serve


5. Visit `http://localhost:8080/` to view the app.

## Usage

To use OptionViz, simply enter the required parameters for the option you wish to analyze:

- Stock Price (S)
- Strike Price (K)
- Volatility (σ)
- Risk-Free Rate (r)
- Time to Expiration (T)

After entering these parameters, click "Calculate" to see the option's theoretical price and the Greeks. Use the interactive graphs to explore how changes in each parameter affect the option's valuation.

## Built With

- [Vue.js](https://vuejs.org/) - The progressive JavaScript framework used for building the UI.
- [Chart.js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting for designers & developers.

## Contributing

I welcome contributions to OptionViz! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thanks to the creators of the Black-Scholes-Merton model for their contributions to financial mathematics.
- This project was inspired by the need for interactive educational tools in finance.