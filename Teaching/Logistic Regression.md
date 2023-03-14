# Basic Idea
Logistic regression was originally designed to solve binary classification problems.  For example
- Will this customer leave our business?  (leave or stay)  
- Is this patient sick?  (healthy or sick)  
- Should I approve this loan application?  (approve or reject)  
- etc.  

The model predicts the probability of outcome $(y)$ from a given sample represented as a feature vector $(\mathbf{x})$.  The notations used in this tutorial are the following.  Let $\mathcal{D} = \left \langle \mathbf{X}, \mathbf{y} \right \rangle$ be a dataset.  $\mathbf{X} = \left \langle \mathbf{x}_1, \mathbf{x}_2, ... , \mathbf{x}_m \right \rangle$ be $n$ feature vectors with dimension of $n \times m$.  $\mathbf{x}_i$ be the $i^{\mathrm{th}}$ feature vector with dimension of $1 \times m$.  $\mathbf{y}$ be a target classes with dimension of $n \times 1$  
