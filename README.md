# 🏠 AMES AI — Elite Property Valuation Platform

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-1.30+-red?style=for-the-badge&logo=streamlit" alt="Streamlit">
  <img src="https://img.shields.io/badge/Scikit--learn-1.3+-orange?style=for-the-badge&logo=scikit-learn" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ridge%20Regression-α=100-9D50BB?style=for-the-badge&color=9D50BB" alt="Ridge Regression">
  <img src="https://img.shields.io/badge/R²%20Score-0.875-00D2FF?style=for-the-badge&color=00D2FF" alt="R2 Score">
  <img src="https://img.shields.io/badge/RMSE-%2421k-00FF87?style=for-the-badge&color=00FF87" alt="RMSE">
</p>

---

<p align="center">
  <strong>Luxury meets Machine Learning.</strong><br>
  An enterprise-grade house price prediction system powered by Ridge Regression.
</p>

---

## 🚀 Overview

**AMES AI** is a premium SaaS-style web application that predicts residential property prices using advanced regression modeling on the Ames Housing dataset.

The platform combines:

| | | |
|:---:|:---:|:---:|
| 📊 **Data Science** | 🤖 **Machine Learning** | 🎨 **Modern UI/UX Design** |
| 🌐 **Streamlit Web Deployment** | 📈 **Interactive Visualizations** | 🔮 **Intelligent Predictions** |

---

## 🧠 Machine Learning Model

<div align="center">

| **Algorithm** | **Ridge Regression** |
|:---:|:---:|
| Regularization (Alpha) | 100 |
| R² Score | 0.875 |
| RMSE | ~ $21,000 |
| Training Samples | 1,400+ |
| Features | 79+ |

</div>

### Why Ridge Regression?

- ✅ Handles multicollinearity in housing features
- ✅ Reduces overfitting with L2 regularization
- ✅ Works efficiently with high-dimensional feature space
- ✅ Produces stable and reliable predictions

### Model Pipeline

```
Raw Data → Missing Value Handling → Feature Encoding → Feature Scaling → Ridge Regression → Price Prediction
```

- **Dataset**: Ames Housing Dataset (1,460 rows, 80+ features)
- **Preprocessing**: One-Hot Encoding, StandardScaler
- **Split**: Train/Test (80/20)
- **Tuning**: Cross-validation for optimal alpha

---

## 🎨 Application Features

### ✨ Premium UI Experience
- 🌙 Dark SaaS dashboard theme
- 🔮 Glassmorphism cards with subtle gradients
- 📍 Sticky top navigation
- 🌈 Gradient typography
- 📊 Interactive charts (Plotly)
- ✨ Smooth animations

### 📊 Market Intelligence Dashboard
- 📈 Area vs Price scatter plot
- 🏘️ Neighborhood average price analysis
- 📉 Simulated demand curves
- 📊 Feature influence visualization

### 🔮 Elite Valuation Engine

**Dynamic Inputs:**
| Build & Space | Quality & Luxury | Location & Plot |
|:---:|:---:|:---:|
| Living Area | Overall Quality | Neighborhood |
| Basement Area | Bedrooms | Lot Size |
| Year Built | Bathrooms | Lot Shape |
| Year Remodeled | Fireplaces | Central Air |
| Garage Capacity | | |

**Outputs:**
- 💰 Large prediction display with formatting
- 📊 Interactive Gauge Chart
- 📝 Configuration summary

---

## 📈 Model Performance

<div align="center">

| Metric | Value |
|:---:|:---:|
| R² Score | **0.88** |
| RMSE | **$21k** |
| Training Rows | **1,400+** |

</div>

### Methodology

- Uses **Ridge Regression** with L2 regularization
- Features engineered from area, quality, age, and amenities
- Hyperparameters tuned via cross-validation for stability
- Outputs calibrated price ranges suitable for portfolio decisions

---

## 🏗️ Tech Stack

<div align="center">

| Layer | Technology |
|:---|:---|
| 🔵 Backend | Python |
| 🤖 ML Framework | Scikit-learn |
| 🎈 UI Framework | Streamlit |
| 📊 Visualization | Plotly |
| 📦 Data Handling | Pandas & NumPy |
| 🌐 Deployment | Streamlit Cloud |
| 📝 Version Control | Git & GitHub |

</div>

---

## 🚦 Getting Started

### Prerequisites

```
bash
Python 3.11+
```

### Installation

1. **Clone the repository:**
```
bash
git clone https://github.com/your-repo/ames-ai.git
cd ames-ai
```

2. **Install dependencies:**
```
bash
pip install -r requirements.txt
```

3. **Run the application:**
```
bash
streamlit run app.py
```

4. **Open in browser:**
```
http://localhost:8501
```

---

## 📁 Project Structure

```
📂 ames-ai/
├── 📄 app.py                 # Main Streamlit application
├── 📄 requirements.txt       # Python dependencies
├── 📄 README.md              # This file
├── 📄 model training.ipynb   # Jupyter notebook for model training
├── 📄 ridge_model.pkl        # Trained Ridge Regression model
├── 📄 scaler.pkl            # Fitted StandardScaler
├── 📄 train.csv              # Training dataset
└── 📄 test.csv               # Test dataset
```

---

## 📸 Screenshots

<p align="center">
  <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?q=80&w=2000&auto=format&fit=crop" width="400" alt="Luxury Home">
  <img src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?q=80&w=2000&auto=format&fit=crop" width="400" alt="Modern Property">
</p>

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

<p align="center">
  <strong>AMES AI • Enterprise Solutions • 2024</strong><br>
  <sub>Built with ❤️ using Ridge Regression</sub>
</p>
