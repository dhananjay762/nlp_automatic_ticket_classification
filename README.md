# Automatic Ticket Classification based on Topic Modelling


For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 


In this case study, We have built a model that is able to classify customer complaints based on the products/services. With this, we can segregate these tickets into their relevant categories and therefore, help in the quick resolution of the issue. The data set given is in json format and contains around 78k+ customer complaints and are not labelled. We have used Non-negative Matrix Factorization (NMF) approach for topic modelling which can detect patterns and recurring words present in each ticket. It is an unsupervised learning which classifies the ticket into the following 5 clusters since this data is not already labelled.
1. Credit card / Prepaid card
2. Bank account services
3. Theft/Dispute reporting
4. Mortgages/loans
5. Others 

Once we have mapped each ticket onto its respective department/category i.e. labelled dataset, as a next step, we have used this data to train supervised learing model such as Logistic Regression, Decision Tree, Random Forest and Naive Bayes which can classify any new customer complaint support ticket into its relevant department. So broadly speaking, this case study is a perfect example where we can apply both unsupervised and supervised learning algorithms. 

