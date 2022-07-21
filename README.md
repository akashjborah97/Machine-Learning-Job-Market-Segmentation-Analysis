# Machine Learning Job-Market Segmentation Analysis
Target: To analyze the ML joB market in India using Segmentation analysis for finding companies probable of hiring an ML Engineer/Data Analyst in respect to his/her skillset.


Techniques and Algorithms used: Machine learning using python with libraries(numpy, pandas, scikit-learn, matplotlib) , elbow method, stability based structure analysis, k means clustering, Agglomerative clustering.

In this project, we took a dataset form the website naukri.com analysed the skills and companies and using clustering algorithm we performed segmentation. k-means fails to find hidden pattern thus we implemented agglomerative hierarchical clustering wherein the population  is divided into several clusters such that data points in the same cluster are more similar and data points in different clusters are dissimilar.

Results : As Segmentation analysis is an important step before we embark on any plan. Hence it is important to learn how to analyze the job market and the demanded skills by the company. By analyzing the trend in k-means clustering, we have observed cluster 0 contains companies which are inclined towards hiring people with Python skills on Data Science and Machine Learning. Cluster 1 contains companies which are likely to hire people with skills are not oriented towards Data Analysis. Cluster 2 contains companies which are inclined towards hiring people with Python and R skills on Data Science. Cluster 3 contains companies which are inclined towards hiring people with Python skills on Machine Learning. Cluster 4 contains companies which are likely to hire people with skills are not oriented towards Data Analysis. Cluster 5 contains companies which are likely to hire people with skills of Python, Machine Learning and minimal Data Science. The most demanded skills for the recruiters are Python, Data Science, Machine Learning and other IT skills.
For the company’s analysis based on experience demanded, it was observed that Wipro, HiringSign, Global Logic and Gojek etc. didn’t appear in top numbers before the segmentation and appeared after the segmentation was carried out for the minimum, average and maximum experience level.


Agglomerative clusters were able to generate better results. Agglomerative clustering helped us to generate more stable clusters,where the skills were distributed in a more evenly manner. The results were more accurate in relevant skill distribution profiling, finding probable companies hiring in each cluster. Based on experience level, new companies appeared hiring with minimum experience level.


