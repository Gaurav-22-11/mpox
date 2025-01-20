# Global Monkeypox Outbreak Dynamics: A Multi-faceted Predictive Analysis and Risk Assessment Framework

This project analyzes the global dynamics of the monkeypox outbreak through predictive modeling, interactive visualizations, and a comprehensive risk assessment framework.

---

## Features

### Data Visualization
- **Interactive Global Map**: Visualizes the global distribution of cases.
- **Monthly Trends**: Highlights new cases trends on a monthly basis.
- **Case Fatality Rate (CFR)**: Tracks the CFR over time to identify patterns.
- **Violin and Histogram Plots**: Shows distribution of new cases across continents and daily new cases.

### Predictive Models
- **Time Series Forecasting**:
  - Combines ARIMA, Prophet, and LSTM models to forecast new cases and outbreaks.
- **Risk Assessment Framework**:
  - SHAP analysis using a Random Forest Classifier highlights influential factors like total cases, new cases, and fatalities.
- **Transmission Dynamics**:
  - Simulates the SEIR (Susceptible, Exposed, Infected, Recovered) model for understanding disease spread over time.

### Natural Language Processing (NLP)
- **Sentiment Analysis**: Evaluates news sentiment to assess public reaction.
- **Misinformation Detection**: Identifies potentially misleading content in monkeypox-related news.

---

## Dataset
The project utilizes a dataset with key features:
- **Epidemiological Data**: `total_cases`, `new_cases`, `total_deaths`, `new_deaths`
- **Geographical Data**: `location`, `continent`
- **Temporal Data**: `date`

---

## Visualizations

### Examples:
1. **Cumulative Monkeypox Cases Over Time**
   - Tracks case accumulation in the most affected countries.
2. **Case Fatality Rate**
   - Displays the CFR trends to monitor disease severity.
3. **Correlation Heatmap**
   - Examines relationships between epidemiological factors.
4. **Box and Violin Plots**
   - Shows distributions of new cases by continent and other variables.

---

## Methodology

### Time Series Models
1. **ARIMA**:
   - Autoregressive Integrated Moving Average for short-term case predictions.
2. **Prophet**:
   - Robust forecasting framework designed for time series with strong seasonality.
3. **LSTM**:
   - Long Short-Term Memory network for capturing long-term dependencies in case trends.

### SEIR Model
Simulates the disease dynamics:
- Susceptible (S), Exposed (E), Infected (I), and Recovered (R) compartments.

### Risk Assessment
- Employs machine learning (Random Forest) and interpretable SHAP values to identify influential factors contributing to outbreak severity.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/monkeypox-dynamics.git
Results
Comprehensive forecasts for monkeypox case trajectories.
Insights into risk factors influencing outbreak severity.
Clear visualizations to guide public health interventions.
