# Sampling from an SVM
Have you ever wondered what a Support Vector Machine thinks the world looks like? Usually, one does not think of the SVM as generative model, but if we did, here would be a few samples:

![An example of what an SVM thinks data looks like](svm.png)
![An example of what an SVM thinks data looks like](svm2.png)
![An example of what an SVM thinks data looks like](svm3.png)

 There's a bayesian interpretation of SVMs (due to Peter Sollich http://web.cs.iastate.edu/~honavar/bayes-svm.pdf), as MAP solutions to inference problems with priors determined by a choice of gaussian process. In the [accompanying notebook](Support_Vector_Machine_Samples.ipynb) we sample from this prior. The above samples were generated from a squared exponential gaussian process. 