# Preliminaries

## Supervised learning notation

On supervised learning exists a very standard notation that improves to communicate or think about their concepts.
Because of that, we will define the next concepts 

- **Training set** is the data set we use to train the model.
In supervised (or more specific, in classic supervised models) it frequently has given like a set of tabular data, like spreadsheets.

- **Feature vector or feature input** corresponds to the vector of features that we need to give at the model to produce a label.

- **Label** refers to the feature that we want to predict.

- **Simple training pair** consists of a pair $(\bar{x}, y)$ where $\bar{x}$ is the feature vector of the training example, and the $y$ is their corresponding label.

- Analogously, we can refer to the **$i$-th pair of the training data set** by writing the pair $(\bar{x}^{(i)}, y^{(i)}),$.

- **Learning algorithm** can be thought as a function $\f$ that receives a feature vector as input, and return a $\hat{y}$ as output.
This $\hat{y}=f(x)$ represents the prediction under the model $\f$ for the given input $x$, of the real $y$ label.
Sometimes this model can be indexed to make explicit their train parameters, for example, $f_{w,b}$ refers to a model with parameters $w$ and $b$.

