# *Customer Segmentation*
<br>
Customer segmentation is the process of dividing a company's customers into groups based on common characteristics. These groups, or 
segments, are created to help businesses better understand their customers and tailor their marketing and sales efforts to each specific group.

<br>

  This project aims at creating segments based on customers purchase behaviour and create a clustering model to group the customers by purchasing 
behaviour and also by demographics. The resulting segments can be used to target marketing campaigns, personalize product 
recommendations, and improve customer satisfaction. Data collected from an online retail store.


## **Table of Contents**
* Project Structure
* Requirements
* Procedure
* Results


## *Project Structure*
* Data collection and cleaning.
* Data preprocessing and transformation.
* Data Clustering and analysis.
* Results.


## **Requirements**

* Jupyter Notebook.
* Pandas.
* NumPy.
* Scikit-learn.
* Matplotlib.

## **Procedure**

These steps are found in the notebook, [customer segmentation.ipynb](https://github.com/MbungaiMichael/Customer-Segmentation/blob/main/customer%20segmentation.ipynb) file with summary explanations.

* Data collection and cleaning.
* Data preprocessing and transformation.
* Data Clustering and analysis.

## **Results**

**Customer behaviour clustering**

| Cluster | Type of Customer | RFM analysis| Suggestions |
|---|---|:---:|---|
| 0 | Steady Customers  |Frequent and high purchase customers | Target customer for recent products |
| 1 | New Customers | new comers with low frequency and purchases| make their purchases and stay at the store comfortable |
| 2 | Marginal Customers |moderate purchases and moderate frequency at the shops | Feedback from these customers can help better quality of service to these group|

**Geographical purchase Clustering**

**Top Purchases By Country**
 
| Country |Purchases| Suggestion|
|---|---|---|
| United Kingdom |close to 362,000  | Increase Products, Target audience| 
| Germany |close to 10,000  |Increase Product delivery| 
| France |close to 9,000  |Increase Product delivery| 
| Eire|close to 8,000  |Increase Product delivery|
| Spain |close to 3,000  |Increase Product delivery|
|Belgium|close to 2,100  |Increase Product delivery|


**Suboptimal Purchases by Country**
| Country |Purchases| Suggestion|
|---|---|---|
| Saudi arabia | 10  | Increase Product awareness through Discounts and public advertisement| 
| Bahrain |17 | Increase Product awareness through Discounts and public advertisement| 
| Czech |30 | Increase Product awareness through Discounts and public advertisement| 
| brazil|32  | Increase Product awareness through Discounts and public advertisement|

