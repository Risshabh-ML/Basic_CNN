# Basic_CNN
Single &amp; Multiple CNN Layer , LeNet

The 2D convolution operation
What about 2D inputs? What are the neighbors that we consider?
1. In a nutshell, the convolution operation boils down to taking a given input and re-estimating it as
a weighted average of all the inputs around it.
2. The above definition is easy to visualise in 1D, but what about 2D?
3. In 2D, we would consider neighbors along the rows and columns, using the following formula
4. sij = (I * K)ij = Σm−1_a=0 Σ_n−1 b=0 Ii+a, j+b * Ka,b
5. 
