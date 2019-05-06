## Turing Reaction-Diffusion Model  

_Please install [MathJax Plugin for Github](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima/related) or [Math Anywhere](https://chrome.google.com/webstore/detail/math-anywhere/gebhifiddmaaeecbaiemfpejghjdjmhc) Chrome plug-ins to view equations_  

The Turing reaction-diffusion model [1], sometimes called _chemical morphogenesis_, is a mean field description in the form of balance equations. On the left hand size of the equation, we have to find the partial derivative of macrostates over time. The first part of the right-hand side of the equation shows the effect of a chemical reaction. The second part shows transport variables such as heat diffusivity ($D$) and macroscopic variables ($x_1, x_2,....x_i$) as they operate along a gradient ($\nabla$). 

$${\frac{\partial{x_i}}{\partial_t}} = V_i({x_j}, \lambda) + D_i \nabla^2 {x_i}\tag{1}$$

<p align="center">
  <img width="617" height="172" src="https://user-images.githubusercontent.com/19001437/53520874-552f8e80-3a9c-11e9-91c1-2ae61fc9fac8.jpg"><BR>
  Figure 1. Example of patterns that result from Equation 1. Taken from [2].
</p>

The coupled feedback system described in equations 2 and 3 are a restatement of the dynamics described in equation 1. Equation 2 characterizes the changes in $I$ per unit time (see Figure 1). $G(A, I)$ represents the reaction component, while $D_I$ represents the diffusion component. 

$${\frac{\partial{I}}{\partial{t}}} = G(A, I) + D_I {\frac{\partial^2{I}}{\partial{x^2}}}\tag{2}$$

Equation 3 characterizes the changes in $A$ per unit time (see Figure 1). $F(A, I)$ represents the reaction component, while $D_A$ represents the diffusion component.

$${\frac{\partial{A}}{\partial{t}}} = F(A, I) + D_A {\frac{\partial^2{A}}{\partial{x^2}}}\tag{3}$$

<p align="center">
  <img width="521" height="225" src="https://user-images.githubusercontent.com/19001437/53523296-13a1e200-3aa2-11e9-991b-88ccea1dc72f.png"><BR>
  Figure 2. Example of pattern formation in fish skin. The activity of the black hexagons (striped pattern) is characterized in Equation 2, and is representative of faster diffusion, while the activity of yellow hexagons is characterized in Equation 3, and is representative of slower diffusion. Taken from [3].
</p>
  
This simple form of [bistability](https://en.wikipedia.org/wiki/Bistability) provides a mechanism for striping and spotting in an organism's phenotype.  


Is the Turing mechanism enough to produce a patterned phenotype? Are there other mechanisms related to cell movements [4, 5] or interactions between genotype and phenotype [6] that provide a similar or augmentative mechanism?

__NOTES:__   
[1]  Turing, A. M. (1952). [The Chemical Basis of Morphogenesis](https://royalsocietypublishing.org/doi/10.1098/rstb.1952.0012). _Philosophical Transactions of the Royal Society of London B_, 237 (641), 37–72.

[2] Kondo S, and Miura T (2010). [Reaction-diffusion model as a framework for understanding biological pattern formation](https://www.ncbi.nlm.nih.gov/pubmed/20929839). _Science_, 329, 1616-1620.  

[3] Torii, K.U. (2012). [Two-dimensional spatial patterning in developmental systems](https://www.ncbi.nlm.nih.gov/pubmed/22789547). _Trends in Cell Biology_, 22(8), 438-446.

[4] Painter, K.J., Maini, P.K., and Othmer, H.G. (1999). [Stripe formation in juvenile Pomacanthus explained by a generalized Turing mechanism with chemotaxis](https://www.pnas.org/content/96/10/5549). PNAS, (10), 5549-5554.

[5] 

[6] Kiskowski, M., Glimm, T., Moreno, N., Gamble, T., and Chiari, Y. (2019). [Isolating and quantifying the role of developmental noise in generating phenotypic variation](https://doi.org/10.1371/journal.pcbi.1006943). PLoS Computational Biology, 15(4), e1006943.
