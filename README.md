# Introduction to Bayesian inference of phylogenies using molecular and fossil data in RevBayes

## Upcoming Worshops

* **August 14-15, 2017** -- *Iowa State University*, Ames, Iowa
* **September 25-26, 2017** -- *International Biogeography Society*, Bengaluru, India


## Instructors

* Dr. Tracy A. Heath, Iowa State University ([http://phyloworks.org](http://phyloworks.org)) 
* Dr. Walker Pett, Iowa State University ([http://willpett.github.io](http://willpett.github.io)) 

## Workshop Description

Bayesian statistical methods enable analysis of macroevolutionary processes under complex phylogenetic models. 
This workshop will focus on the theory and practice of estimating time-calibrated phylogenies from neontological and paleontological data.
We will teach these concepts by integrating theory-based lectures with hands-on practicals in the program RevBayes.
[RevBayes](http://revbayes.github.io/) is a program that provides a flexible framework for Bayesian phylogenetic inference. 

### Topics

* Introduction to Bayesian inference and MCMC
* Probabilistic graphical models
* The Rev language 
* Inferring phylogenies in RevBayes
* Model selection using Bayes factors
* Estimating species divergence times
    * Stochastic branching processes as tree priors, with particular emphasis on the fossilized birth-death model (FBD)
    * Models of lineage-specific substitution rates (or rates of morphological change)
    * Models of discrete morphological character change and accounting for acquisition biases


## Install RevBayes & Accessory Programs

This workshop will use the most recent version of RevBayes. It can be downloaded for Windows 7 or higher or for Mac OSX 10.6 or higher from [https://github.com/revbayes/revbayes/releases](https://github.com/revbayes/revbayes/releases). For Unix systems, you can clone the source code from [https://github.com/revbayes/revbayes](https://github.com/revbayes/revbayes).

The RevBayes workshops will also use additional for analysis of output and summarization of the MCMC. Please download and install the following:

* Tracer ([http://tree.bio.ed.ac.uk/software/tracer/](http://tree.bio.ed.ac.uk/software/tracer/))
* FigTree ([http://tree.bio.ed.ac.uk/software/figtree/](http://tree.bio.ed.ac.uk/software/figtree/))
* IcyTree (a web-based tree viewer; [http://tgvaughan.github.io/icytree/](http://tgvaughan.github.io/icytree))
* Text editors: [Sublime Text](https://www.sublimetext.com/) or [Atom](https://atom.io)

## Recommended Background Material

### Tutorials

This workshop covers phylogenetic analysis under complex statistical models. Because of the challenging material, workshop participants will benefit from working through introductory material before taking the course. This is particularly true for anyone without a previous introduction to Bayesian phylogenetics. 

* Basic Introduction to Rev and MCMC ([tutorial PDF](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_Basics_Tutorial.pdf))
* Introduction to MCMC Simulation ([tutorial PDF](https://github.com/revbayes/revbayes_tutorial/blob/master/tutorial_TeX/RB_MCMC_Intro_Tutorial/RB_MCMC_Intro_Tutorial.pdf))
* Substitution Models for Time-Constrained Trees ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_CTMC_Tutorial.pdf))
* Partitioned Data Analysis ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_Partition_Tutorial.pdf))
* Model Selection using Bayes Factors ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_BayesFactor_Tutorial.pdf))

### Reading

Höhna, Landis, Heath, Boussau, Lartillot, Moore, Huelsenbeck, Ronquist. 2016. RevBayes: Bayesian phylogenetic inference using graphical models and an interactive model-specification language. Systematic Biology, 65:726-736.

Heath, Huelsenbeck, Stadler. 2014. The fossilized birth-death process for coherent calibration of divergence-time estimates. Proceedings of the National Academy of Sciences 111(29):E2957–E2966. 

Höhna, Heath, Boussau, Landis, Ronquist, Huelsenbeck. 2014. Probabilistic graphical model representation in phylogenetics. Systematic Biology 63:753–771.