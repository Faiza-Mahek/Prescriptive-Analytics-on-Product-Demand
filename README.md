# Prescriptive Analytics on Product Demand

**Assigned On:** 16 Jan 2025 at 16:09:17  
**Due Date:** 23 Jan 2025  
**Status:** Complete

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Tools & Technologies](#tools--technologies)  
4. [Implementation Steps](#implementation-steps)  
5. [Presentation](#presentation)  
6. [References](#references)

---

## Project Overview

In this task, we explore **prescriptive analytics** techniques to optimize inventory management for a given product. By leveraging optimization algorithms, we aim to determine the best possible strategy to balance costs, maximize revenue, and improve overall profit.

**Key objectives include**:
- Applying **linear programming**, **integer programming**, and **mixed-integer programming** to optimize inventory decisions.  
- Evaluating the performance of the optimization solution using metrics like **cost**, **revenue**, and **profit**.  
- Performing **sensitivity analysis** to understand how changes in parameters (demand, lead time, holding cost, etc.) affect the optimal solution.

---

## Dataset

- **Name:** Product Demand Forecasting  
- **Source:** [Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting)  
- **Description:** Contains product demand history across different warehouses. Ideal for forecasting demand and applying prescriptive analytics to minimize costs and stockouts while meeting consumer demand.

---

## Tools & Technologies

- **Python (3.12)**  
- **Jupyter Notebook**  
- **Optimization Libraries**: e.g., **PuLP**, **OR-Tools**, **Pyomo**  
- **Data Handling & Visualization**: **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Statistical & ML Tools** (optional): If demand forecasting or advanced methods are needed prior to optimization.

---

## Implementation Steps

1. **Data Preparation**  
   - Download and load the “Product Demand Forecasting” dataset.  
   - Clean and structure the data for analysis (handle missing values, format date fields, etc.).

2. **Demand Forecasting (Optional)**  
   - Perform basic demand forecasting to predict future demand if needed for the optimization model.  
   - Validate the forecasted values using time-series metrics (MAE, RMSE, etc.).

3. **Formulating the Optimization Problem**  
   - Define variables (e.g., inventory levels, order quantities) and constraints (e.g., capacity, demand fulfillment).  
   - Set up the objective function (e.g., minimize total cost or maximize profit).

4. **Implementing Optimization Algorithms**  
   - Use **linear programming**, **integer programming**, or **mixed-integer programming** as required.  
   - Solve the optimization model with a library like **PuLP**, **OR-Tools**, or **Pyomo**.

5. **Evaluation & Metrics**  
   - Calculate cost, revenue, and profit for the final solution.  
   - Compare different modeling scenarios if multiple approaches are tested.

6. **Sensitivity Analysis**  
   - Alter key parameters (demand, holding cost, lead time, etc.) to see how the optimal solution changes.  
   - Document insights about the system’s robustness to parameter variations.

---

## Presentation

### PPT Link
> **[Click Here to View the Presentation Slides](https://www.canva.com/design/DAGc7ftbsC8/nAjiRZr6odSfG5aY0J9yUQ/edit)**

*(Replace the above link with your actual presentation URL once available.)*

---

## References

- **Product Demand Forecasting Dataset:** [Kaggle - felixzhao/productdemandforecasting](https://www.kaggle.com/felixzhao/productdemandforecasting)  
- **PuLP Documentation:** [coin-or.github.io/pulp](https://coin-or.github.io/pulp/)  
- **Pyomo Documentation:** [pyomo.org](http://www.pyomo.org/)  
- **OR-Tools:** [developers.google.com/optimization](https://developers.google.com/optimization)  
