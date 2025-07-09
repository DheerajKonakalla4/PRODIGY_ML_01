
```markdown
# 🏡 House Price Prediction using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on key features from the Ames Housing dataset, such as square footage, number of bedrooms, and number of bathrooms.

## 📊 Features Used
- `GrLivArea`: Above ground living area (in square feet)
- `BedroomAbvGr`: Number of bedrooms above ground
- `FullBath` + `HalfBath`: Combined as `TotalBath`

## 🧠 Model Summary
- **Model**: Linear Regression
- **Library**: scikit-learn
- **Train/Test Split**: 80/20
- **Metrics**:
  - Mean Squared Error (MSE)
  - R² Score
- **Visualization**: Scatter plot of actual vs predicted prices

## 📁 Project Structure
```

house\_price\_prediction/
├── train.csv
├── model.py
├── README.md
├── requirements.txt

```

## 🚀 How to Run

### 1. Install dependencies
```

pip install -r requirements.txt

```

### 2. Run the project
```

python model.py

```

## 🖼 Output Sample

A scatter plot is generated comparing actual vs predicted sale prices.

## 📦 Requirements
- Python 3.7+
- pandas
- scikit-learn
- matplotlib
- seaborn

Install via:
```

pip install pandas scikit-learn matplotlib seaborn

```

## 👨‍💻 Author
**Dheeraj Konakalla**  
📧 dheeraj.konakalla@example.com  
🔗 [GitHub](https://github.com) • [LinkedIn](https://linkedin.com)

## 📜 License
This project is open-sourced under the MIT License.
```