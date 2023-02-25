Title: Predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud.

Description:Kaggle Dataset was used for this experiment. The data comes from Vesta Corporation – world’s leading payment service company, real-world ecommerce transactions and contains a wide range of features from device type to product features. The data is broken into two files identity and transaction, which are joined by TransactionID. Not all transactions have corresponding identity information. To merge the files, a left outer join was performed in order to retain all rows from transaction dataset. Another major challenge was how to handle many of the missing data. A number of approaches exists for handling missing data such as deleting the entire data instance, replacing with zero etc. In this case, there were many columns having higher percentage of missing values. Hence, the NaN values were replaced with zero to preserve the other attribute information available in those records. The categorical data was converted into numerical data.



