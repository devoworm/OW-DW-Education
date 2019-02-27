Please install [MathJax Plugin for Github](https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima/related) or [Math Anywhere](https://chrome.google.com/webstore/detail/math-anywhere/gebhifiddmaaeecbaiemfpejghjdjmhc) Chrome plug-ins to view equations

The Turing reaction-diffusion model is a mean field description in the form of balance equations. On the left hand size of the equation, we have to find the partial derivative of macrostates over time. The first part of the right-hand side of the equation shows the effect of a chemical reaction. The second part shows transport variables such as heat diffusivity ($D$) and macroscopic variables ($x_1, x_2,....x_i$) as they operate along a gradient ($\nabla$). 

$${\frac{\partial{x_i}}{\partial_t}} = V_i({x_j}, \lambda) + D_i \nabla^2 {x_i}\tag{1}$$

<p align="center">
  <img width="617" height="172" src="https://user-images.githubusercontent.com/19001437/53520874-552f8e80-3a9c-11e9-91c1-2ae61fc9fac8.jpg">
  Example of patterns that result from Equation 1. Taken from [1].
</p>


NOTES:
[1] Kondo S, and Miura T (2010). [Reaction-diffusion model as a framework for understanding biological pattern formation](https://www.ncbi.nlm.nih.gov/pubmed/20929839). _Science_, 329, 1616-1620.
