# Introduction to Bayesian inference of phylogenies using molecular and fossil data in RevBayes

## Upcoming Workshop

* **September 25-26, 2017** -- [*International Biogeography Society - India Meeting*](https://www.biogeography.in/), Bengaluru, India


## Instructors

* Dr. Tracy A. Heath, Iowa State University ([http://phyloworks.org](http://phyloworks.org)) 
* Dr. Walker Pett, Iowa State University ([http://willpett.github.io](http://willpett.github.io)) 


## Funding

This workshop is supported by funds form the Simons Center for the Study of Living Machines at the National Centre for Biological Sciences (India) and by National Science Foundation (USA) grants [DEB-1556615](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1556615&HistoricalAwards=false) and [DEB-1556701](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1556701&HistoricalAwards=false).

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

This workshop will use a new version RevBayes that has not been posted online yet. It should be available by 23 September for Mac OS X and Windows. For Unix systems, you can clone the source code from [https://github.com/revbayes/revbayes](https://github.com/revbayes/revbayes).

The RevBayes workshops will also use additional for analysis of output and summarization of the MCMC. Please download and install the following:

* Tracer ([http://tree.bio.ed.ac.uk/software/tracer/](http://tree.bio.ed.ac.uk/software/tracer/))
* FigTree ([http://tree.bio.ed.ac.uk/software/figtree/](http://tree.bio.ed.ac.uk/software/figtree/))
* IcyTree (a web-based tree viewer; [http://tgvaughan.github.io/icytree/](http://tgvaughan.github.io/icytree))
* Text editors: [Sublime Text](https://www.sublimetext.com/) or [Atom](https://atom.io)

## Workshop Schedule


### Day 1: 25 September 2017

|   Time            |           Topic                                              | 
|---------------|---------------------------------------------------------| 
| 09:00 - 10:00 | Theory: Introduction to Bayesian phylogenetic inference 
| 10:00 - 10:30 | Break                                                   | 
| 10:30 - 12:00 | Theory: MCMC ([MCMC Robot](http://phylogeny.uconn.edu/mcmc-robot/)), RevBayes demonstration                    | 
| 12:00 - 13:00 | Lunch                                                   | 
| 13:00 - 15:00 | Tutorial: Introduction to MCMC in RevBayes             | 
| 15:30 -16:00  | Break                                                   | 
| 15:30 - 18:00 | Tutorial: Phylogenetic Models in RevBayes              |
| 18:00 - 18:30 | Discussion or finish tutorials               |


### Day 2: 26 September 2017

|   Time            |       Topic                                                 | 
|---------------|--------------------------------------------------------| 
| 09:00 - 10:30 | Theory: Bayesian Divergence-Time Estimation           | 
| 10:30 - 11:00 | Break                                                  | 
| 11:00 - 12:00 | Practical: Total-Evidence Dating in RevBayes [[tutorial PDF](https://github.com/revbayes/revbayes_tutorial/raw/master/tutorial_TeX/RB_TotalEvidenceDating_FBD_Tutorial/RB_TotalEvidenceDating_FBD_Tutorial.pdf), [Data files](https://raw.githubusercontent.com/revbayes/revbayes_tutorial/master/RB_TotalEvidenceDating_FBD_Tutorial/data.zip), [Rev scripts](http://rawgit.com/revbayes/revbayes_tutorial/master/RB_TotalEvidenceDating_FBD_Tutorial/scripts.zip)]          | 
| 12:00 - 13:30 | Lunch                                                  | 
| 13:30 - 15:30 | Practical: Total-Evidence Dating in RevBayes, continued                                  

## Recommended Background Material

### Tutorials

This workshop covers phylogenetic analysis under complex statistical models. Because of the challenging material, workshop participants will benefit from working through introductory material before taking the course. This is particularly true for anyone without a previous introduction to Bayesian phylogenetics. 

* Basic Introduction to Rev and MCMC ([tutorial PDF](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_Basics_Tutorial.pdf))
* Introduction to MCMC Simulation ([tutorial PDF](https://github.com/revbayes/revbayes_tutorial/blob/master/tutorial_TeX/RB_MCMC_Intro_Tutorial/RB_MCMC_Intro_Tutorial.pdf))
* Substitution Models for Time-Constrained Trees ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_CTMC_Tutorial.pdf))
* Partitioned Data Analysis ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_Partition_Tutorial.pdf))
* Model Selection using Bayes Factors ([tutorial pdf](https://github.com/ssb2017/revbayes_intro/blob/master/tutorials/RB_BayesFactor_Tutorial.pdf))

### Reading

Höhna, Landis, Heath, Boussau, Lartillot, Moore, Huelsenbeck, Ronquist. 2016. [RevBayes: Bayesian phylogenetic inference using graphical models and an interactive model-specification language](http://sysbio.oxfordjournals.org/content/65/4/726). Systematic Biology, 65:726-736.

Heath, Huelsenbeck, Stadler. 2014. [The fossilized birth-death process for coherent calibration of divergence-time estimates](http://www.pnas.org/content/111/29/E2957.abstract). Proceedings of the National Academy of Sciences 111(29):E2957–E2966. 

Höhna, Heath, Boussau, Landis, Ronquist, Huelsenbeck. 2014. [Probabilistic graphical model representation in phylogenetics](http://sysbio.oxfordjournals.org/content/63/5/753). Systematic Biology 63:753–771.

Gavryushkina, Heath, Ksepka, Stadler, Welch, Drummond. 2017. [Bayesian total evidence dating reveals the recent crown radiation of penguins](http://sysbio.oxfordjournals.org/content/early/2016/07/27/sysbio.syw060.full). Systematic Biology, 66(1):57-73.

du Plessis, and Stadler. 2015. [Getting to the root of epidemic spread with phylodynamic analysis of genomic data](http://www.sciencedirect.com/science/article/pii/S0966842X15001018). Trends in Microbiology, 23:383-386.

Stadler, Kühnert, Bonhoeffer, and Drummond. 2013. [Birth–death skyline plot reveals temporal changes of epidemic spread in HIV and hepatitis C virus (HCV)](http://www.pnas.org/content/110/1/228). Proceedings of the National Academy of Sciences, 110:228-233.

