
# Black-Scholes Option Pricing Model in Python

This project implements the Black-Scholes model for pricing European call and put options using Python. It also visualises how option prices change with respect to time to expiration and volatility.

## Features

- Calculates European option prices (call/put) using the Black-Scholes formula.
- Visualises the sensitivity of option prices to:
  - Time to expiration
  - Volatility
- Clean plots with Seaborn and Matplotlib.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install numpy scipy matplotlib seaborn
```

### Running the Project

1. Clone the repository or download the `.ipynb` file.
2. Run the script in a Jupyter Notebook or any Python environment.

### Example Usage

```python
# Example: Calculate a call option price
price = black_scholes(S0=100, K=100, T=1, r=0.05, sigma=0.2, option_type='call')
print(f"Call Option Price: {price}")
```

## Visualisations

- **Call Option Price vs Time to Expiration**

  Illustrates how the option value increases as expiration time increases, assuming all other variables are constant.

- **Call Option Price vs Volatility**

  Shows the impact of increased volatility on the option value, reflecting greater uncertainty and thus potentially higher value.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

Rory McTeague  
[Github Profile](https://github.com/RoryMcTeague/)
