---
title: "What I've been up to in Zurich: FIRE(box) edition"
layout: post
post-image: "/assets/images/ZH.jpg"
description: "A summary of papers I am involved in with the FIRE folks in Zurich."   
tags:
- FIREbox
- starbursts
- outflows
- simulations
---

List of papers in alphabetical order: 
* [FIREbox](#firebox-simulating-galaxies-at-high-dynamic-range-in-a-cosmological-volume)
<!-- * [Mass-metallicity relation in FIREbox](#inflow-and-outflow-properties-not-gas-fractions-drive-the-evolution-of-the-mass-metallicity-relation) -->
* [Outflows at high redshift](#the-inefficiency-of-stellar-feedback-in-driving-galactic-outflows-in-massive-galaxies-at-high-redshift)
* [Starbursts](#starbursts-driven-by-central-gas-compaction)

and see also the [HI scale heights in FIREbox](/blog/HI-scale-heights) and [HI disc properties](/blog/HI-disc-properties) blog posts.

----------
## Starbursts driven by central gas compaction ##
Starburst (SB) galaxies are a rare population of galaxies with star formation rates (SFRs) greatly exceeding those of the majority of star-forming galaxies with similar stellar mass. It is unclear whether these bursts are the result of either especially large gas reservoirs or enhanced efficiencies in converting gas into stars. Tidal torques resulting from gas-rich galaxy mergers are known to enhance the SFR by funneling gas towards the centre. However, recent theoretical works show that mergers do not always trigger a SB and not all SB galaxies are interacting systems, raising the question of what drives a SB. We analyse a large sample of SB galaxies and a mass- and redshift-matched sample of control galaxies, drawn from the FIREbox cosmological volume at z=0-1. We find that SB galaxies have both larger molecular gas fractions and shorter molecular depletion times than control galaxies, but similar total gas masses. Control galaxies evolve towards the SB regime by gas compaction in their central regions, over timescales of about 70 Myr, accompanied by an increase in the fraction of ultra-dense and molecular gas. The driving mechanism behind the SB varies depending on the mass of the galaxy. Massive (M∗ > 10<sup>10</sup> M<sub>⊙</sub>) galaxies undergoing intense, long-lasting SBs are mostly driven by galaxy interactions. Conversely, SBs in non-interacting galaxies are often triggered by a global gravitational instability, that can result in a breathing mode in low-mass galaxies.


*Cenci, Elia; Feldmann, Robert; Gensior, Jindra; Moreno, Jorge; Bassini, Luigi and Bernardini, Mauro*

Submitted to Monthly Notices of the Royal Astronomical Society, September 13th 2023.

[ADS](https://ui.adsabs.harvard.edu/abs/2023arXiv230909046C) / [arXiv](https://arxiv.org/abs/2309.09046)

![Starburst paper Fig. 15; a schematic summarising the main results of the paper.](/assets/images/SB_schematic.png#centre)

----------
<!-- ## Inflow and outflow properties, not gas fractions, drive the evolution of the mass-metallicity relation ##

Submitted to Monthly Notices of the Royal Astronomical Society Letters, July 24th 2023.

*Bassini, Luigi; Feldmann, Robert; Gensior, Jindra; Faucher-Giguère, Claude-André; Cenci, Elia; Moreno, Jorge; Bernardini, Mauro and Liang, Lichen*

---------- -->

## The inefficiency of stellar feedback in driving galactic outflows in massive galaxies at high redshift  ##
Recent observations indicate that galactic outflows are ubiquitous in high-redshift (high-z) galaxies, including normal star-forming galaxies, quasar hosts, and dusty star-forming galaxies (DSFGs). However, the impact of outflows on the evolution of their hosts is still an open question. Here, we analyse the star-formation histories and galactic outflow properties of galaxies in massive haloes (10<sup>12</sup>M<sub>⊙</sub> < M<sub>vir</sub> < 5×10<sup>12</sup>M<sub>⊙</sub>) at z ≳ 5.5 in three zoom-in cosmological simulations from the MassiveFIRE suite, as part of the Feedback In Realistic Environments (FIRE) project. The simulations were run with the FIRE-2 model, which does not include feedback from active galactic nuclei. The simulated galaxies resemble z > 4 DSFGs, with star-formation rates of ∼1000 M<sub>⊙</sub>yr<sup>−1</sup> and molecular gas masses of M<sub>mol</sub> ~ 10<sup>10</sup> M<sub>⊙</sub>. However, the simulated galaxies are characterized by higher circular velocities than those observed in high-z DSFGs. The mass loading factors from stellar feedback are of the order of ~0.1, implying that stellar feedback is inefficient in driving galactic outflows and gas is consumed by star formation on much shorter time-scales than it is expelled from the interstellar medium. We also find that stellar feedback is highly inefficient in self-regulating star formation in this regime, with an average integrated star formation efficiency (SFE) per dynamical time of 30 per cent. Finally, compared with FIRE-2 galaxies hosted in similarly massive haloes at lower redshift, we find lower mass loading factors and higher SFEs in the high-z sample. We argue that both effects originate from the higher total and gas surface densities that characterize high-z massive systems.  


*Bassini, Luigi; Feldmann, Robert; Gensior, Jindra; Hayward, Christopher C.; Faucher-Giguère, Claude-André; Cenci, Elia; Liang, Lichen and Bernardini, Mauro*

Monthly Notices of the Royal Astronomical Society, 2023, 525, 5, 3831


[ADS](https://ui.adsabs.harvard.edu/abs/2023MNRAS.525.5388B) / [arXiv](https://arxiv.org/abs/2211.08423)

![Outflow paper Figs. 6 & 7; showing the mass loading factor as a function of stellar mass colour coded by redshift, peak of the rotation curve velocity and gas surface density.](/assets/images/outflowsFIRE.png#centre)

----------

## FIREbox: simulating galaxies at high dynamic range in a cosmological volume ##
We introduce a suite of cosmological volume simulations to study the evolution of galaxies as part of the Feedback in Realistic Environments project. FIREbox, the principal simulation of the present suite, provides a representative sample of galaxies (~1000 galaxies with M∗ > 10<sup>8</sup>M<sub>⊙</sub> at z = 0) at a resolution (Δx∼20pc , m<sub>b</sub>∼6×10<sup>4</sup>M<sub>⊙</sub> ) comparable to state-of-the-art galaxy zoom-in simulations. FIREbox captures the multiphase nature of the interstellar medium in a fully cosmological setting (L = 22.1 Mpc) thanks to its exceptionally high dynamic range (≳10<sup>6</sup>) and the inclusion of multichannel stellar feedback. Here, we focus on validating the simulation predictions by comparing to observational data. We find that star formation rates, gas masses, and metallicities of simulated galaxies with M∗ < 10<sup>10.5−11</sup>M<sub>⊙</sub> broadly agree with observations. These galaxy scaling relations extend to low masses (M∗∼10<sup>7</sup>M<sub>⊙</sub>) and follow a (broken) power-law relationship. Also reproduced are the evolution of the cosmic HI density and the HI column density distribution at z ~ 0-5. At low z, FIREbox predicts a peak in the stellar-mass-halo-mass relation but also a higher abundance of massive galaxies and a higher cosmic star formation rate density than observed, showing that stellar feedback alone is insufficient to reproduce the properties of massive galaxies at late times. Given its high resolution and sample size, FIREbox offers a baseline prediction of galaxy formation theory in a ΛCDM Universe while also highlighting modelling challenges to be addressed in next-generation galaxy simulations. 


*Feldmann, Robert; Quataert, Eliot; Faucher-Giguère, Claude-André; Hopkins, Philip F.; Çatmabacak, Onur; Kereš, Dušan; Bassini, Luigi; Bernardini, Mauro; Bullock, James S.; Cenci, Elia; Gensior, Jindra; Liang, Lichen; Moreno, Jorge and Wetzel, Andrew*

Monthly Notices of the Royal Astronomical Society, 2023, 522, 3, 3831


[ADS](https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.3831F) / [arXiv](https://arxiv.org/abs/2205.15325)


![FIREbox paper figure 1. A visualisation of the gas stars and dark matter at various redshifts.](/assets/images/FBox_fig1.jpeg#centre)