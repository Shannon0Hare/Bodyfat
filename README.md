# Bodyfat
Investigating a bodyfat dataset of 88 males.
Overall goal - see what features should be kept in a model.

Data originally published by https://ww2.amstat.org/publications/jse/v4n1/datasets.johnson.html

Principal components analysis
PCA was invented by Karl Pearson in 1901. It is a very widely used statistics learning method.

For data with many variables/dimensions it is difficult to comprehend or visualize the associations between them.

There may be high levels of multicollinearity. Multicollinearity is when features rely/correlate to each other within your model. This can have a great impact on a model leading to over-fitting and not allowing you to trust the statistical values which are calculated from your model such as the p-value.

PCA ‘re-expresses’ the data to account for most of the information in the data through a few linear combinations of the original variables.
Imagine that a data set is made up of three positively correlated variables.
Could one linear combination of the three variables be sufficient to convey most of the information given by the 3 individual variables?

Thus the overall aim in PCA is to describe the variation in a set of correlated variables x1, x2, . . . , xp in terms of a new set of uncorrelated variables y1, y2, . . . , yq (where q << p) where each yj is a linear combination of the x1,x2,...,xp variables.
The new coordinate values that represent the data are known as the principal components (PCs).

Screeplots, also used in this project, helps to calculate the proportion of variance explained by each principal component. I then also used bi-plots to help with the interpretation of the coefficients.
