---
layout: page
title: Software
permalink: /software/
---

<a href="../functions/scale.tree.rates.R" download>scale.tree.rates.R</a>: This R script contains two functions that can be used to apply the rate heterogeneity quantification/visualization methods described at the bottom of the <a href="https://maxchin0701.github.io/research">Research</a> page. These functions are designed to be easily incorporated into existing analyses which incorporate phylogenetic comparative methods. At the top of the page are existing R packages which scale.tree.rates.R references and calls functions from.
<br><br>
The first function, scaleTreeRates, performs the rate heterogenity analysis and assigns scalars describing relative rates to each edge of a supplied phylogeny. This function takes three mandatory arguments and five optional arguments (defaults available) from users. These arguments are:
<br>
<div style="margin-left: 50px;">
tree (mandatory): the phylogeny to be analyzed.<br><br>
tip.states (mandatory): a vector of tip states for some discrete character which is associated with the phylogeny. The vector should be named such that all tip labels of the phylogeny are represented, but labels themselves can be in a different order than in the phylogeny.<br><br>
model (mandatory): the model which should be used to perform likelihod calculations. This can either be a character string which can be passed to the <i>fitMk</i> function of <i>phytools</i> or a symmetrical transition matrix which has transitions between states categorized into some number of distinct classes<br><br>
fixedQ: an optional argument where a Q-matrix with preestimated rates can be supplied. This is useful for more complex models where you may want to fit and estimate models using Bayesian methods prior to running the analysis. By default, this argument is set to NULL and rates for the model are estimated using maximum likelihood methods (the <i>fitMk</i> function of <i>phytools</i> is called)<br><br>
max.ratio: a number greater than one descirbing the maximum ratio of scalar bins to one. By default this argument is set to 2, with scalar bins ranging between 0.5 and 2.<br><br>
nbins: an integer giving the number of scalar bins above and below one. By default, this argument is set to 10, which translates into 10 bins below one and 10 bins above one, giving a total of 21 scalar bins inclusive of one.<br><br>
max.transition: the maximum number of bins which the scalar associated with an edge can differ from the scalar associated with it's parent edge. By default, this is set to one, i.e each edge has three possible scalars which it can take: the parent scalar, one below the parent scalar, and one above the parent scalar. It is recommended to use this default to ensure a degree of autocorrelation between rates across the phylogeny and avoid overfitting.<br><br>
var.start: This is a logical argument describing whether or not to increment scalar values at the root of the tree. If true, the analysis will be iterated across all pssible root scalar values and the best tree (highest likelihood) returned. If false (default), root scalar is set to one and only a single iteration is performed. <br><br>
pi: method to be used for estimating the prior (state of the discrete character at the root of the tree). This argument can take any character string which can be passed to fitMk, with the default being "fitzjohn"
</div>
<br>
The output of this function is an object of class "phylo" and "phyloscaled". This is the base phylogeny which was supplied by the user with an additional element, "scalar", which is a vector of scalars associated with each edge of the tree. The ordering of this vector is the same as that of the "edge.length"/"edge" elements of the phylogeny.
<br><br>
The second function, plot.phyloScaled, facilitates the visualization of a "phyloscaled" object, plotting the phylogeny with edges colored on a gradient according to their associated scalars. The one mandatory argument and four optional arguments are:
<div style="margin-left: 50px">
tree (mandatory): a phylogeny of class "phyloscaled" and "phylo" <br><br>
palette: the palette to be used for coloring of phylogeny edges, set by default to "RdYlGn" from RColorBrewer. It is recommended that this is a diverging palette so that color gradient formed using scalars is visually informative and easy to interpret. This can either be a character string which is passed to RColorBrewer or "viridis" to specify usage of the standard viridis palette. Because RColorBrewer sets the maximum number of distinct colors for divergent palettes to be 11, any phylogeny which has greater than 11 unique scalar bins represented within it's edges must use a viridis palette. <br><br>
edge.width, cex, show.tip.label: see plot.phylo
<br><br>
Both of these functions can also be found in the R pacakge <a href="https://github.com/coleoguy/evobir">evobiR</a>.
</div>