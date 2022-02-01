# Insurance_CrossSell

#### Abstract:
Cross-selling is the action or practice of selling an additional product or service to an existing customer. The objective of cross-selling can be either to increase the income derived from the client or to protect the relationship with the client or clients. This project uses data provided by JantaHack to discover the problem if the customer who already purchased health insurance from one company, would be interested in the same company’s vehicle insurance, the logistic regression model with regularization and support vector machine (SVM) are used. After clarifying that the distribution of respond variable is unbalanced, two methods are utilized in these two models, including downsampling technique and weighted loss function. The data preprocessing process includes checking for missing values and selecting variables related to the response, and converting some categorical variables. Data description is carried out, related summary tables and plots are generated. To find the optimal penalized parameters, a 5-fold cross-validation grid search is performed on specific intervals. Logistic regression model and support vector machine model are established by using weighted loss function or downsampling method. Finally, the weighted logistic regression model with the highest area under the ROC curve (AUC) as 0.84476 is selected as the best model.
