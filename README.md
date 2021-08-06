# Amazon_Vine_Analysis

## Challenge Overview:
*Use  and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.*

*Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.*

*Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.*

### Deliverables:
- Deliverable 1: Perform ETL on Amazon Product Reviews
- Deliverable 2: Determine Bias of Vine Reviews
- Deliverable 3: A Written Report on the Analysis (README.md)

### Resources:
- Data Sources:
  - [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
 
- Software:
  - PostgresSQL
  - pgAdmin 4
  - AWS
  - Google Colab

## Challenge Results:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:
  - How many Vine reviews and non-Vine reviews were there?
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

### Total Reviews:

![1](https://user-images.githubusercontent.com/36451701/128567224-5d1f8262-d411-4b34-b5bc-982bcc0a68b5.png)

![4](https://user-images.githubusercontent.com/36451701/128567258-0479b97e-b390-49e0-93c4-ac1d9a1aa90c.png)

### Total 5-Star Reviews:

![2](https://user-images.githubusercontent.com/36451701/128567245-db73b1ed-3fe2-4ac3-a410-f99057685ec7.png)

![5](https://user-images.githubusercontent.com/36451701/128567268-2eaaae4d-7213-476f-96f8-a8b8ef6af94d.png)

### Percentage of 5-Star Reviews:

![3](https://user-images.githubusercontent.com/36451701/128567253-b2d5d841-c6ea-4679-8d6f-42065d7660da.png)

![6](https://user-images.githubusercontent.com/36451701/128567278-12bbcefc-a1f1-49dd-98a1-5fdb4bad1c1a.png)


## Challenge Summary:

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.


