## Turing Reaction-Diffusion Model  

_Please install [MathJax Plugin for Github](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima/related) or [Math Anywhere](https://chrome.google.com/webstore/detail/math-anywhere/gebhifiddmaaeecbaiemfpejghjdjmhc) Chrome plug-ins to view equations_  

The Turing reaction-diffusion model is a mean field description in the form of balance equations. On the left hand size of the equation, we have to find the partial derivative of macrostates over time. The first part of the right-hand side of the equation shows the effect of a chemical reaction. The second part shows transport variables such as heat diffusivity ($D$) and macroscopic variables ($x_1, x_2,....x_i$) as they operate along a gradient ($\nabla$). 

$${\frac{\partial{x_i}}{\partial_t}} = V_i({x_j}, \lambda) + D_i \nabla^2 {x_i}\tag{1}$$

<p align="center">
  <img width="617" height="172" src="https://user-images.githubusercontent.com/19001437/53520874-552f8e80-3a9c-11e9-91c1-2ae61fc9fac8.jpg"><BR>
  
  __Figure 1.__ Example of patterns that result from Equation 1. Taken from [1].
</p>

Equation 2 characterizes the changes in $I$ per unit time (see Figure 1). $G(A, I)$ represents the reaction component, while $D_I$ represents the diffusion component.

$${\frac{\partial{I}}{\partial{t}}} = G(A, I) + D_I {\frac{\partial^2{I}}{\partial{x^2}}}\tag{2}$$

Equation 2 characterizes the changes in $A$ per unit time (see Figure 1). $F(A, I)$ represents the reaction component, while $D_A$ represents the diffusion component.

$${\frac{\partial{A}}{\partial{t}}} = F(A, I) + D_A {\frac{\partial^2{A}}{\partial{x^2}}}\tag{3}$$

<p align="center">
  <img width="521" height="225" src="https://user-images.githubusercontent.com/19001437/53523296-13a1e200-3aa2-11e9-991b-88ccea1dc72f.png"><BR>
  Example of pattern formation in fish skin. Taken from [2].
</p>


__NOTES:__    
[1] Kondo S, and Miura T (2010). [Reaction-diffusion model as a framework for understanding biological pattern formation](https://www.ncbi.nlm.nih.gov/pubmed/20929839). _Science_, 329, 1616-1620.  

[2] Torii, K.U. (2012). [Two-dimensional spatial patterning in developmental systems](https://www.ncbi.nlm.nih.gov/pubmed/22789547). _Trends in Cell Biology_, 22(8), 438-446.
