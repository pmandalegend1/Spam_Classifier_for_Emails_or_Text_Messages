Project: - Spam Classifier for Emails or Text Messages
A very accurate Email / Text message spam classifier. Primarily uses Multinomial Naive Bayes (Precision - 100 %) but also compares the metrics with other models like Random Forest, Logistic Regression and XGBoost in the end. 

Link to the Dataset used :- https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv

Parijat Mandal, Roll No- 125CS0011
NIT Rourkela CSE Freshman

Here, I have chosen Multinomial Naive Bayes since it had a Precision of 100%. In terms, of messages, it is very important to not mark an important Message or email as spam. Even though other models produced better metric scores in terms of F1, Recall. The precision undoubtedly turns out to be the most important feature in there. One cannot risk loosing out to view an Interview call or something as much as important.
Though XGBoost gave better results for all other metrics except the precision, my long experience with XGBoost says that it classifies very aggressively, meaning it brings in more false positives and that's why precision is lesser than Multinomial Naive Bayes.

The final F1 Score that could be achieved is 86.1789.

Learning Resources - CampusX Machine Learing, My School's Computer Teacher, GFG tutorial site for machine learning.
