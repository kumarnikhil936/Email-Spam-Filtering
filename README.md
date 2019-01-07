
# Email-Spam-Filtering

Email spam filtering is a naive example of document classification task, where we classify a mail to be spam or non spam. Here we will be using the Linear SVM and Naive Bayes classifier to perform this task over two different types of dataset mentioned below. 

Dataset : https://aclweb.org/aclwiki/Spam_filtering_datasets
1. Ling-spam Corpus : A dataset that contains spam messages and messages from the Linguist list. 
2. Enron-spam : A collection of encrypted datasets that contain spam messages and ham messages from real users.

Data Preprocessing 
- Removal of stop words 'and', 'the', 'of', etc
- Grouping together (lemmatization) different inflected forms of a word like 'include', 'includes', etc
- Removing non-words like punctutation marks
- We will be looking only at the email content (3rd line) and not subject (1st line)

References : https://appliedmachinelearning.blog/2017/01/23/email-spam-filter-python-scikit-learn/
