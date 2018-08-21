# Chapter 1 On the resolving DCT, DTD and Three Kernels problem

Feng Yin  
Department of Geography, UCL  
ucfafyi@ucl.ac.uk  


<br/>

In this chapter, I am trying to find an analytical way of calculating Observation, prior and spatial or temporal constrains problem in data assimilation system in a matrix form by solving:

\begin{equation*}
\mathbf{A}{\mathbf{x}}=\mathbf{b}
\end{equation*}

![alt text](https://latex.codecogs.com/gif.latex?\mathbf{A}\mathbf{x}&space;=&space;\mathbf{b})

Particularly, with an example of solving the kernel inversion of BRDF from MODIS observations with nearly a years observations.

And adding the temporal and/or sptatial constrain to solve:


\begin{equation*}
\left(\mathbf{A} + \gamma^{2}\mathbf{D}^{\top}\mathbf{D}\right)\mathbf{x} = \mathbf{b}
\end{equation*}

[![Notebook]](./Chapter\ 1\ On\ the\ resolving\ DCT\,\ DTD\ and\ Three\ Kernels\ problem.ipynb)

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MarcYin/DTD-DCT-and-Three-Kernels/master)
