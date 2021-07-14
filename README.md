
# Customers Segmentation
------
1. [Project Overview](#ProjectOverview)
2. [Installation](#installation)
3. [Data Exploration](#data)
4. [Implementation](#model)
5. [Results](#results)
6. [Contributors](#Contributors)
7. [Acknowledgements](#acknowledgements)

## 1. Project Overview <a name="ProjectOverview"></a> 

Customer Segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. 

The aim of this project is to helps Mandob Tuwiaq founders to understand their customers and applying different marketing approaches by build clustering models.

## 2. Installation <a name="installation"></a>

- Python versions 3.*.
- Python Libraries:
    - matplotlib.
    - seaborn.
    - sklearn.
    - Pandas.
    - plotly.
    - numpy.


## 3. Data Exploration <a name="data"></a> 

Data used in this project was provided from Mandob Tuwaiq delivery app. The dataset contains 3 tables:
- Orders: 26 features
- Users: 12 features
- OrderPayment: 6 features
 
#### 1- Who are user types mainly using the app's services?

![image](https://user-images.githubusercontent.com/81440100/125507948-ab2d1830-4a97-40b2-b073-a5955714dbf7.png)
 
The figure shows that the most user type are using the app for is buyer with 95.67%.

#### 2- How can the user pay in mandoob tuwaiq app? What are the most used Payment methods?
![image](https://user-images.githubusercontent.com/81440100/125504560-9165bcbd-3e22-4a22-9c86-69df1c7a2356.png)

The figure shows that the product category Food is the most used cash payment method with 500 orders.

#### 3- What products are user's mostly using the app's services for?

![image](https://user-images.githubusercontent.com/81440100/125507612-e2bdc51e-786d-48e0-8b60-8a54618c77d3.png)

The figure shows that the most product that customer's are using the app for is food with 41.51%.

#### 4-Do the customers cancel their orders in Tuwaiq?
![image](https://user-images.githubusercontent.com/81440100/125507782-a0072423-2045-4400-902e-733a46b6c563.png)

 The figure shows that the number of confirmed orders are high given the number of accepted orderes, in comparision to the cancelled orders. 



## 4. Implementation <a name="model"></a> 
In this project, we built two clustering models using Kmean and DBSCAN algorithms from **[Sklearn](https://scikit-learn.org/stable/)**, with the following features:
  - Number of Orders
  - Total payment 
  - Orders paid by Card
  - Orders paid by Cash
  - Orders paid by STCPay
  - Orders product categories


## 5. Result<a name="results"></a> 
This animation shows the result for both models.
![Results](https://user-images.githubusercontent.com/42017072/125319024-120ba880-e343-11eb-8d25-8abace9a2e2b.gif)


## 6. Contributors<a name="Contributors"></a> 
- [Wajd Alturki](https://github.com/wajdalturki)
- [Mashael Alhassan](https://github.com/mashaelalhassan)
- [Lama Alzahrani](https://github.com/ldfjre)
- [Zarah Shibli](https://github.com/ZarahShibli)

## 7. Acknowledgements <a name="acknowledgements"></a> 
We wish to thank [Mandob Tuwaiq](http://mandobak.sa/) for giving us the opportunity to work on the data.. Also,Thanks, [Saudi Digital Academy](https://sda.edu.sa/)  and [Coding Dojo](https://www.codingdojo.com/) to help and guide us during the data science Bootcamp. For more details about this project can read this [article](https://medium.com/@lamaalzahrani353/3ae4d6cfd41d) and [Poster](https://www.canva.com/design/DAEj-CS_1zM/QfCQJp3WazP1bnR8EWL-AA/view?website#4). Also,  you could checkout [our dashboard](https://customer-segmentation-tuwaiq-2.herokuapp.com/) to view the full insights we’ve analyzed we’ve found.
