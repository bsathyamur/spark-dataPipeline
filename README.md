# Building a spark data pipeline using pyspark

The goal of the project is to use the walmar_sales.csv file data, upload to the azure blob container, perform the following processing steps in the file, split the files based on country (Uk and others) and upload to the output blob container.

Processing steps performed:
1. Convert null customer ID to Guest
2. Convert null description to Unlisted
3. Add quarter based on purchase date
4. Add invoice type column based on purchase amount - zero for return else purchase

# Output files written to the output blob container

![img](https://github.com/bsathyamur/spark-dataPipeline/blob/main/blob-output.png)
