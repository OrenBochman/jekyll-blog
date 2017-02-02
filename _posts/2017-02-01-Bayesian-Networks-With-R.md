---
layout: post
title: Bayesian Networks With R
tags: [Data Science, Bayesian Networks, Graphical Models, Graph Theory, Bayesian Methodology]
category: [Data Analysis]
date: 2017-02-05
---

# Bayesian Methods

Bayesian methods have been considered advanced topics in data science, typicaly tought in graduate school. These methods have been considered controversial in statistics and this is covered in a popular science book called "The Theory That Would Not Die: How Bayes' Rule Cracked the Enigma Code, Hunted Down Russian Submarines, and Emerged Triumphant from Two Centuries of Controversy ".
Their advantage is that it allows the modeler to to update his or her beliefs based on incoming data as new observation or other knowledge is collected. The challanges are a need to come up with a decent prior distribution which provides a sufficent statitic for describing the initial state of the system. (i.e. it incorprates all available knowledge and can provide answers about any questions about the state of the system)

As observation are made we use Bayes law to update the prior which provides a posterior distribution. In practice baysian are intractable to solve analyticaly and accodinglt the solutions are provided via simulations.

# Bayesian Network Modeling

Bayesian network models extend Baysian methods to cover models with are structured and more specificaly this class of models structures observations in the form of causes and thier effects. Depending on the situation we can learn the structure from data, we use knowledge to incorprate data into an existing network topology. In this cases there are three steps:

*  Modling the network topology - casual structure. (constraint, scoring or hybrid methods)
*  Estimate the parameters (joint distributions at various nodes in the model.
*  Make infrence (use the model to make predictions).


# Bayesian Network Modeling with R




# References

*  Bayesian Networks in R: with Applications in Systems Biology by Nagarajan, Radhakrishnan, Scutari, Marco, Lèbre, Sophie
  *  http://www.springer.com/gp/book/9781461464457
  *  https://www.r-project.org/nosvn/conferences/useR-2013/Tutorials/Scutari.html
*  https://www.youtube.com/watch?v=iRvXfx9IWM0
*  Stan (Python and R)
*  The Theory That Would Not Die: How Bayes' Rule Cracked the Enigma Code, Hunted Down Russian Submarines, and Emerged Triumphant from Two Centuries of Controversy

