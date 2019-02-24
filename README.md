# DataSci

Here is the email from our mentor:

'
1. How do we define business success and what amount of investment means a great amount? After setting out the threshold and dividing your examples into different categories(e.g. success/not success), it's good to perform a summary statistical analysis of the features for each of those different categories, and also attach some visualizations with your analysis. 

 

2. The next step will be trying out some different models on your data. 

The general form of a supervised learning question is:

y = f(x), where y is the target variable (the variable you want to predict, i.e. total revenue, success or not...), x is the set of predictive variables (the variables you use to predict y, i.e. location, GDP of the county, industry of the business...)

If the target variable (the variable you want to predict) is quantitative, you can use regression models. If the target variable is binary or categorical, you can use logistic regression or random forest. And I will focus on what are the variable importance and regression coefficients for each of the predictive variable and how to interpret them. Let's say if y is total revenue, and x is GDP of the county, then positive coefficient for x means the wealthier the location of the company, the higher the revenue they will generate.

 

3. Deal with categorical features. The predictive variables can include a lot of categorical ones, like industry, county, etc. The common way to deal with them is to do one-hot-encoding or frequency encoding. In that way, you can turn your categorical variables into numerical ones and fit a model on them. Also a lot of packages like sklearn are well implemented, so when you assign the input variable, you just need to point out which features are categorical and the package will take care of it for you.

 

4. For the tools you can use, Python has a lot of great packages. E.g., numpy is a package for importing, cleaning, combining and doing basic summary analysis on datasets. sklearn is the package for implementing machine learning models. matplotlib, seaborn, plotly are some nice visualizations tools.

I also highly recommend R for doing regression and random forest. R provides a whole bunch of detailed statistical analysis and fancy visualizations (ggplot package), and is kind of intuitive if you are familiar with Python.



5. How judges will review the project: Technical tools you used is only one side of the picture, how you organize your material and present them out to be insightful and attractive is often more critical factor when readers review your project. I believe you guys will have some very interesting insights when you brings in your domain knowledge, and some cool visualizations will definitely attract people's eyes.

 

For some of the tutorials, you can check out Andrew NG's lecture on machine learning to get familiar with some of the concepts. There are also a lot of Kaggle kernels, tech blogs and code tutorials about data analysis and implementing these algorithms.
'
