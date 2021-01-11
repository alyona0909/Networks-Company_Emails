# Networks : Company_Emails

This project making predictions about networks : will edges be formed. We will using a company's email network email_prediction.txt.

## Data

* `email_prediction.txt` : each node corresponds to a person at the company, and each edge indicates that at least one email has been sent between two people. The network also contains the node attributes Department and ManagementSalary.
* `Future_Connections.csv` : the index is a tuple indicating a pair of nodes that currently do not have a connection, and the Future Connection column indicates if an edge between those two nodes will exist in the future, where a value of 1.0 indicates a future connection.

## Content

* `Company_Emails.ipynb` : notebook to predict whether or not these individuals are receiving a management position salary and predict future connections between employees of the network. The `GradientBoostingClassifier` model was used.
