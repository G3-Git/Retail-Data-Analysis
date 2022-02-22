# Retail-Data-Analysis
Digitally enabled customers like to shop on the run, and that is the reason why online shopping is one of the most popular online activities worldwide. In 2019, global e-commerce sales amounted to 3.53 trillion USD and are projected to grow to 6.54 trillion USD in 2022.     The analytical capabilities of big data have had a positive impact across industries, including e-commerce. Big data tools improve business performance by enabling companies to analyse trends and current consumer behavioural patterns and offer better and more customised products.   
For the purposes of this project, we have been tasked with computing various Key Performance Indicators (KPIs) for an e-commerce company, RetailCorp Inc. We have been provided real-time sales data of the company across the globe. The data contains information related to the invoices of orders placed by customers all around the world.

At the industry level, an end-to-end data pipeline is built for this purpose. Tools such as HDFS(Hadoop Distributed File System) are used to store the data that is processed by the real-time processing framework and then shown on a dashboard with tools such as Tableau and PowerBI.



As part of this project, we have performed the following tasks in this project:

Reading the sales data from the Kafka server

Preprocessing the data to calculate additional derived columns such as total_cost etc

Calculating the time-based KPIs and time and country-based KPIs

Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis
