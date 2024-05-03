# Amazon E-commerce Customer Analysis - Linear Regression

## Project Summary
This project analyzes customer data from Amazon_cloths, an online clothing store. The company aims to determine whether they should focus their efforts on improving their mobile app experience or their website. The analysis utilizes linear regression to predict customer spending based on various features.

## Dataset Overview
- The dataset contains information on customer attributes and spending behavior, including email, address, avatar, average session length, time spent on the app, time spent on the website, length of membership, and yearly amount spent.
- There are 500 observations in the dataset.
- Data analysis involves descriptive statistics, data visualization, and regression modeling.

## Data Analysis
- Descriptive statistics:
  - The dataset consists of numerical features such as average session length, time on the app, time on the website, length of membership, and yearly amount spent.
  - Summary statistics provide insights into the central tendency and variability of the data.

- Data Visualization:
  - Jointplots and pairplots are used to explore relationships between features and yearly amount spent.
  - Correlation analysis indicates that the length of membership is the most correlated feature with yearly amount spent.

## Linear Regression Modeling
- The analysis utilizes linear regression to predict yearly amount spent based on customer attributes.
- Model training involves splitting the data into training and testing sets.
- Features used for prediction include average session length, time on app, time on website, and length of membership.
- The trained model is evaluated using mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).

## Conclusion
- The coefficients of the linear regression model suggest that length of membership has the highest influence on yearly amount spent, followed by time on app and average session length. Time spent on the website has a minimal impact on spending.
- Based on the analysis, the company should focus more on improving the mobile app experience to enhance customer spending.
- Further analysis and experimentation may be needed to optimize customer engagement and increase overall revenue.

## Contact
For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com](mailto:sayak.kr.dutta1@gmail.com).

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

Thank you for your contribution to the analysis.
phics, purchase history) for a more comprehensive analysis.
Investigate alternative models (e.g., decision trees) for potentially better prediction accuracy.


