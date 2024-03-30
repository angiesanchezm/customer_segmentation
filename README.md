# SEGMENTATION OF GASTRONOMIC CUSTOMERS OF AN E-COMMERCE

This project was carried out with the objective of proposing sales strategies to gastronomic clients through customer segmentation with an unsupervised learning algorithm.

* Perform cleaning and exploratory analysis of sales transactions data.
* Determine the RFM score of each client considering its recency, frequency and monetary value.
* Train the k-means model considering recency, frequency and monetary value as variables.
* Propose marketing strategies adapted to each segment of clients according to their characteristics.

### Installing dependencies
Install pandas, seaborn and scikit-learn libraries.
To install the project in local execute the next line in terminal:
```
pip install -r requirements.txt
```
### Instructions
To run the code succesfully, it is necessary to create a csv file containing at least the following fields:

* fecha_compra: Date of the purchase made by the customer.
* customer_id: Customer identification.
* type_id: Type of business.
* cantidad_venta: Quantity of products purchased.
* monto_venta_transf: Total purchase amount.
