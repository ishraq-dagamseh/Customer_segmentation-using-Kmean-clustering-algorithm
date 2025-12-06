# Customer_segmentation-using-Kmean-clustering-algorithm

![download](https://github.com/user-attachments/assets/26d1c4a2-26d5-4a64-aae7-1dae420cbc1b)

In this project we applied one of the clustering algorithms, that called k-mean. to grouping customers based on two features: 'Quantity'and 'UnitPrice' features.
we used dataset from kaggle: (online Retail from Kaggle: https://www.kaggle.com/datasets/yasserh/customer-segmentation-dataset?resource=download)

After dropping null raws, we made reading for  data, then we made some exploring on the features, like:( relationship between Invoice year and the quantity) as we see in the next image:
<img width="632" height="436" alt="image" src="https://github.com/user-attachments/assets/42f56117-0696-4b62-8575-a641da4205b5" />
We noted that the largest quantity was in 2011
In United Kingdom
<img width="588" height="533" alt="image" src="https://github.com/user-attachments/assets/28223547-f2df-4cb4-9a78-1de27d9bd063" />

to apply kmean, we decided 'Quantity','UnitPrice','Country_encoded' features and after scaling it, we made a small search about the best number of k or groups to this problem and from the graph, we noticed that the optimal number of groups is 4, beacouse thier are a small amount of updating in WCSS(Within-Cluster Sum of Squares)
<img width="597" height="451" alt="image" src="https://github.com/user-attachments/assets/72c512c8-fe4b-4376-892a-bc0971044f5e" />

The final distribution of data as we see in the next graph:
<img width="597" height="440" alt="image" src="https://github.com/user-attachments/assets/c957d9e7-7cef-4e27-800c-af11aa1c03a7" />







