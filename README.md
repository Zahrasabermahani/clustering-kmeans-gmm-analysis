# clustering-kmeans-gmm-analysis
Clustering individuals using salary, height, weight, and housework time with K-Means and Gaussian Mixture Models (GMM). Gender labels are excluded during training for unbiased grouping.



##  Clustering Analysis with K-Means & GMM

In this project, I tried to group people based on their **salary, height, weight, and time spent on housework** — without using their gender as input.

I used two unsupervised learning methods:
- **K-Means**
- **Gaussian Mixture Model (GMM)**

The idea was simple: can the algorithm figure out natural groupings in the data on its own?

After scaling the data and reducing dimensions with **PCA**, I visualized the clusters. Then I compared them with the actual gender labels (M/F) — just to see how close the model got without knowing it.

Turns out, even without the gender feature, the clusters made a lot of sense. Some clear patterns emerged, especially with GMM.

This was a great hands-on way to explore how unsupervised learning works on real-world-style data.

## What I learned

Even though gender was not used in the clustering process, the models , especially GMM , were able to group individuals in a way that closely reflected actual gender differences. This shows how powerful unsupervised learning can be when the data has a strong internal structure. K-Means gave reasonable results too, but GMM captured the data's natural variation better.


