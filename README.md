# Fitting playground

Born during the Hack Day at PyAstro 2019, this repo contains tutorials and showcases 
on using popular minimizers and samplers, their performance in minimizing and sampling multimodal distributions, 
as well as fitting data.

### A taste of what you can find here

[Minimizers Playground](https://nbviewer.jupyter.org/github/gecheline/fitting_playground/blob/master/minimizers.ipynb) 
- several minimizing algorithms using [scipy.optimize](https://docs.scipy.org/doc/scipy/reference/optimize.html)
(Nelder-Mead, CG, differential evolution) and [PySwarms](https://pyswarms.readthedocs.io/en/latest/)
(particle swarm optimization) on a 2D multimodal function with two global and many local minima.

[Samplers Playground](https://nbviewer.jupyter.org/github/gecheline/fitting_playground/blob/master/samplers_eggbox.ipynb)
- nested sampling with [dynesty] and [nestle] and MCMC sampling with [emcee] on the eggbox distribution.

[Fitting Playground](https://nbviewer.jupyter.org/github/gecheline/fitting_playground/blob/master/sinegaussian_playground.ipynb) 
- an overview of the performance of both minimizers and samplers when fitting the parameters of 
a sine + Gaussian function.

[Two step sampling: PRISM to emcee](https://nbviewer.jupyter.org/github/gecheline/fitting_playground/blob/master/quadratic_npdists_prism_emcee.ipynb)
