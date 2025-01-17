# Market Anomaly Detection

This project implements machine learning models to detect market anomalies using financial market data. The analysis uses various indicators and techniques to identify unusual market behavior that could signal potential opportunities or risks.

## Overview

The project uses a dataset containing multiple financial market indicators including:
- VIX (Volatility Index)
- DXY (US Dollar Index)
- Various government bond yields (German, Italian, Japanese)
- EONIA (Euro Overnight Index Average)
- And other market metrics

Multiple machine learning approaches are implemented to detect anomalies:

1. Logistic Regression
2. Isolation Forest
3. Decision Tree Classification

## Models and Performance

### Logistic Regression
- Implements balanced class weights to handle imbalanced data
- Uses feature scaling for better model performance
- Achieves ~82% accuracy with strong precision on normal market conditions

### Isolation Forest
- Unsupervised learning approach for anomaly detection
- Uses contamination factor of 0.2
- Achieves ~80% accuracy across all classes

### Decision Tree
- Provides interpretable decision rules
- Limited to depth of 4 for better generalization
- Achieves ~87% accuracy with good balance between precision and recall

## Key Features

- Data preprocessing and feature scaling
- Multiple model implementations
- Performance evaluation using classification metrics
- Visual decision tree representation
- Handling of imbalanced classes

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

The analysis is implemented in a Jupyter notebook format. To run:

1. Ensure all required libraries are installed
2. Load the FinancialMarketData.csv dataset
3. Run the notebook cells sequentially to see the analysis and results

## Results

The models show strong performance in detecting market anomalies:
- High precision (>90%) for normal market conditions
- Good recall (>80%) for anomaly detection
- Balanced handling of class imbalance
- Interpretable decision rules through tree visualization

## Future Improvements

- Feature engineering to include more market indicators
- Implementation of deep learning models
- Real-time anomaly detection capabilities
- Cross-validation for more robust model evaluation
- Hyperparameter tuning for better model performance

## License

This project is open source and available under the MIT License. 
