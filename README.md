# Surrogate Modelling
A collection of resources associated with discussions had by members of the Surrogate Modelling Working Group of the INI UQ Programme Jan-June 2018. For further info - contact Catherine Powell. 


Suggested Reading List. The links below are to webpages where papers can be downloaded (if you have the appropriate permissions/subscription rights through your institution). Note - this page is a work in progress ....


## Comparison Papers 

- [Comparison of Surrogate-Based Uncertainty Quantification Methods for Computationally Expensive Simulators](http://epubs.siam.org/doi/abs/10.1137/15M1046812), N. E. Owen, P. Challenor, P. P. Menon, and S. Bennani


##  Background on sparse grids (for interpolation/quadrature) 

- [A low level introduction to Sparse Grids](http://people.sc.fsu.edu/~jburkardt/presentations/sandia_2007.pdf)
- [Numerical Integration Using Sparse Grids](https://link.springer.com/article/10.1023/A:1019129717644), Thomas Gerstner, Michael Griebel (1998). 
- [High Dimensional Polynomial Interpolation on Sparse Grids](https://link.springer.com/article/10.1023/A:1018977404843), Volker Barthelmann, Erich Novak, Klaus Ritter (2000).
- Quadrature and Interpolation Formulas for Tensor Products of Certain Classes of Functions, Doklady Akademii Nauk SSSR, Volume 4, pages 240-243, Sergey Smolyak, (1963)
- [SPINTERP: MATLAB code](http://people.sc.fsu.edu/%7Ejburkardt/m_src/spinterp/spinterp.html)


## Polynomial Approximation based on point evaluations

... also known as stochastic collocation (although that term is often used to mean interpolation exclusively). There are a wide range of polynomial-based approximation techniques that are constructed from point evaluations (computer model runs at particular choices of the input parameters), including interpolation, regression and non-intrusive forms of polynomial chaos approximation based on quadrature.


### Interpolation

- [A Stochastic Collocation Method for Elliptic Partial Differential Equations with Random Input Data](http://epubs.siam.org/doi/abs/10.1137/050645142), Ivo Babuška, Fabio Nobile, and Raúl Tempone.

- [High-Order Collocation Methods for Differential Equations with Random Inputs](http://epubs.siam.org/doi/abs/10.1137/040615201), Dongbin Xiu and Jan S. Hesthaven.

- [A Sparse Grid Stochastic Collocation Method for Partial Differential Equations with Random Input Data](
http://epubs.siam.org/doi/abs/10.1137/060663660), F. Nobile, R. Tempone, and C. G. Webster.

- [An Anisotropic Sparse Grid Stochastic Collocation Method for Partial Differential Equations with Random Input Data](
http://epubs.siam.org/doi/abs/10.1137/070680540), F. Nobile, R. Tempone, and C. G. Webster.


### Regression

Suggestions for papers ..... ? 

### Quadrature

Suggestions for papers .... ? 


## Polynomial Approximation not based on point evaluations

Stochastic Galerkin approximation is perhaps an outlier in polynomial approximation, in that it does not use point evaluations. It imposes a Galerkin condition, and in some sense is 'structure preserving'. Also known as intrusive polynomial chaos (if the polynomials chosen for the parameteric/random part are orthogonal).

### Stochastic Galerkin Approximation 

- [Galerkin Finite Element Approximations of Stochastic Elliptic Partial Differential Equations](http://epubs.siam.org/doi/abs/10.1137/S0036142902418680), Ivo Babuska, Raúl Tempone, and Georgios E. Zouraris.

More soon .... 

## Gaussian Process Emulation

## Reproducing Kernel Hilbert Spaces

 RKHS ideas have been used recently in several works. For example, 

- [Reproducing Kernel Hilbert Spaces for Parametric Partial Differential Equations](http://epubs.siam.org/doi/10.1137/15M1026870), Michael Griebel & Christian Rieger

- [Convergence Types and Rates in Generic Karhunen-Loeve Expansions with Applications to Sample Path Properties](https://arxiv.org/pdf/1403.1040.pdf), Ingo Steinwart


