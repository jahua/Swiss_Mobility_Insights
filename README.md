## Conclusion
This project showcases the application of data data structure and analytics for comprehending shared mobility services. It highlights the importance of proper data pre-processing, data modelling and storage using MongoDB. Data visualisation of the dataset to gain meaningful insights, we performed some machine learning model analysis of a shared mobility dataset to gain insights, we also performed a simulation to categorise the accessibility and availability of vehicles in different communities.

The project consisted of several key components:

### Data Preparation

We started by cleaning and preprocessing the dataset. This involved handling missing values, data type conversions, and feature extraction.

### Data Exploration

We explored the dataset to better understand the distribution of variables, such as vehicle types, provider names, and the number of available stations in communes.

### Correlation Analysis

We performed a correlation analysis to assess the relationship between the population of communes and the number of shared vehicles available. The results indicated a weak negative correlation, suggesting that population size does not strongly influence vehicle availability.

### Machine Learning Model

To predict vehicle types based on available features, we built a classification model using the Support Vector Machine (SVM) algorithm. The model achieved an accuracy of around 71% on both training and test datasets.

### Accessibility Categorization

We introduced a categorization scheme for accessibility, classifying communes as "High," "Moderate," or "Low" based on vehicle variety and station availability.

### Data Visualization

We employed various data visualization techniques, including bar plots and pie charts, to visually represent the accessibility categories and make the data more comprehensible.


## Learning

The foundation of any robust data analytics project lies in data integrity, efficient modelling and an appropriate storage mechanism. In this project, the flexibility and scalability of MongoDB recognises their key role in unlocking meaningful insights. Careful data modelling, including filtering and structuring, was critical in preparing the data for deeper analysis, but also where and how it was stored. MongoDB, a flexible and scalable NoSQL database, has served as a robust repository, enabling seamless data integration and retrieval, and the integrity of our data and the efficiency of our modelling filtering mechanisms remain central to the success of the project.
Building on what we have learnt, we are also focusing on what we can do better for future projects.

- Future work could include collecting more comprehensive data, including additional demographic and geographic factors that might differentiate urban and suburban areas and impact shared mobility services, 
- Exploring advanced machine learning models and feature engineering could potentially improve prediction accuracy, forecasting and prediction.
- A more detailed analysis of the presence of each vehicle type in different municipalities could provide valuable insights.
- Temporal trends in shared mobility services could be further explored.

  ### Key Takeaways

- The correlation analysis pointed out that factors other than population size influence vehicle availability in communes.
- The SVM classification model demonstrated decent predictive capabilities for identifying vehicle types.

![Screenshot 2023-10-31 at 12 19 48](https://github.com/jahua/Swiss_Mobility_Insights/assets/16496916/958533b7-cd1c-4d21-aa31-300f28970943)
![Screenshot 2023-10-31 at 12 20 19](https://github.com/jahua/Swiss_Mobility_Insights/assets/16496916/cbba4627-8a7d-4741-8dce-b5c65ffd7fa1)
![Screenshot 2023-10-31 at 12 20 45](https://github.com/jahua/Swiss_Mobility_Insights/assets/16496916/0a691281-6f4d-4c21-b070-f989e2ccbd89)
![Screenshot 2023-10-31 at 12 21 05](https://github.com/jahua/Swiss_Mobility_Insights/assets/16496916/dc53d2d0-328c-4d35-9557-6408e28bbdd4)