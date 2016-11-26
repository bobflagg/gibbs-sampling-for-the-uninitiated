# Gibbs Sampling for the Uninitiated (with Python)

The tutorial paper 
[Gibbs Sampling for the Uninitiated](https://www.umiacs.umd.edu/~resnik/pubs/LAMP-TR-153.pdf)
by Resnik and Hardisty is a masterpiece of exposition.  Their main example provides an amazingly 
clear description of how to build a Gibbs sampler for the very simple Naı̈ve Bayes probabilistic model. 
In this repository I implement their Gibbs sampling in Python, build a SPAM detector with the sampler, and illustrate
some techniques for optimizing Python code by increasing the speed of the sampler by a couple of orders of magnitude.
![Graphical Model](https://ai2-s2-public.s3.amazonaws.com/figures/2016-11-01/fc024fbdc59c3b5e708268b29e00cebaf9593875/8-Figure4-1.png)
