# Linear Regression Project


Books are open doors to the unimagined worlds which is unique to every person. It is more than just a hobby for many. Many among us prefer to spend more time with books than anything else.

Here I explore a big database of books. Books of different categories, from thousands of authors. In this project, I choose  to use this dataset which I got from a previous pipeline project to build a Machine Learning model to predict the price of books based on a given set of features below:

**FEATURES**:

**pages**: How many pages do this book have

**weight_gram**: How heavy this book 

**media_reviews**: Does this book have a media review or not

**num_reviews**: The number of customer reviews about the book

**num_stars**: The customer ratings of the book

**categories**: The department the book is usually available at.

**Price**: The price of the book (Target variable)

### Data preprocessing

- Deal with null values, convert data types, drop the duplicates, work with outliers
- Choose target and features
- EDA: use **Matplotlib** to plot to scatter, show the relations within target and features, this step helps with features selection
- Encoding categorical variables
- Train/test split

### Modeling

 - Data normalization
 - Fit the model
 - Make a prediction

### Measuring model performance

- The loss function : ** Mean Squared error**
- plot the residuals for **y_test** and **y_pred**
