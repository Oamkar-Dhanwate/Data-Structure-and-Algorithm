# Stock Price Management and Prediction System

## Overview

This project implements a comprehensive stock price management and prediction system using:
- AVL Trees for efficient price storage and retrieval
- Linear and polynomial regression models for price prediction
- Statistical methods for confidence interval calculation
- Visualization tools for both data structures and predictions

## Features

### Core Functionalities
- **AVL Tree Implementation**:
  - Insert, delete, and search stock prices with O(log n) complexity
  - Automatic balancing to maintain optimal performance
- **Price Prediction**:
  - Linear regression model for stable trend prediction
  - Polynomial regression model for capturing non-linear patterns
  - Confidence interval calculation for both models
- **Visualization**:
  - Interactive AVL tree visualization
  - Stock price trend graphs
  - Prediction plots with confidence intervals

### Advanced Features
- Adaptive confidence level adjustment (95%-99%)
- Model reliability assessment
- Non-negative price constraints
- Dynamic visualization of predictions

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   cd stock-price-prediction
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main script:
```bash
python stock_predictor.py
```

### Menu Options
1. **Insert Stock Price** - Add new prices to the system
2. **Delete Stock Price** - Remove existing prices
3. **Search Stock Price** - Check if a price exists
4. **Update Stock Price** - Modify existing prices
5. **Display Prices** - Visualize AVL tree and price trends
6. **Predict Prices** - Generate future price predictions
7. **Adjust Confidence** - Change prediction confidence level
8. **Exit** - Quit the program

## Technical Details

### Data Structures
- **AVL Tree**: Self-balancing binary search tree implementation
- **Graph Visualization**: NetworkX and Matplotlib integration

### Machine Learning Models
- **Linear Regression**: For stable trend prediction
- **Polynomial Regression (Degree 2)**: For capturing curvature in data
- **Statistical Methods**: t-distribution for confidence intervals

### Key Algorithms
- Tree rotations (LL, RR, LR, RL)
- Recursive tree operations
- Feature transformation for polynomial regression
- Mean Squared Error calculation

## Dependencies

- Python 3.6+
- NumPy
- SciPy
- scikit-learn
- Matplotlib
- NetworkX

## Screenshots

![AVL Tree Visuali![Screenshot 2025-04-21 154845](https://github.com/user-attachments/assets/68fd4036-58ca-4648-a62a-1b493a9572d5)
zation]()
*AVL Tree and Price Trend Visualization*

![Prediction Visualization](scr![Screenshot 2025-04-21 155212](https://github.com/user-attachments/assets/98bb1cd8-21c1-4323-a926-bc87f92fec7e)
eenshots/prediction_visualization.png)
*Price Prediction with Confidence Intervals*

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by financial data analysis techniques
- Uses standard Python data science stack
- Visualization techniques adapted from NetworkX documentation
