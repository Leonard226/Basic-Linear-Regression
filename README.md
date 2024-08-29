# Basic-Linear-Regression
Please refer to `main.ipynb` for mathematical derivations, more details, and specific implementations; everything is documented there. 
<br>
<br>
Short description: <br>
Given a labeled data set $D_{train}=\{(x_i, y_i)\}_{i=1}^n$, where $x_i \in \mathbb R^d$, $y_i \in \mathbb R$, and $n \gg d$. For a given $x_i$, we make the prediction $y_i = w^Tx_i$, where we have to "learn" the optimal $w$ via linear regression. We use simple gradient descent algorithm with momentum to minimize the loss function. 
