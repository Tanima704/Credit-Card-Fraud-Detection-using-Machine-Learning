Title: Predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud.

Description:Kaggle Dataset was used for this experiment. The data comes from Vesta Corporation – world’s leading payment service company, real-world ecommerce transactions and contains a wide range of features from device type to product features. The data is broken into two files identity and transaction, which are joined by TransactionID. Not all transactions have corresponding identity information. To merge the files, we performed a left outer join in order to retain all rows from transaction dataset. Another major challenge was how to handle many of the missing data. A number of approaches exists for handling missing data such as deleting the entire data instance, replacing with zero etc. In our case, there were many columns having higher percentage of missing values. Hence, we replaced the NaN values with zero to preserve the other attribute information available in those records. We converted categorical data into numerical data.



