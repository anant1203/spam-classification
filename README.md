# spam-classification
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

# Built With

- Python 3.6
- Apache Spark
- PySpark- Python API for Apache Spark 
- Jupyter Notebook 

# Dependencies 

### To use PySpark components
!pip install pyspark

# Approach:

### Pre Processing:
* we removed the unwanted expression from the data set
* we Tokenized it and used count vectorizer to form feature.
* we converted the string label to integer format.
* we used differnt algorithm of classification such as:
     * Random Forest Classification
     * Logistic Regression
     * Naive Bayes Classification
     * K Mean clustering
     * Support Vector Machine

# Result

| algorithm                    | accuracy |
|------------------------------|----------|
| Random Forest Classification | 0.94     |
| Logistic Regression          | 0.95     |
| Naive Bayes:                 | 0.98     |
| Support Vector Machine       | 0.96     |
| K Mean clustering            | 0.81     |

# Contributing 

There are no specific guidlines for contibuting. If you see something that could be improved, send a pull request! If you think something should be done differently (or is just-plain-broken), please create an issue.

# Authors 

Anubhav Nigam\
Anant Tripathi\
Priyank Malviya

# References 

https://towardsdatascience.com/multi-class-text-classification-with-pyspark-7d78d022ed35

https://spark.apache.org/docs/2.1.0/ml-features.html

https://www.kaggle.com/benvozza/spam-classification/data

# License

This Project is under the MIT License
