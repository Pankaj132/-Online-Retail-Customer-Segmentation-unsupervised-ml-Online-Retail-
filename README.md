# Online-Retail-Customer-Segment

![image](https://user-images.githubusercontent.com/99709967/208321981-aef60a43-3c2e-43e4-bb42-426c86bff746.png)

Customer segmentation is the process by which you divide your customers up based on common characteristics – such as demographics or behaviors, so you can market to those customers more effectively. These customer segmentation groups can also be used to begin discussions of building a marketing persona. This is because customer segmentation is typically used to inform a brand’s messaging, positioning and to improve how a business sells – so marketing personas need to be closely aligned to those customer segments in order to be effective.Customer segmentation is popular because it helps you market and sell more effectively. This is because you can develop a better understanding of your customers’ needs and desires. The business impact of doing this is even more important, and effective customer segmentation will help you to increase customer lifetime value. This means they will stay longer, and spend more. By better understanding the customer, and therefore being able to target them more effectively, you can drive greater loyalty.

# Data Set Information

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Attribute Information

Feature Description

InvoiceNo Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

StockCode Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

Description Product (item) name. Nominal.

Quantity The quantities of each product (item) per transaction. Numeric.

InvoiceDate Invoice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice Unit price. Numeric, Product price per unit in sterling.

CustomerID Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

Country Country name. Nominal, the name of the country where each customer resides.

# BUSINESS OBJECTIVE

Customer Segmentation is a most popular and common technique to used by the most of the e-commerce retail companies. In order to increase top line and bottom line of the company, they need to inspect some things where customer segmentation helps a lot. The goal of segmenting customers is to decide how to relate to customers in each segment in order to maximize the value of each customer to the business. Main objective is to find the solution of the following questions:

We want to know who my customers are(belongs to which class) What they like to purchase and in what amount they purchase? How frequent they purchase? When they purchase?(Seasonal, Festivals, occasionally) Which products are sold in large amount.

# Recency-Frequency-Monetary (RFM) model to determine customer value:

The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?

Frequency – How often do they purchase?

Monetary Value – How much do they spend?

A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

# Segmentation with K-means clustering:

Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton. Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm. The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.

# Conclusion:

K-Means Clustering with h Elbow Method and Silhouette Score , we can conclude that optimal clusters are 2..

Sales has been increased from 2010 to 2011.

RFM for Cluster ID box plots tells well about Cluster detail.
