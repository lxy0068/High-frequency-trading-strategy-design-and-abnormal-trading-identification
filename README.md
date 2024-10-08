# High-frequency-trading-strategy-design-and-abnormal-trading-identification

Machine Learning Assignment (Autumn 2023)

Project Introduction: Application of Machine Learning on Hang Seng Index Daily Data and 5-minute Data
This project aims to use machine learning methods to implement index enhancement strategies through in-depth analysis and modeling of Hang Seng Index daily data and 5-minute data, thereby obtaining excess returns. 
The project spans from November 17, 2020 to November 17, 2023, with an initial capital of 1,000,000 yuan.

1. Data preprocessing and factor mining:
Preprocess the provided daily data and 5-minute data, including missing value processing, data standardization, etc.
Review relevant information and mine factors related to the Hang Seng Index, such as technical indicators, market sentiment indicators, etc.

3. Machine learning model for daily data:
Build machine learning models, including LSTM models and Transformer models, for predicting daily data. Design training sets, test sets, and validation sets, and use these data for model training and evaluation. For the prediction period, implement daily, weekly, and monthly index predictions.

5. Model and trading strategy for 5-minute data:
Use 5-minute data to build a model and find the best intraday buy and sell timing signals.
Combining the daily forecast results with the intraday buy and sell signals, write a specific trading strategy to achieve index enhancement and obtain excess returns.

7. Control the maximum drawdown and visualize the display:
Ensure that the final strategy achieves index enhancement and controls the maximum drawdown within a reasonable range.
Use visualization tools to display investment results, including strategy yield curves, trading signals and actual trading conditions.

9. Algorithm and model selection:
Use LSTM model and Transformer model to process daily data to capture time series relationships and long-term dependencies.
Use Markov decision process model to process 5-minute data and optimize intraday trading decisions.
Build a multi-factor stock selection model to comprehensively consider the impact of multiple factors on the investment portfolio.

| Team Member   | Responsibilities                                                                                                                                 |
|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| Xingyan Liu    | Data preprocessing and visualization, factor extraction, writing and training the hidden Markov stock timing strategy model, completing backtest evaluation metrics and strategy evaluation visualization. |
| Yanzhi Liu    | Writing and training a transformer-based sliding window stock prediction model, writing and training a random forest-based dynamic stock selection model. |
| Shiyi  Wang   | Writing LSTM code, training the LSTM model, using the LSTM model to predict stock and Hang Seng Index trends.                                       |

![image](https://github.com/user-attachments/assets/a44dada3-9836-4a2a-989e-747a404dc189)
![image](https://github.com/user-attachments/assets/b2d355fe-8347-4e38-8049-a2df2e1d6e76)
![image](https://github.com/user-attachments/assets/98b86973-d5c2-4e98-9198-c53d11e0d312)
![Moving_Averages_00001](https://github.com/user-attachments/assets/66b6ad23-76b8-4f76-b285-7d2a780eaec5)
![Candlestick_Volume_00001](https://github.com/user-attachments/assets/702f9057-c31e-4e66-831d-2e716588a424)
![image](https://github.com/user-attachments/assets/ddcae1c3-3742-42fa-83ef-0339d1d10dc0)
![image](https://github.com/user-attachments/assets/11916830-27b5-4dbe-9d72-37c364cca6db)
![image](https://github.com/user-attachments/assets/288d76a1-7a81-4fa5-a30f-4ef7bc15d60c)
![image](https://github.com/user-attachments/assets/241bb2e8-9e9f-4255-a95a-77a59ca23d77)
![image](https://github.com/user-attachments/assets/fa2473c3-136a-4c14-9e25-56782886d698)
