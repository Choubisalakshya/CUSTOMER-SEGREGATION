# CUSTOMER-SEGREGATION
# TASK - Given a dataset of customers that include the customer ID, the products they buy, price of each product ,time,date etc . My task is to classify the data into the possible types of customers which the retailer can encounter.
# Steps followed by me :
Load the data set.
Preprocessing and visualization of data.
Making a new dataframe that will contain all information about a customer.
Cluster the customers based on type of products they buy (like related to food, electronics etc.)
Cluster the customers based on all information collected in the new data frame except the type of product a customer buy (ie in this case, clustering will be independent of description column (product type))
Cluster the customer based on their financial behavior and the type of products they buy. (in this case we will take into account the description column and use text clustering and general clustering concept together to segment customers)
Cluster the customers solely based on their financial habits (in this case I will not take into account what type of product a customer buy, country, time, how many time he/she goes shopping, etc).
