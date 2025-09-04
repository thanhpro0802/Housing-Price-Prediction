# Housing Price Prediction with Linear Regression from Scratch

A comprehensive machine learning project implementing housing price prediction using Linear Regression built from scratch with Gradient Descent algorithm. This project uses the California Housing dataset to demonstrate fundamental machine learning concepts.

## 🎯 Project Overview

This repository contains a complete Jupyter Notebook implementation that covers:

- **Data Preparation**: Loading and preprocessing the California Housing dataset
- **Exploratory Data Analysis**: Comprehensive visualizations including histograms, heatmaps, and scatter plots
- **Linear Regression from Scratch**: Complete implementation using Gradient Descent algorithm
- **Model Training & Evaluation**: Training with MSE, RMSE, and R² metrics
- **Comparison Study**: Validation against scikit-learn's LinearRegression
- **Practical Application**: Real-world price prediction examples

## 🚀 Features

- ✅ **Complete Linear Regression Implementation**: Built from mathematical foundations
- ✅ **Gradient Descent Algorithm**: Step-by-step optimization process
- ✅ **Data Visualization**: Rich charts and plots for data understanding
- ✅ **Model Evaluation**: Multiple metrics for performance assessment
- ✅ **Educational Content**: Detailed explanations and comments throughout
- ✅ **Practical Examples**: Real house price predictions
- ✅ **Comparison Analysis**: Custom vs. industry-standard implementation

## 📊 Dataset

The project uses the **California Housing Dataset** which contains:
- 20,640 housing districts in California
- 8 features: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
- Target: Median house value in hundreds of thousands of dollars

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/thanhpro0802/Housing-Price-Prediction.git
   cd Housing-Price-Prediction
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook housing_price_prediction.ipynb
   ```

## 📋 Requirements

- Python 3.7+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

See `requirements.txt` for specific versions.

## 🔍 What You'll Learn

### Mathematical Concepts
- **Cost Function**: J(θ) = (1/2m) * Σ(hθ(x) - y)²
- **Gradient Computation**: ∂J/∂θⱼ = (1/m) * Σ(hθ(x) - y) * xⱼ
- **Parameter Updates**: θⱼ := θⱼ - α * ∂J/∂θⱼ

### Machine Learning Fundamentals
- Feature scaling and standardization
- Train-test split methodology
- Model evaluation metrics
- Overfitting vs. underfitting
- Residual analysis

### Data Science Skills
- Exploratory data analysis
- Data visualization techniques
- Feature importance analysis
- Model comparison and validation

## 📈 Key Results

The custom implementation achieves:
- **R² Score**: ~0.60 on test data
- **RMSE**: ~0.73 (in $100k units)
- **Nearly identical performance** to scikit-learn's LinearRegression
- **Convergence**: Smooth cost function reduction over iterations

## 🏠 Practical Usage

The notebook includes a prediction function that can estimate house prices:

```python
predicted_price = predict_house_price(
    med_inc=8.0,      # $80,000 median income
    house_age=10.0,   # 10 years old
    ave_rooms=7.0,    # 7 rooms per household
    ave_bedrms=1.0,   # 1 bedroom per household
    population=3000,  # 3000 people in block
    ave_occup=3.0,    # 3 people per household
    latitude=34.0,    # Los Angeles area
    longitude=-118.0  # Los Angeles area
)
```

## 📚 Educational Value

This project is perfect for:
- **Students** learning machine learning fundamentals
- **Developers** wanting to understand algorithms from scratch
- **Data Scientists** reviewing core concepts
- **Anyone** interested in practical ML applications

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- California Housing Dataset from scikit-learn
- Mathematical foundations from machine learning literature
- Inspiration from educational ML resources