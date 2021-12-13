# Kitchen Appliance Selection - Stove and Chimney
Finding the best stove and chimney for the kitchen post-renovation.

### Problem Statement:
- After a recent renovation of the kitchen, there came a problem of installing a new stove and chimney. Each store were selling products from the companies which sponsored them and the recommendations were highly subjective. So choosing the right product for the kitchen seemed difficult.

### Solution:
- To get an objective opinion of the products, all stoves and chimneys data was scraped from Amazon for each of the three brands and compared against each other.

### Tools Used:
- BeautifulSoup, Pandas, Numpy, Seaborn, Matplotlib

### Findings:
- The Three companies used for comparison are Faber, Elica and Glen.

#### The Count of all the products are measured and the following plot has been generated:
![Count of Products](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Count%20of%20Products.png)

#### Insight:
   - Glen has the highest number of products in the dataset and the lowest is of Elica. The number of products from Faber is almost the same as Glen.
   - This would mean that using an average value for the comparisons would not be reliable and therefore median can be used.

#### The Prices of the three companies are compared as follows:
![Average Product Price Comparison](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Average%20Product%20Price%20Comparison.png)
#### Insight:
  - (Note: Both Stoves and Chimney records are used for the following comparison).
  - Faber is the most expensive among the three companies on an average and Glen is the least expensive.

- To Further understand the data the following Kernel Density Estimate Plots have been plot:

#### KDE plots for Stoves

![KDE Plots Stove](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Stove_Price_Rating.png)

#### KDE plots for Chimneys

![KDE Plots Chimney](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Chimney_Price_Ratings.png)

#### Insight:
- For Stoves:
  - Glen has a high number for stoves which are priced between 1000 and 11000 and not one product more expensive than that and has a relatively better rating than the other two companies.
  - But, it cannot be detemined that Glen would be the best company overall since the other two companies also have a rating similar to Glen. The only distinct feature is price which can be noted. However, there are several products from Faber and Elica which can be purchased for the same price as the range that Glen prices their products.

- For Chimney:
  - As seen from the Countplot, Glen has a higher number of products and are less expensive than the other two. However, it can also be seen that Glen has products which are having lower rating and higher rating peaking towards 4.
  - When the other two companes are noted, Faber does not have any product rated less than 4.0, maximum being 4.5. Suggesting that Faber has the best chimney's among the three.

#### Aggregate Tables:
- For Stoves

![Stoves](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Stove_Cluster_Table.JPG)

- For Chimneys:

![Chimney](https://github.com/the19thpirate/Kitchen-Appliances/blob/main/Stove_Cluster_Table.JPG)

#### Insight:
  - Since looking at the data for Stoves didn't provide the distinction that was required for making a decision but the data for chimney's do. Looking at these tables it can be determined that Faber Chimneys are the most expensive among the three companies but are most highly rated.


### Conclusion

- Few other logical reasons come into the analysis which helps determining the appliance. Namely:
  - The Vendor,
  - The After Sale Service,
  - History of the company
  - etc.

- When the after sale services of the companies were considered, in my area of residence, Glen and Elica do not have a good after sale service. (Basic Google search)
- Faber has almost three service centers around my area and is reliable and has their dedicated service team which the other two companies do not have.
- Also, going for the same brand of stove and chimney would be better since both compliment each other in usage and the worry of cluttering the services can be avoided.
- 
### Verdict:
- From the Analysis the best product in each category is Faber for chimney and Glen for Stove. Going by the previous statement, choosing the same company would be reliable. Therefore the company which I eventually purchased for the house is **Faber** ( Both Chimney and Stove ).
