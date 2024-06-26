One of my first DS/ML-Projects. I was playing around with Fourier, trying to figure out if it can be useful when trying to find patterns in outlier-data.

### Robust pattern detection in multivariate outliers: 

While there already exist some suitable (software) solutions to robustly detect
outliers in multivariate datasets, for example, algorithms based on a robust version of the
Mahalanobis distance published by  [Leys et.al. (2018)](https://www.sciencedirect.com/science/article/abs/pii/S0022103117302123), the amount and quality of
information that can be algorithmically obtained about the origins and mechanisms behind
such outliers are still limited. Therefore this project tries to create an algorithm that can reliably
discover such hidden mechanisms with the help of modern pattern detection algorithms, to thereby help researchers and scientists to gain deeper insights into the origins and mechanisms behind the occurrences of outliers in their data sets. 

### Project Description
The main idea of this project was to use Fourier Analysis/Fourier Clustering + k-Means Clustering to identify patterns in multivariate outliers in data from empirical psychology. In case of higher dimensional data/outliers, two popular dimension reduction technologies (namely PCA and t-SNE) have been applied beforehand. 

<div style="text-align:center;">
    <img src="documentation/structural_overview.png?raw=true" alt="Alt text" title="Title" width="50%">
</div>

### How to use
Just take a look at the `app.py`. You only need to specify the input data (the determined outliers) and by running the `app.py`, you will automatically receive a html report in the /results directory. 


### Further
If you have any questions or want to learn more, feel free to reach out to me: info@dominik-pichler.com
