# Introduction

Tensors are higher-order extensions of matrices. In recent work \cite{kilmer2011factorization}, the authors introduced the notion of the t-product, a generalization of matrix multiplication for tensors of order three. The multiplication is based on a convolution-like operation, which 	can be implemented efficiently using the Fast Fourier Transform (FFT). Based on t-product, there has a similar linear algebraic structure of tensors to matrices. For example, there has the tensor SVD (t-SVD) which is computable. By using some properties of FFT, we have a more efficient way for computing t-product and t-SVD in \cite{lu2018tensor}. We develop a Matlab toolbox to implement several basic operations on tensors based on t-product. The toolbox is available at <a href="https://github.com/canyilu/tproduct" >https://github.com/canyilu/tproduct</a>.

Table \ref{tabfuns} gives the list of functions implemented in our toolbox. The detailed definitions of these tensor concepts, operations and tensor factorizations are given at <a href="../tproduct/manual.pdf" class="textlink" target="_blank">https://github.com/canyilu/tproduct/manual.pdf</a>. Note that we only focus on 3 way tensor in this toolbox. We will develop the same functions for p-way tensor in the near future. We will also provide the python verion soon. 

![Alt text](https://github.com/canyilu/tproduct/blob/master/tab_tprod_funlist.JPG)



