# House-Price-Prediction

![house-price-forecast](https://github.com/anish2105/House-Price-Prediction/assets/71202304/1e3bc18d-dbe8-4711-a078-74ab866e21ca)

## Introduction

In this project, the objective was to predict house prices in 6 metropolitan cities of India. The dataset provided contained essential features and amenities of houses in these cities. To achieve accurate predictions, a systematic approach was followed, encompassing exploratory data analysis, feature engineering, model building, and hyperparameter tuning.

## Approach

1. **Exploratory Data Analysis (EDA):** The initial step involved comprehensive EDA to gain insights into the dataset's structure and characteristics. This allowed us to identify missing values, understand feature distributions, and uncover initial patterns.

2. **Data Visualization:** Visualizations were utilized to delve deeper into the dataset, revealing relationships between variables and uncovering trends. These insights provided the basis for subsequent feature engineering.

3. **Feature Engineering:** Missing values were a challenge in the dataset, represented by the value '9'. Traditional imputation methods like mean, median, or mode were not suitable. Hence, rows with missing values were removed. Although this resulted in reduced data, it was a necessary step to maintain data integrity and model accuracy.

4. **Feature Selection:** Leveraging the power of Random Forest modeling, important features were identified. These significant features were then chosen for building predictive models, ensuring the most relevant information contributes to the predictions.

5. **Model Building:** Three different models—Gradient Boost, Random Forest, and Decision Tree—were selected for predicting house prices. Models were built for each city, recognizing the distinct price ranges in each location. This approach provided tailored predictions that align with the unique housing dynamics of each city.

6. **Hyperparameter Tuning:** Despite initial model building efforts, results were refined through hyperparameter tuning. This step optimized model performance by fine-tuning parameters, enhancing accuracy, and mitigating overfitting.

## Conclusion

The project's approach of combining exploratory data analysis, strategic feature engineering, tailored model selection, and hyperparameter tuning resulted in accurate predictions for house prices across the 6 cities. Recognizing the diverse nature of housing markets in each city allowed for a more nuanced and realistic prediction framework. This approach not only improved prediction accuracy but also enhanced the understanding of how various features contribute to housing prices in different locations.

This GitHub repository showcases the project's code, data analysis, and model implementation. By following this approach, we successfully navigated the complexities of predicting housing prices in a diverse urban landscape.

---
## Run Locally

Clone the project

```bash
  git clone https://github.com/anish2105/House-Price-Prediction.git
```
All dependencies are already present in the notebook, just run all cells and feel free to experiment around!!!

---
## Thank You
Thank you for taking the time to explore this project! The journey from data exploration to model predictions has been an exciting one, and your interest in this work means a lot. If you have any questions, feedback, or suggestions, please feel free to reach out. Your insights and contributions are highly valued.


![housing_crash](https://github.com/anish2105/House-Price-Prediction/assets/71202304/b74ee84a-b34d-4755-981a-ca09b4f22db8)
