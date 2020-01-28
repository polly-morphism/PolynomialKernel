The Kernel trick.

The Kernel trick. provides a bridge from linearity to non-linearity to any algorithm that can expressed solely on terms of dot products between two vectors. With this method we first map our input data into a higher-dimensional space, a linear algorithm operating in this space will behave non-linearly in the original input space.

Kernel functions must be continuous, symmetric, and most preferably should have a positive (semi-) definite Gram matrix. Kernels which are said to satisfy the Mercer’s theorem (which polynomial and linear kerles do) are positive semi-definite, meaning their kernel matrices have only non-negative Eigen values. The use of a positive definite kernel means that the optimization problem will be convex and solution will be unique.

Polynomial Kernel.

The Polynomial kernel is a non-stationary kernel. Polynomial kernels are well suited for problems where all the training data is normalized.

𝑘(𝑥,𝑦)=(𝛼𝑥𝑇𝑦+𝑐)𝑑

Adjustable parameters are the slope 𝛼, the constant term c and the polynomial degree d. In this case I use 3 degree polynomial.

