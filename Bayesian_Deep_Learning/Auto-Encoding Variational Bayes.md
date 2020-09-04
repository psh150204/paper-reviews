# Auto-Encoding Variational Bayes (ICLR 2014)
Sep 4. 2020

## 1. Problems
* How can we perform efficient inference and learning in directed probabilistic models, in the presence of continuous latent variables with intractable posterior distributions, and large datasets?

* continuous latent variable이나 parameter들의 posterior가 intractable한 경우, 기존의 variational Bayes(VB)라는 방법이 있긴 하지만 이는 approximate posterior에 대해서 analytic solution을 필요로 할 뿐더러 이 또한 일반적으로 intratable한 경우가 많다.

* -> 따라서, SGD를 사용할 수 있도록 효과적으로 posterior를 approximate하는 방법을 찾아보겠다.

## 2. Methods




## 3. Contributions
- Show that a reparametrization of the variational lower bound yields a lower bound estimator that can be straightforwardly optimized using standard stochastic gradient methods.
 - Show that for i.i.d. datasets with continuous latent variables per datapoint, posterior inference can be made especially efficient by fitting an approximate inference model to the intractable posterior using the proposed lower bound estimator.
 
## 4. Critique
- Points in favor

- Points in against
