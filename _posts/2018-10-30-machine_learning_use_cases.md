---
layout: post
title:  "Data science and machine learning applications for business success"
author: weisseo
categories: [use case, business]
image: assets/images/machine_learning_use_cases/Churn.png
mathjax: true
---

In the last years technologies like data science, artificial intelligence
and predictive analytics have become increasingly popular.
The academic field behind these technologies is called “machine learning”.
The core idea is that the computer (“machine”) learns autonomously from data and generates
business insights and leads to data-driven decision making.
In this article we will discuss where and how these techniques are applied in industry.

## Advertising, Sales & Customer Experience

There are a lot of machine learning applications that are used on customer data.
The key idea is to get some insights about your customer so that you know when,
what or even if it is worth it to sell, contact or offer.
If other companies have the same customers, data or insights can be sold.

### Targeted Marketing

The most popular technique in advertising probably is targeted marketing.
Every individual is advertised differently so that the probability of action like a
click on your advertisement is maximized.
In order for the machine to learn, it needs positive and negative examples in the data.
A positive example would be data from people that clicked on advertisements in the past
and negative examples are where advertisements did not work.
In online advertising click rates are recorded automatically, which makes it optimally suitable for machine learning.
But also in mailed advertisements it is possible to record response rates and let the machine learn from the data.

![png](/assets/images/machine_learning_use_cases/targeted_marketing.png)

Targeted marketing ist most famously used by Facebook and Google.
The content of the advertisements is optimally chosen from your past click behaviour.
The advertiser has the advantage to only approach people where the effort is most effective,
and the users only get advertisements that might be interesting for them.

### Churn Prediction

Very often it can be foreseen that a customer will switch to a competitor.
Possible predictors are decreasing use of your service, increasing complaints or something
less obvious like using a different vocabulary in the written communication.
If you have enough examples of churns in your client data, machine learning can autonomously
find patterns and predict the churn before it happens.
With these warnings, you can try to convince the customer by, for example, special offers.

![png](/assets/images/machine_learning_use_cases/Churn.png)

The American delivery service FedEx used this technique to predict to 65%-95% if a client will
switch to a competitor.
Another company which can predict if a client will quit service is PayPal.
They use written client feedback to classify their users into high and low risk groups and are able to
predict with 83% accuracy if a client will quit their service.

### Recommender Systems

Similar clients are interested in similar products.
This fact can be used to recommend your clients the right product.
If you have client ratings from your users, this data can be used to predict how much a
client will like a product she has not rated yet.
But even knowing only which client bought which item can be enough to recommend appropriate products.

![png](/assets/images/machine_learning_use_cases/amazon_recommender_systems.png)

Very famous examples of these techniques are Amazon.com and Netflix.
They use their client ratings to recommend you products or movies.
At Amazon.com you have, for example, the features "Customers who bought this item also bought these items."
or "These items are frequently bought together".
Any modern eCommerce company uses these kinds of techniques nowadays.

## Product / Process Improvement and Maintenance

Machine Learning is also used to make improvements in products or business processes.
With help of these technologies certain problems that previously could only be solved by humans,
can now be solved by computers and therefore make your business more efficient.
Furthermore, computers can see far more data than humans and can predict,
for example, system failure that previously could not be detected at all.

### Predictive Maintenance

The techniques that predict system failure before it has happened,
are called predictive maintenance.
Engineering companies predict from sensor data such as temperature or pressure if their machines will fail in advance.
This helps them to service them before a complete damage, which can have huge costs, will happen.
Sensor data could also be camera images.
For example, camera images of your products can be classified into the categories "damaged" and "not damaged".
Techniques involving images are often summarized under the name computer vision.

![jpeg](/assets/images/machine_learning_use_cases/predictive-mainenance.jpg)

To name two examples, the American railway company TTX uses predictive maintenance
to predict the failure probability for each of hundreds of thousands of railcar wheels in
order to forecast overall annual inventory and maintenance need within a 1.5 percent margin.
Con Edison from the energy sector predicts failure of energy distribution cables,
updating risk levels that are displayed on operators' screens three times an hour.

### Improving Support Channel Efficiency

A lot of support channels are separated into several categories and for each of them there are specialists
to respond to the specific tickets.
To get directed to the right support channel, either the client has to pick the right one herself or a
member of staff has to do that.
Classifying text into predefined categories is a classical task in machine learning and can therefore be automated.
If you have historical data where client feedback is directed to the correct support channel,
the machine can learn from that.
If the support channel is based on verbal communication, in order to be analyzed,
a transcript of the spoken words is needed.
With the help of speech recognition techniques these transcripts can be generated automatically.

Citibank uses machine learning to make their support channel more efficient.
They classify their written client feedback and direct it automatically to the right
support channel and thereby make their business more efficient.

### Predicting Sales

For retail companies, predicting the sales of store items helps planning how much of each product
needs to be kept in the warehouse.
Store sales are influenced by many factors, including promotions, competition, school and state holidays,
seasonality, and locality. The complexity of this tasks makes it difficult to be done by humans.

In 2015, the German store Rossmann was confronted with this task.
The store managers were tasked with predicting their daily sales for up to six weeks in advance.
They outsourced their problem to the data science competition website Kaggle.com.

If you are interested in how sales prediction works from a data science perspective,
you might want to check out our article about sales prediction.

### Fraud Detection and Financial Risk Management

For financial institutions it is crucial to find frauds or classify people into risk groups.
Frauds can often be found through their abnormal behavior.
For example, when a credit card gets stolen, it will have a lot of abnormal purchases on it.
The techniques which are used to find unusual patterns in large sets of data are called anomaly detection.
With historical client data, it can also be calculated how likely it is for a customer to pay back a loan.
This has proven to be very helpful for financial risk management.

![jpeg](/assets/images/machine_learning_use_cases/fraud.png)

There are several companies who use these kinds of techniques in their business.
Brasil Telecom predicts, which clients will not pay back their loan and could save 4 million US dollar.
Canadian Tire manages their risk by predicting which clients are likely to pay back their loan late.

### Process Improvements in Logistics

Forecasting methods are also used in logistics in order to make process improvements.
For a delivery service, it might be helpful to have a prediction of the destination addresses in advance.
This helps to plan the optimal route.
From GPS data, it can also be predicted if a courier is late and inform the receiver.

Continental Airlines is making use of these techniques to predict late flights and UPS predicts
the destination addresses to plan the optimal route.

![jpeg](/assets/images/machine_learning_use_cases/logistics.jpg)
