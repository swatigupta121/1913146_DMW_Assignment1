# 1913146_DMW_Assignment1
## Apriori Algorithm

This is a simple implementation of Apriori Algorithm in Python. It takes in a csv file with a list of transactions, and results out the most frequent itemsets. The values for minimum_support should be given from the user at the runtime.

### Input

The input format should be csv file in following format:

A,B <br>
A,B,C <br>
C,D <br>
B,C,D so on..

For uploading csv file, We have used following method:

df=pd.read_csv(io.BytesIO(uploaded['basket_data.csv']),header=None)

Here, enter the csv file name in the method or rename the csv file name as dataset.csv.

### Output
The output will show the most frequent itemsets from the given dataset.

### Submitted By - Swati Gupta
### Roll no - 1913146
