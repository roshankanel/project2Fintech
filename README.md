<h1> One World Currency</h1>
This One World Currency (OWC) APP aims to provide various functionalities related to currency conversion, currency analysis, and currency forecasting. Our APP utilises the following steps to determine the “best investment outlook” for its user:
<br><br>
<b>- Currency Data Retrieval:</b> OWC retrieves currency data using the ExchangeRate-API to obtain the latest currency conversion rates.
<br><br>
<b>- Currency Conversion:</b> OWC allows users to convert an amount from one currency to another using the retrieved currency conversion rates.
<br><br>
<b>- Currency Map Visualisation:</b> OWC visualises the currencies on a map using the Folium library. The map displays markers for each currency, representing its location based on country coordinates.
<br><br>
<b>- Currency Analysis and Forecasting:</b> OWC performs currency analysis and forecasting using the machine learning models XGBoost and Random Forest. It trains the models on historical currency data and generates predicted prices for future dates. OWC also calculates the root mean squared error (RMSE) as an evaluation metric for the models.
<br><br>
<b>- Buy/Sell Signals:</b> OWC provides buy/sell signals based on the predicted prices compared to historical prices. It generates signals for each currency and plots the forecast results.
<br><br>
<b>- Best Investment Outlook:</b> OWC determines the currency with the most buy signals, the currency with the highest cumulative percentage change to USD, and the currency with the best investment outlook based on a combined score considering buy signals and cumulative change. 
<br><br>
<b>- Unique Algorithm:</b> The process to generating the currency with the best investment outlook, is an algorithm unique to OWC. 
<br><br>
<b>- Chatbot Interface:</b> Finally, OWC includes a chatbot interface powered by OpenAI's text-based language model. Users can interact with the chatbot to ask questions or seek any further assistance regarding currency-related topics.

## Before you run the application
 - You will find an ipynb file
    - FINALPROJECT.ipynb is where we have drawn our results from
 - Make sure you run below
    1. !pip install folium
    2. !pip install xgboost
    3. !pip install openai
    4. !pip install Console

## Below is the graphical forecast output (AUD, CHF, EUR) of our application
 ![](/Images/forecast_results_AUD.png)
 ![](/Images/forecast_results_CHF.png)
 ![](/Images/forecast_results_EUR.png)

## Below is the graphical training output (AUD, CHF, EUR) of our application
 ![](/Images/training_results_AUD.png)
 ![](/Images/training_results_CHF.png)
 ![](/Images/training_results_EUR.png)

## Below is the graphical forecast for AUD only
  ![](/Images/AUD_forecast_plot.png)
  
## Below is the graphical forecast for CHF only
  ![](/Images/CHF_forecast_plot.png)
  
## Below is the graphical forecast for EUR only
  ![](/Images/EUR_forecast_plot.png)



## Conclusion
The One World Currency (OWC) APP provides users with a robust and versatile toolkit. By seamlessly integrating features such as data retrieval, conversion, visualisation, analysis, forecasting, investment insights, and chatbot interaction, the application enhances the user experience, facilitating informed decision-making in the realm of global currencies. OWC empowers users to navigate the complexities of the financial landscape, enabling them to make intelligent and well-informed choices regarding currency transactions and investments.

