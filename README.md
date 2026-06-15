# Used Vehicles Dashboard with Streamlit

Interactive dashboard developed with **Streamlit** to explore a dataset of used vehicles in the United States.

The goal of this project is to create a simple and accessible web application that allows users to visually analyze vehicle characteristics such as price, mileage, model year, condition, and vehicle type through interactive charts.

---

## Project overview

This project focuses on exploratory data analysis and interactive visualization.

The dashboard allows users to explore patterns in the used vehicles market, especially relationships between:

* Vehicle price and mileage.
* Mileage distribution.
* Model year and vehicle characteristics.
* Vehicle condition and price behavior.
* General trends across the dataset.

The application was designed to make data exploration easier for users who want quick visual insights without modifying code.

---

## Analytical context

Used vehicle datasets often contain multiple variables that can influence price and purchasing decisions, such as mileage, age, condition, model, and vehicle type.

This dashboard provides a visual way to explore these relationships and identify general patterns in the data. While it is not a pricing prediction model, it can support preliminary analysis and help users understand how different vehicle characteristics relate to price and mileage.

---

## Tools and technologies

* Python
* Pandas
* Plotly Express
* Streamlit
* Git / GitHub

---

## Main features

* Interactive data exploration through a web interface.
* Histogram to analyze mileage distribution.
* Scatter plot to explore the relationship between price and mileage.
* Simple checkbox-based controls.
* Visual analysis without needing to modify the source code.
* Lightweight structure that can be deployed as a Streamlit application.

---

## Repository structure

```text
dashboard-vehiculos-usados-streamlit/
├── notebooks/              # Exploratory analysis notebook
├── app.py                  # Main Streamlit application
├── vehicles_us.csv         # Dataset used in the project
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## Skills demonstrated

* Exploratory data analysis.
* Interactive dashboard development.
* Data visualization with Plotly.
* Streamlit application structure.
* Basic user interface design for data exploration.
* Clear communication of data insights.
* GitHub project documentation.

---

## How to run the application locally

1. Clone this repository:

```bash
git clone https://github.com/danielpdls/dashboard-vehiculos-usados-streamlit.git
```

2. Navigate to the project folder:

```bash
cd dashboard-vehiculos-usados-streamlit
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit app:

```bash
streamlit run app.py
```

---

## Possible improvements

Future improvements could include:

* Adding filters by vehicle type, model year, condition, or price range.
* Including additional charts for categorical variables.
* Adding summary metrics at the top of the dashboard.
* Improving the visual layout of the application.
* Deploying the app publicly with Streamlit Community Cloud.

---

## Author

**Daniel Puente de los Santos**

Data Analyst focused on business, operations, and data-driven decision-making.

* GitHub: [github.com/danielpdls](https://github.com/danielpdls)
* LinkedIn: [linkedin.com/in/danielpdls](https://www.linkedin.com/in/danielpdls)
