# DataSci - "Which industry codes experience greatest success in each MD county"


Our project focuses on the application of data science to business regulation and legislation. The most important thing to look at in terms of business performance is how businesses affect a community and how local government can foster economic growth. Using machine learning, we examined business’ community impact with regard to capital investment, jobs created, and revenue increase. We then categorize the businesses’ impact scores based on NAICS industry code to determine which industries have the greatest economic impact on their county’s respective economy/RGDP. County legislators could determine new industry incentivization models from these findings.

We use a Jupyter notebook and IPython to accomplish our project objectives. After simple data sanitation (deleting descriptions, etc), the dataset is imported as a Pandas Dataframe. Then, we use Pandas to determine the unique counties represented in the dataset. We use ScikitLearn Principal Component Analysis to reduce the dimensionality of “impact fields” (defined as capital investment, jobs created, and revenue increase) into an overall business impact score. We fit the model on the overall dataset, but then separated the data out by county and applied the PCA model individually. We sort mean business impact score by NAICS code for each county separately. 

According to our data, NAICS Sector Code 53: “Real Estate and Rental and Leasing” scored highest overall (no regard for county), but few individual counties had 53 scoring highest. A plurality of the counties had 42: “Wholesale Trade” scoring highest. NAICS classifies the Wholesale trade sector establishments as “engaged in wholesaling merchandise, generally without transformation, and rendering services incidental to the sale of merchandise.”  Prince Georges County has 48: Transportation and Warehousing as the highest scoring sector. A legislative body should not only examine the highest scorers, though. Examining the lowest scorers could show what areas need improvement and thus which industries to promote.

