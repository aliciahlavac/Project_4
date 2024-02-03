# Loan Approval Prediction

Loans are a very important part of financial institutions.  By analyzing loans, decisions can be made to save the institution a lot of money while keeping their customer satisfaction up.  Using a dataset from India, the following questions drove the research for this project:
* What factors influence loan approval?
* Does credit history specifically impact the loan approval decision?
* What role does employment type (self-employed versus non self-employed) play in loan approval?
* Can we predict loan approval determination with high accuracy?

# Results

Throughout this project, three models were created to see whether or not a we could predict loan approval determination with high accuracy; a logistic regression model, a decision tree model, and a random forest model were all created to see which one most accurately predicted what we wanted.  We found out that the tuned random forest model was most accurate, with statistics as follows:

![2024-02-03](https://github.com/aliciahlavac/Project_4/assets/127240852/b4a41bbb-95b7-4c2f-a6f3-a2a6538ae920)

We can see the model has a high accuracy, and high precision, recall and f1-scores, suggesting that the model is effiective in predicting loan approval status with minimal error rates. The high performance across all metrics suggests the model is well-tuned and robust, making it reliable for predicting loan outcomes based on the dataset's features.

## Authors

Alicia Hlavac
[Alicia Hlavac's GitHub](https://github.com/aliciahlavac?tab=repositories)

## Citations

* Choosing color palettes#. Choosing color palettes - seaborn 0.13.1 documentation. (n.d.). https://seaborn.pydata.org/tutorial/color_palettes.html 
* FAQs – understand your credit score and report. PERSONAL. (2022, December 22). https://www.cibil.com/faq/understand-your-credit-score-and-report#:~:text=Your%20CIBIL%20score%2C%20calculated%20based,%2C%20ranges%20between%20300%2D900. 
* How to remove space from columns in pandas a data scientists guide. Saturn Cloud Blog. (2023, October 25). https://saturncloud.io/blog/how-to-remove-space-from-columns-in-pandas-a-data-scientists-guide/#:~:text=Using%20the%20str.strip(),column%20names%20or%20column%20values. 
* Kai. (2023, July 16). Loan-approval-prediction-dataset. Kaggle. https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset 
* Matplotlib.pyplot.text#. matplotlib.pyplot.text - Matplotlib 3.8.2 documentation. (n.d.). https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.text.html 
* Pandas.DataFrame.unstack#. pandas.DataFrame.unstack - pandas 2.1.4 documentation. (n.d.). https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.unstack.html 
