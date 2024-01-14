# Stock Recovery Gain Visualization

## Overview
This project presents a Python-based visualization of the relationship between the percentage drop in a stock's price and the subsequent gain required to break even. Inspired by the principles of value investing and the concept of "investing at the point of maximum pessimism" as advocated by Sir John Templeton, this simple yet profound analysis showcases the non-linear and asymmetric nature of stock price recovery.

## Motivation
In the realm of investing, understanding the fundamental dynamics of market movements is crucial. This project aims to reinforce core financial principles by visualizing how a stock recovers from a downturn. It's a testament to how mathematical insights can enhance our understanding of financial markets, serving as a powerful tool for investors and finance enthusiasts.

## Visualization
The visualization is created using a Jupyter Notebook, leveraging the power of Python libraries like `matplotlib` and `numpy`. The curve `y = (x * 100) / (100 - x)` is plotted, where `x` represents the percentage drop in stock, and `y` depicts the gain required to break even. This graph not only provides clarity on market recovery but also emphasizes the asymmetric nature of financial gains post-decline.

## Getting Started
To run this project, clone the repository and open the Jupyter Notebook in an environment where Python, along with `matplotlib` and `numpy`, is installed.

### Prerequisites
- Python
- Matplotlib
- NumPy

### Installation
If you don't have `matplotlib` and `numpy` installed, you can install them using pip:
- pip install matplotlib numpy


### Running the Notebook
Open the Jupyter Notebook and execute each cell to see the visualization. The code is well-commented, making it easy to follow and understand the plotting process.

## Contributing
Contributions to this project are welcome! Feel free to fork the repository and submit pull requests.

## License
[MIT License](LICENSE)
