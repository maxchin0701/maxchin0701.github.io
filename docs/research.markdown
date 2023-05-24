---
layout: page
title: Research
permalink: /research/
---

<style>
div {
  text-align: justify;
  text-justify: inter-word;
}
</style>

<figure style="float:right;margin-left:20px;margin-bottom:30px;height:284px;width:213px;text-align:center">
	<img src="../images/Cichaz stocktanks.jpg" alt="Stocktanks at the CICHAZ field station">
	<figcaption><i>Xiphophorus stocktanks at CICHAZ field station</i></figcaption>
</figure>
<div>
Getting involved with research in evolutionary biology has been a long time dream of mine, and I feel extremely fortunate that I have been gifted so many opportunities to be able to contribute to so many projects during my time as an undergraduate student. I work on projects with two primary groups: the Rosenthal Lab based in the Department of Biology at the University of Padua, and the <a href="http://coleoguy.github.io/">Blackmon Lab</a> based in the Department of Biology at Texas A&M University. My work with the Rosenthal Lab focuses on morphometrics and computational forward time simulation of early generation hybrid populations in poecilid fish (<i>Xiphophorus birchmanni</i> and <i>X. malinche</i>), focusing particularly on the interactions between polygenic traits that are targets of mate choice and ecological selection. My work in the Blackmon Lab encompasses a variety of projects studying the evolution of genome structure, with a special emphasis on sex chromosome evolution and the development/application of phylogenetic comparative methods.<br><br>
</div>

<h3>Drivers of morphometric differentiation in early genetation hybrid <i>Xiphophorus</i> swordtails</h3>
PIs: Drs. <a href="https://www.biologia.unipd.it/en/department/people/teacher-details/?tx_wfqbe_pi1%5Baccount%5D=gil-rosenthal">Gil Rosenthal</a> and <a href="https://www.bio.tamu.edu/faculty-page-heath-blackmon/">Heath Blackmon</a>
<br>
<figure style="float:left;margin-right:20px;margin-bottom:40px;height:300px;width:300px;text-align:center">
        <img src="../images/Xipho hybrids.png" alt="Xiphophorus hybrids">
        <figcaption><i>Xiphophorus hybrids across different environments and time points</i></figcaption>
</figure>
<div>
With advances in sequencing methods corresponding with more access than ever to sequence data, it has become increasingly apparent that naturally occurring hybridization events are significantly more common than they were once thought to be. When two hybridizing species are differentiated along multiple axes, hybrids between them are able to explore a wide range of trait space and populations of these hybrids are diverse in phenotype. When diverse phenotypes are combined with diverse selection regimes, populations differentiate rapidly. The components of selection that drive differentiation in populations following gene flow can often be difficult to tease apart using purely empirical approaches, but computational simulations facilitate easy exploration of a wide variety of selection regimes. If both empirical and computational methods are applied in conjunction, statistical model fitting approaches can then be used to infer the selection regime that best corresponds with phenotypes observed empirically.
</div>
<br>
<figure style="float:right;margin-left:20px;margin-bottom:50px;height:160px;width:300px;text-align:center">
	<img src="../images/Xipho morph.jpg" alt="Xiphophorus morphometric measurements">
        <figcaption><i>Morphometrics collected for stocktank Xiphophorus hybrids</i></figcaption>
</figure>
<div>
My work in the Rosenthal Lab applies these concepts to a system revolving around two species of naturally hybridizing <i>Xiphophorus</i> swordtail fish, <i>X. birchmanni</i> and <i>X. malinche</i>. These sister species are diverged morphologically, physiologically, and behaviorally, with differentiated habitat preferences and mate choice behavior resulting in discordance between the selective pressures encountered by each species. Hybrids between the two species exhibit diverse morphology, physiology, and behavior, representing axes along which hybrid populations can differentiate.  As part of an ongoing project funded under the NSF’s Long Term Research in Environmental Biology grant, the Rosenthal lab monitored replicated mesocosm hybrid populations at regular intervals over a five year period, collecting a variety of morphometric data from individuals in the populations. To complement this extensive empirical dataset, I designed individual-based forward time population simulations that replicate the structure of our empirical populations. These simulations incorporate up to six polygenic traits which have genomic architecture informed by empirical  studies on quantitative trait loci in the system, and implement various combinations of selection functions and strengths, including ecological selection, incompatibility selection, and various forms of mate choice. Where sufficient empirical phenotypic data was available (at this point in time, long term empirical data only exists for morphometric measurements), sum mean error approaches were used to determine the selection regime that resulted in the simulated phenotypes which most closely fit empirical phenotypes. 
</div>
<br>
<figure style="float:left;margin-right:20px;margin-bottom:45px;height:200px;width:300px;text-align:center">
        <img src="../images/Sword index plot.jpg" alt="Sword length plot">
        <figcaption><i>Indirect ecological selection drives differentiation in a sexual display trait (sword index)</i></figcaption>
</figure>
<div>
One of the major findings from this project is that direct selection on traits which are polygenic can lead to differentiation in other polygenic traits which are not direct targets of selection. This results from physical linkage between loci which contribute genetic variation to different traits, some degree of which is bound to occur when traits are highly polygenic. It is for this reason that we observe in our simulations that differentiation in sword index, a morphometric trait which is relevant to mait choice, is driven primarily by ecological selection on thermal tolerance, a physiological trait. This "dragging" along of traits has long been hypothesized as one of the primary drivers of morphometric differentiation in empirical mesocosm populations encountering different environmental conditions, and using simulations we are able to show that this does indeed occur. We demonstrate that in early generation populations encountering multiple sources of selection pressure, differentiation in display traits relevant to mate choice is driven by indirect selection through physical linkage with physiological traits which are under ecological selection. We suggest that direct selection on display traits by means of sexual selection is hindered by the need for resetablishment of linkage disequilibrium between loci associated with display traits and preference for these display traits follwing admixture and the associated breaking of linkage disequilibrium.<br><br>
</div>

<h3>Sex chromosome autosome fusions in mammals</h3>
PIs: Dr. <a href="https://www.bio.tamu.edu/faculty-page-heath-blackmon/">Heath Blackmon</a>

<figure style="float:right;margin-left:20px;margin-bottom:80px;height:225px;width:300px;text-align:center">
        <img src="../images/Platy karyotype.png" alt="Platypus karyotype">
        <figcaption><i>Karyotype of a male platypus. Note the novel sex chromosome system possessing multiple X and Y chromosomes</i></figcaption>
</figure>
<div>
Fusions between chromosomes are a key mechanism by which genome structure evolves. Fusions between autosomes and sex chromosomes are especially interesting due to the potential they have to form new associations between sex and loci which were historically autosomal. There are certain conditions under which the formation of such new associations may have beneficial effects on fitness. One of these conditions is the presence of intra-locus sexual antagonism at an autosomal locus. Intra-locus sexual antagonism describes a situation where an allele at an autosomal locus confers differential fitness effects which are dependent on sex. Because the polarity of fitness effects associated with loci experiencing sexual antagonism is dependent on sex, a possible mechanism towards the resolution of intra-locus sexual antagonism lies in the formation of non-random associations between sex and inheritance of the allele in question. Fusions between sex chromosomes and autosomes have the potential to form these non-random associations, and as such, resolution of intra-locus sexual antagonism has long been hypothesized as a potential selective pressure driving sex chromosome-autosome fusion (SAF) events. However, attempts to find empirical evidence for positive selection on SAF events have been mostly restricted to smaller taxonomic clades, and often return mixed results. The best support for broad selection for SAF events would be an excess of such fusion types on large taxonomic scales. Diverse in karyotype and heterogenous in rates of karyotypic evolution, mammals represent an interesting taxonomic class upon which to evaluate this hypothesis and utilize methods which have previously only been applied to smaller taxonomic clades on a limited scale
</div>
<br>
<figure style="float:left;margin-right:20px;margin-bottom:80px;height:200px;width:169px;text-align:center">
        <img src="../images/mk model.jpg" alt="SAF markov model">
        <figcaption><i>A biologically realistic markov model describing karyotypic evolution</i>
	</figcaption>
</figure>
<div>
This project incorporates an extensive database of mammalian karyotypes that has been maintined by the Blackmon Lab, a modern timetree of mammalian taxa which incorporates genomic data, and a biologically realistic markov model describing the evolution of karyotype, expanding on phylogenetic comparative methods used in the study of discrete character evolution to explore the evolution of karyotype across time in 950 mammal species. We estimate rates associated with our model of character evolution using Bayesian MCMC methods, and use stochastic mapping techniques to produce maps of ancestral karyotypes and fusion events. We develop new methods to "fill the gaps" associated with stochastic maps when rate heterogenity throughout the phylogeny being mapped is prominent, expanding the applicapbility of this commonly used phylogenetic comparative method.  Observed SAF events as a proportion of total fusion events are extracted and compared against proportions expected given a null hypothesis of no selection on fusions of any kind. 
</div>
<br>
<figure style="float:right;margin-left:20px;margin-bottom:80px;height:300px;width:300px;text-align:center">
        <img src="../images/mammal smap.jpg" alt="Mammals stochastic map">
        <figcaption><i>Stochastic map depicting evolution in karyotype (autosome number and sex chromosome fusion state) across a mammalian phylogeny</i>
        </figcaption>
</figure>
<div>
Our preliminary results suggest that observed proportions of SAF events are significantly lower than proportions expected under a null model, with this being true of both mammals as a whole and several mammal subclades. We hypothesize that this is driven by high rates estimated for autosome – autosome fusions and fissions in our model. Various factors such as extreme rate heterogeneity and the inability of our current model to account for multiple SAF events may contribute to this overestimation. Our next steps are to develop a new model which allow for such multiple fusions and rerun the analyses under this new model. We predict that this should result in null and observed SAF proportions that are more aligned.