# ✈️ Flight Ticket Price Predictor

A machine learning project that predicts flight ticket prices based on various features such as airline, source, destination, stops, and travel time. Built using Python and Jupyter Notebook.

---

## 📌 Project Overview

Flight ticket prices fluctuate based on numerous factors — booking time, airline, number of stops, journey duration, and more. This project leverages machine learning regression techniques to predict ticket prices, helping travelers and analysts make data-driven decisions.

---

## 📂 Repository Structure
Flight-Ticket-Price-Predictor/
│
├── Data_Train.xlsx          # Training dataset with flight details and prices
├── flightds.ipynb           # Main Jupyter Notebook (EDA + Model Training)
├── flightds-checkpoint.ipynb # Auto-saved checkpoint of the notebook
└── README.md

---

## 🗃️ Dataset

The dataset (`Data_Train.xlsx`) contains the following features:

| Feature | Description |
|---|---|
| `Airline` | Name of the airline |
| `Date_of_Journey` | Date of the flight |
| `Source` | Departure city |
| `Destination` | Arrival city |
| `Route` | Flight route (with stops) |
| `Dep_Time` | Departure time |
| `Arrival_Time` | Arrival time |
| `Duration` | Total flight duration |
| `Total_Stops` | Number of stops |
| `Additional_Info` | Extra details (meal, no-info, etc.) |
| `Price` | 🎯 Target variable — ticket price in INR |

---

## 🔧 Tech Stack

- **Language:** Python 3.x
- **Environment:** Jupyter Notebook
- **Libraries:**
  - `pandas` — Data manipulation
  - `numpy` — Numerical computation
  - `matplotlib` / `seaborn` — Data visualization
  - `scikit-learn` — Machine learning models & preprocessing

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/jishnuuverse/Flight-Ticket-Price-Predictor.git
cd Flight-Ticket-Price-Predictor
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### 3. Run the Notebook

Open `flightds.ipynb` in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook flightds.ipynb
```

---

## 📊 Workflow

1. **Data Loading** — Load and inspect the Excel dataset
2. **Exploratory Data Analysis (EDA)** — Visualize distributions, correlations, and trends
3. **Feature Engineering** — Extract date/time features, encode categoricals, handle stops
4. **Model Training** — Train regression model(s) to predict ticket prices
5. **Evaluation** — Assess model performance using metrics like R² and MAE

---

## 📈 Results

The model learns patterns from historical flight data and predicts ticket prices based on input features. Performance metrics are documented in the notebook.

---

## 🙋 Author

**Jishnu** — [@jishnuuverse](https://github.com/jishnuuverse)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
