# Flow chart of the Forex Data Pipeline

1. check availability of forex rates
2. check availability of the file having currencies to watch
3. download forex rates with python
4. save the forex rates in HDFS
5. create a hive table to store forex rates from the HDFS
6. process forex rates with Spark
7. send an email notificatoin
8. send a slack notification
