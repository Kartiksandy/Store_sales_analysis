## Predictive Analysis Exercise: Store Sales

This project involves performing time series analysis and forecasting on store sales data. The goal is to build predictive models to forecast future sales based on historical data. The notebook utilizes statistical methods to decompose, analyze, and predict sales trends.

### Project Overview:

1. **Objective:**
   - The primary goal is to forecast future store sales using historical sales data, focusing on furniture and office supplies categories.

2. **Data Visualization:**
   - **Time Series Plot:** The historical sales data is visualized to identify patterns, trends, and seasonality in the dataset.
   
  <img width="984" alt="image" src="https://github.com/user-attachments/assets/1bd15033-ab01-4bd3-9cec-813f6c061e37">


   - **Seasonal Decomposition:** The time series data is decomposed into trend, seasonal, and residual components to better understand the underlying patterns.
   

<img width="1083" alt="image" src="https://github.com/user-attachments/assets/fdfaef18-794b-46ef-a3b5-46d8053f3dbb">


3. **Model Building:**
   - **ARIMA Model:** 
     - An ARIMA (AutoRegressive Integrated Moving Average) model is built to forecast sales based on the identified trends and patterns in the historical data.
   - **Model Diagnostics:** 
     - Diagnostic plots are generated to investigate any unusual behavior and validate the model assumptions.
     
<img width="728" alt="image" src="https://github.com/user-attachments/assets/bbd22232-db53-46cd-ace0-3460e192aea3">


4. **Model Validation and Forecasting:**
   - **One-Step Ahead Forecast:** 
     - The model's performance is validated by comparing the forecasted values with the actual sales data.
     
<img width="651" alt="image" src="https://github.com/user-attachments/assets/4c187ab7-2443-486d-9867-ede54db4ebb4">


   - **Future Sales Forecast:** 
     - The model is used to produce and visualize forecasts for future sales, providing insights into expected sales trends.
       
     
<img width="642" alt="image" src="https://github.com/user-attachments/assets/48bee844-a80c-4c6b-95a9-11c5d880a569">


5. **Comparison of Sales Categories:**
   - **Sales Comparison Plot:**
     - A comparison plot of furniture and office supplies sales is generated to analyze the differences and similarities in sales trends between the two categories.
     

<img width="756" alt="image" src="https://github.com/user-attachments/assets/72adee1f-ebc0-4d74-87f9-0a38da380433">


### How to Use:

1. **Clone the Repository:**
   - Clone this repository to your local machine using `git clone`.
   
2. **Install Dependencies:**
   - Install the required Python packages using `pip install -r requirements.txt`.

3. **Run the Notebook:**
   - Open the notebook in Jupyter and execute the cells in sequence to perform the analysis and generate the plots.

### Conclusion:

This project demonstrates the use of time series analysis and ARIMA modeling to forecast store sales. The insights gained from this analysis can be used to make informed business decisions, optimize inventory management, and plan marketing strategies based on predicted sales trends.
