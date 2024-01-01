---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home


---


### Hi! Welcome to my collection of fun visualizations

- An interative version of the PAG 2024 [poster](./poster.pdf) dimensionality reduction results is shown [here](./dimred_highlight.html). Dragging the slider highlights the different populations. Notice how PCA has issues differentiating T1 C-E, and how t-SNE greatly spreads out samples from T2 and T3, issues not found in the deep leanring embeddings. 

- [This](./dog2d.html) shows an embedding on a dog dataset in 2D.



- Given an embedding, we [here](./knn_pheno_pred.html) visualize the decision boundaries for a knn-regression model for phenotype prediction. This give an insight on how using more neighbours smoothes the decision boundary. From the results on the [poster](./poster.pdf) we see that the best prediction score is obtained at k=12, a middle-ground between too much smoothing, and too little (which yields overfitting).



