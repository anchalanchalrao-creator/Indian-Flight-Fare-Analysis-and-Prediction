# Indian Flight Fare Analysis and Prediction
### Exploratory Data Analysis (EDA) Project

**Project Domain:** Data Analytics  
**Training Programme:** Data Science Training & Internship  
**Organization:** BLEEP Education  
**Dataset:** Flight Price Prediction Dataset – Kaggle

---

## 1. Project Overview

This project focuses on analysing historical Indian domestic flight ticket pricing data to understand the factors associated with airfare variations.

Exploratory Data Analysis (EDA) techniques are used to investigate airline-wise pricing patterns, differences between Economy and Business classes, advance booking windows, flight duration and departure timings.

The project uses Python and its data analysis and visualization libraries to identify pricing trends, statistical relationships and meaningful insights that can help travellers make informed booking decisions.

## 2. Project Objectives

- Analyse flight ticket price distributions and identify pricing trends.
- Compare average and median fares across different airlines.
- Examine differences between Economy and Business-class fares.
- Investigate the relationship between advance booking time and ticket prices.
- Study the relationship between flight duration and ticket fares.
- Analyse how departure and arrival timings relate to ticket prices.
- Identify useful patterns that can support better flight booking decisions.

## 3. Dataset Description

The project uses the **Flight Price Prediction Dataset** available on Kaggle.

| Dataset Attribute | Details |
|---|---|
| Total Observations | 300,153 |
| Dataset Type | Historical flight booking observations |
| Market | Indian domestic aviation |
| Target Variable | Price |
| Dataset File | `Clean_Dataset.csv` |

### Important Features

- Airline
- Flight
- Source City
- Destination City
- Departure Time
- Arrival Time
- Stops
- Class
- Duration
- Days Left
- Price

## 4. Tools and Technologies

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Pandas | Data manipulation and processing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive analysis and documentation |

## 5. Methodology

The project followed a structured data analysis workflow:

1. **Data Acquisition:** Collected the historical Indian flight fare dataset from Kaggle.
2. **Data Inspection:** Examined dataset dimensions, column names, data types and memory usage.
3. **Data Quality Assessment:** Checked missing values, duplicate records, unique values and potential inconsistencies.
4. **Data Preprocessing:** Reviewed and prepared categorical and numerical variables.
5. **Exploratory Data Analysis:** Applied descriptive statistics, grouping techniques and correlation analysis.
6. **Data Visualization:** Used bar charts, boxplots and scatter plots to identify patterns and relationships.
7. **Interpretation and Insights:** Analysed results and developed data-driven business recommendations.

## 6. Key Analysis and Findings

### 6.1 Airline-wise Fare Analysis

- Vistara recorded the highest median fare of ₹15,543.
- Air India followed with a median fare of ₹11,520.
- AirAsia recorded the lowest median fare of ₹3,276.
- Vistara also recorded the highest mean fare of ₹30,396.54.

### 6.2 Economy vs Business Fare Comparison

- Vistara: Business median ₹56,588; Economy median ₹6,461.
- Air India: Business median ₹49,613; Economy median ₹6,082.
- Vistara showed the largest observed class-wise median fare difference of ₹50,127.

Business-class observations were available only for Vistara and Air India in the dataset.

### 6.3 Booking Window Analysis

| Booking Window | Average Fare (₹) | Median Fare (₹) |
|---|---:|---:|
| 0–3 days | 28,068.68 | 16,572 |
| 4–7 days | 25,698.24 | 12,978 |
| 8–15 days | 23,534.11 | 11,893 |
| 16–30 days | 19,754.19 | 6,228.50 |
| 31–45 days | 19,335.68 | 6,056 |
| 46–60 days | 18,963.83 | 5,896 |

The 0–3 day booking window recorded the highest median fare, while the 46–60 day window recorded the lowest.

### 6.4 Flight Duration and Ticket Price

Correlation analysis produced the following results:

| Correlation Method | Coefficient |
|---|---:|
| Pearson Correlation | 0.204 |
| Spearman Correlation | 0.319 |

The results indicate a weak positive association between flight duration and ticket price. Duration alone is not a strong standalone predictor of airfare.

### 6.5 Departure Period and Flight Fare

- Morning departures recorded the highest median fare of ₹8,112.
- Afternoon departures recorded the lowest median fare of ₹6,663.
- Night departures recorded the highest mean fare of ₹22,697.61.

## 7. Visualizations

The analysis includes:

## Visualizations

### 1. Airline-wise Flight Fare Distribution
![Airline-wise Flight Fare Distribution](Airline%20-%20wise%20flight%20fare%20distribution.png)

### 2. Economy vs Business Fare Comparison
![Economy vs Business Fares](Economy%20vs%20Business%20fares%20Across%20Airlines.png)

### 3. Booking Window Analysis
![Median Fares Across Booking Windows](Median%20fares%20across%20booking%20windows.png)

### 4. Flight Duration vs Ticket Price
![Flight Duration vs Ticket Price](Flight%20duration%20against%20ticket%20price.png)

### 5. Departure Period Analysis
![Flight Fares Across Departure Periods](Flight%20fares%20across%20departure%20periods.png)

## 8. Business Recommendations

Based on the observed patterns:

1. **Advance Booking Strategy:** Travel agencies can encourage customers to book earlier through advance-booking notifications and fare alerts.
2. **Budget Travel Recommendations:** Afternoon departures and airlines with lower observed median fares can be highlighted as potential budget-friendly options.
3. **Class-based Pricing:** Airlines can develop customized Business-class packages and targeted corporate travel offers.
4. **Fare Comparison:** Travel platforms can provide airline-wise and route-wise fare comparisons.
5. **Multivariable Analysis:** Flight duration, travel class, booking window and airline should be considered together when studying airfare variations.

## 9. Limitations

- Findings are based on historical booking observations and may not represent current market prices.
- The dataset may contain sampled booking options rather than a complete schedule of all flights.
- Business-class observations are available only for selected airlines.
- Correlation does not establish causation.
- Seasonal demand, holidays, promotions and real-time pricing strategies may also influence fares.

## 10. Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand variations in Indian domestic flight ticket prices.

The analysis identifies differences in airline-wise fares and travel-class pricing. It also highlights the relationship between advance booking time and ticket prices, while flight duration shows a weak positive association with airfare.

Overall, the project demonstrates the practical application of Python-based data analysis, statistical techniques and data visualization in the travel industry.

## 11. Project Files

| File | Description |
|---|---|
| `Flight_Fare_Analysis.ipynb` | Complete Jupyter Notebook containing analysis, code and outputs |
| `INDIAN FLIGHT FARE ANALYSIS AND PREDICTION.pdf` | Project report |
| `Clean_Dataset.csv` | Dataset used for the analysis (shared separately if not uploaded to GitHub) |

## 12. References

1. Kaggle – Flight Price Prediction Dataset.
2. [Pandas Documentation](https://pandas.pydata.org/docs/)
3. [NumPy Documentation](https://numpy.org/doc/)
4. [Matplotlib Documentation](https://matplotlib.org/)
5. [Seaborn Documentation](https://seaborn.pydata.org/)

---

**Developed as part of the BLEEP Education Data Science Training & Internship Programme.**
