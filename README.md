# MLPractice
This project used to practice ML and DL 

The related link: https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/


# Problems
### Further learning
https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/#h-9-dimensionality-reduction-algorithms
Number 10 10. Gradient Boosting Algorithms
GBM

## #Create a series with feature importances:
featimp = pd.Series(model.feature_importances_, index=predictor_var).sort_values(ascending=False)
print (featimp)
