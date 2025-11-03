# 📊 Factor Analysis - Telecom Customer Service Analysis

## 📖 Overview

This project applies **Factor Analysis (FA)** and **Structural Equation Modeling (SEM)** to understand the underlying factors driving customer satisfaction in the telecommunications industry. By reducing 14 observed service quality variables into 3 latent factors, this analysis provides actionable insights for improving customer experience and operational decision-making.

The solution identifies key drivers of customer satisfaction and quantifies their impact, enabling telecom providers to prioritize investments and interventions effectively.

## 🎯 Business Problem

Telecom companies collect extensive customer feedback across multiple service dimensions, but understanding which factors truly drive satisfaction is challenging. Key business challenges include:

- **Complex relationships** between service attributes and customer satisfaction
- **Resource allocation** decisions for service improvements
- **Unclear priorities** among competing service quality metrics
- **High dimensionality** of customer feedback data

This analysis helps organizations identify the most influential factors affecting customer satisfaction and understand their relative importance.

## 🚀 Key Features

- **Dimensionality Reduction**: Consolidates 14 service variables into 3 interpretable factors
- **Statistical Validation**: Bartlett's Test and KMO Test confirm data suitability for factor analysis
- **Varimax Rotation**: Orthogonal rotation for clearer factor interpretation
- **Reliability Testing**: Cronbach's Alpha (>0.77) validates internal consistency
- **Confirmatory Factor Analysis**: Validates the proposed factor structure
- **Structural Equation Modeling**: Quantifies impact of each factor on satisfaction
- **Path Analysis**: Visualizes relationships between variables and latent constructs

## 🛠️ Technical Stack

### Statistical Analysis
- **Factor Analyzer** (Exploratory and Confirmatory FA)
- **Semopy** (Structural Equation Modeling)
- **Pingouin** (Reliability analysis - Cronbach's Alpha)

### Data Processing & Visualization
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Visualization and heatmaps)
- **Scikit-learn** (Preprocessing and label encoding)

### Development Environment
- **Python 3.7+**
- **Jupyter Notebook / Google Colab**

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.7+**
- **Jupyter Notebook** or **Google Colab**
- Required Python packages (see Installation section)

## 🔧 Installation

1. **Clone the repository**:
```bash
