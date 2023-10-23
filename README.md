# SyrialTel Customer Churn Prediction
# Project Overview

To develop a model to predict SyrialTel customer churn. SyriaTel is a company in the telecom business
## Data source
I have chosen a dataset from the curated list, here is the link

https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset
## Project objective

To building a classifier to predict SyrialTel customer churn so that we can help  the company implement methods for reducing customer attrition and retaining business.
## Methods:
The project adopts the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, which encompasses several stages: data understanding, data preparation, modeling, evaluation, and deployment. In the modeling phase, a range of predictive models will be constructed and assessed. The process will commence with a fundamental logistic regression model and progress towards more intricate models like Decision Trees. Performance evaluation will be conducted using metrics such as accuracy, precision, recall, and F1-score.
## Business Problem
The business problem is to identify customers from the customer base of a telecommunications company who exhibit a high likelihood of churning, indicating their potential to discontinue using the company's services. This identification will facilitate the development of effective strategies by the telco to retain these customers and enhance overall business performance.Its known that retaining a customer is less expensive than getting new customers.
**A Summary of the dataset columns**

1. state: The state in which the customer resides (categorical).

2. account length: The length of time the customer has had an account with the company (numerical).

3. area code: The area code associated with the customer's phone number (categorical).

4. phone number: The customer's phone number, likely unique to each customer (string).

5. international plan: Whether the customer has an international calling plan (binary - yes/no).

6. voice mail plan: Whether the customer has a voicemail plan (binary - yes/no).

7. number vmail messages: The number of voicemail messages the customer has (numerical).

8. total day minutes: Total minutes used during the day (numerical).

9. total day calls: Total calls made during the day (numerical).

10. total day charge: Total charge for day usage (numerical).

11. total eve minutes: Total minutes used during the evening (numerical).

12. total eve calls: Total calls made during the evening (numerical).

13. total eve charge: Total charge for evening usage (numerical).

14. total night minutes: Total minutes used during the night (numerical).

15. total night calls: Total calls made during the night (numerical).

16. total night charge: Total charge for night usage (numerical).

17. total intl minutes: Total international minutes used (numerical).

18. total intl calls: Total international calls made (numerical).

19. total intl charge: Total charge for international usage (numerical).

20. customer service calls: Number of calls to customer service (numerical).

21. churn: Target variable indicating whether the customer has churned or not (binary - True/False).
22. ## Conclusion on the 3 model adopted

* Based on the three models the accuracy in making predictions of customer churn are as follows: 
* Logistic regression performs poorly  with `85.1%`
* Random forest classifier has `87.1%` accuracy
* Decision trees perform pretty well with `91.5%` .
  Here are the AUC scores for each model:

- Logistic Regression: AUC = 0.83
- Decision Tree: AUC = 0.91
- Random Forest: AUC = 0.85

In summary, the ROC curves and AUC scores provide a visual and quantitative assessment of the models' ability to discriminate between the classes. A higher AUC score generally suggests better performance. Based on these results, the Decision Tree model has the highest AUC score, indicating it is the most effective at distinguishing between the classes in SyriaTel dataset.Followed by the Random Forest and lastly the Logistic Regression models.
### SUMMARY: CONCLUSION AND RECOMMENDATIONS
- After developing and training the 3 classifications models, I went ahead th evaluate the models using appropriate metrics as evidenced above. The Decision Tree model emerged as the best model with a robust performance.
- We will integrate the Decision Tree model into SyriaTel existing systems for seamless prediction of customer churn.
- I will establish a monitoring system to track the model performance in real time and conduct periodic model re-evaluations and updates as necessary.

### THE IMPLEMENTATION OF THE MODEL WILL ACHIEVE THE FOLLOWING OBJECTIVES
 
 1. **Reduce Customer Churn Rate:** The Decision Tree is a predictive model that accurately identifies customers at risk of churning. By doing so, we aim to reduce the overall customer churn rate and subsequently minimize revenue loss.

2. **Increase Customer Retention:** SyrialTel will implement targeted retention strategies for the identified at-risk customers. This includes personalized offers, improved customer service, and proactive communication to encourage continued business with SyriaTel.

3. **Optimize Marketing Spend:** By predicting customer churn, we can allocate marketing resources more efficiently. Focus can be shifted towards retaining high-value customers and acquiring new customers, rather than expending resources on customers likely to churn.

4. **Improve Customer Satisfaction:** Understanding the factors leading to churn enables us to address pain points and enhance the overall customer experience. This, in turn, contributes to improved customer satisfaction and loyalty.
