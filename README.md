# Tissue Cancer Detection
This code is a series of commands that can be used to download, clean, and analyze data from the "Breast Cancer Wisconsin (Diagnostic)" dataset from the UCI Machine Learning Repository.

The first block installs some necessary dependencies, such as mupy, pandas, matplotlib, seaborn, and lazypredict. The second block imports these dependencies, and the third block installs the kaggle library and downloads the dataset. The fourth block unzips the downloaded file, and the fifth block reads the data into a pandas dataframe.

The following blocks explore and clean the data. They check for missing values and remove any columns with all missing values. They also examine the data types of the columns and the frequency of the diagnosis variable. Finally, the last block creates a box plot of the diagnosis cases. Then it evaluates different models through the LazyPredict Library and trains the best one using sklearn ML library and test it. 
