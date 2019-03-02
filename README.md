# DataSci - "Which industry codes experience greatest success in each MD county"

## Abstract
Our project focuses on the application of data science to business regulation and legislation. The most important thing to look at in terms of business performance is how businesses affect a community and how local government can foster economic growth. Using machine learning, we examined business’ community impact with regard to capital investment, jobs created, and revenue increase. We then categorize the businesses’ impact scores based on NAICS industry code to determine which industries have the greatest economic impact on their county’s respective economy/RGDP. County legislators could determine new industry incentivization models from these findings.

The project uses a Jupyter notebook and IPython framework to contain data transformations and modelling. After simple data sanitation (deleting descriptions, etc), the dataset is imported as a Pandas Dataframe. Then, the project uses Pandas to determine the unique counties represented. Scikit-Learn Principal Component Analysis is used to reduce the dimensionality of “impact fields” (defined as capital investment, jobs created, and revenue increase) into an overall business impact score. The model is fitted to the overall dataset, but data is separated out by county and transformed by the PCA model individually. The project sorts mean business impact score by NAICS code for each county separately. For an explanation of how PCA actually reduces dimensionality, see https://www.youtube.com/watch?v=HMOI_lkzW08.

According to our project runs, NAICS Sector Code 53: “Real Estate and Rental and Leasing” scored highest overall (no regard for county), but few individual counties had 53 scoring highest. A plurality of the counties had 42: “Wholesale Trade” scoring highest. NAICS classifies the Wholesale trade sector establishments as “engaged in wholesaling merchandise, generally without transformation, and rendering services incidental to the sale of merchandise.”  Prince Georges County's highest scoring was 48: "Transportation and Warehousing." A legislative body should not only examine the highest scorers, though. The lowest scorers could expose areas in need of incentivization.

