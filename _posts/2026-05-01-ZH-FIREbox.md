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
* [EMBER-2](#EMBER)
* [FIREbox](#firebox-simulating-galaxies-at-high-dynamic-range-in-a-cosmological-volume)
* [Kinematic misalignment](#starburst-induced-gas-stars-kinematic-misalignment)
* [Mass-metallicity relation in FIREbox](#inflow-and-outflow-properties-not-gas-fractions-drive-the-evolution-of-the-mass-metallicity-relation)
* [Outflows at high redshift](#the-inefficiency-of-stellar-feedback-in-driving-galactic-outflows-in-massive-galaxies-at-high-redshift)
* [Post-Starbursts](#PSBs)
* [Starbursts](#starbursts-driven-by-central-gas-compaction)
* [Unveiling the dark Universe with HI and EMBER-2](#EMBERHI)

and see also the [HI scale heights in FIREbox](/blog/HI-scale-heights) and [HI disc properties](/blog/HI-disc-properties) blog posts.

----------
<h2 id="PSBs"> The Nature of Post-Starburst Galaxies: Real Deal or Masquerading Impostors? </h2>

Post-starburst galaxies (PSBs) are a population of galaxies with spectral and photometric features indicative of rapid quenching following a recent starburst. The origin and nature of PSBs are currently debated. For example, a number of observed PSBs unexpectedly host substantial molecular gas despite their low inferred star-formation activity. Furthermore, the relative roles of galaxy interactions and quenching mechanisms in PSBs remain unclear. We study PSBs at *z*=0.7 and *z*=1 in the FIREbox cosmological simulation, selecting them primarily via their rest-frame optical photometric properties. The fraction of PSBs in FIREbox broadly agrees with observations, although some candidates are clear impostors with star-formation rates comparable to star-forming galaxies of similar mass. Impostors are rich in molecular gas and have a larger near-to-mid infrared flux ratios compared to quenched PSBs in the sample. The role of galaxy interactions of PSBs in FIREbox depends on their stellar mass. At low stellar masses (≲10<sup>10</sup> M<sub>⊙</sub>), PSBs have interaction fractions comparable to those of non-PSBs in the simulation, consistent with a scenario in which stellar feedback and gas consumption drive temporary quenching of star formation. At higher stellar masses (≳10<sup>10</sup> M<sub>⊙</sub>), PSBs are preferentially interacting systems compared to non-PSBs, with major mergers providing the dominant contribution. We conclude that stellar feedback and galaxy interactions in FIREbox can produce galaxies with observational properties akin to those of observed PSBs, many of which are actively forming stars. Additional quenching channels, such as massive black hole feedback, are likely required to explain a long-lived, quenched population of PSBs. 


Monthly Notices of the Royal Astronomical Society, submitted.


*Cenci, Elia; Feldmann, Robert; Wellons, Sarah; **Gensior, Jindra**; Bassini, Luigi; Bernardini, Mauro; Bezanson, Rachel; Moreno, Jorge; Setton, David J.; Tortora, Lucas*

[ADS](https://ui.adsabs.harvard.edu/abs/2025arXiv250900146C/abstract) / [arXiv](https://arxiv.org/abs/2509.00146)

----------
<h2 id="EMBERHI"> Unveiling the dark Universe with HI and EMBER-2  </h2>

Next-generation radio telescopes will provide unprecedented data volumes of the neutral hydrogen (HI) distribution across cosmic time. The spatial and kinematic distribution of HI is a biased tracer of the underlying matter field, and as such contains information on the distribution of dark matter over a wide range of scales. Extracting dark matter properties from HI, however, is non-trivial because baryonic processes linked to galaxy formation significantly modify the HI distribution. Additionally, methods that use empirical relations, often calibrated via numerical simulations, do not use the full field-level information to model the complex relation between HI and dark matter. We use the recently introduced EMBER-2 model to directly predict dark matter distributions from HI tracers over a wide redshift range, *z*=0−6. After training on cosmological galaxy formation simulations run with FIRE-2, our method accurately recovers key statistics, including dark matter mass fractions, surface density profiles and cross-correlations, where the latter are reconstructed at an accuracy of 20 per cent down to scales of k=100*h* cMpc<sup>−1</sup> constituting a significant improvement over traditional approaches. The presented method may become a key ingredient in future inference pipelines as it can be readily integrated into downstream analysis tasks of radio surveys.


Monthly Notices of the Royal Astronomical Society, 2026, 548, 3, stag204


*Bernardini, Mauro; Feldmann, Robert; Anglés-Alcázar, Daniel; Denzel, Philipp; Gensior, Jindra*

[ADS](https://ui.adsabs.harvard.edu/abs/2026MNRAS.548ag204B/abstract) / [arXiv](https://arxiv.org/abs/2507.05339)

----------
<h2 id="EMBER"> EMBER-2: emulating baryons from dark matter across cosmic time with deep modulation networks  </h2>

Galaxy formation is a complex problem that connects large-scale cosmology with small-scale astrophysics over cosmic time-scales. Hydrodynamical simulations are the most principled approach to model galaxy formation, but have large computational costs. Recently, emulation techniques based on convolutional neural networks (CNNs) have been proposed to predict baryonic properties directly from dark matter simulations. The advantage of these emulators is their ability to capture relevant correlations, but at a fraction of the computational cost compared to simulations. However, training basic CNNs over large redshift ranges is challenging, due to the increasing non-linear interplay between dark matter and baryons paired with the memory inefficiency of CNNs. This work introduces EMBER-2, an improved version of the EMBER (EMulating Baryonic EnRichment) framework, to simultaneously emulate multiple baryon channels including gas density, velocity, temperature, and H I density over a large redshift range, from z=6 to z=0. EMBER-2 incorporates a context-based styling network paired with Modulated Convolutions for fast, accurate, and memory efficient emulation capable of interpolating the entire redshift range with a single CNN. Although EMBER-2 uses fewer than 1/6 the number of trainable parameters than the previous version, the model improves in every tested summary metric including gas mass conservation and cross-correlation coefficients. The EMBER-2 framework builds the foundation to produce mock catalogues of field level data and derived summary statistics that can directly be incorporated in future analysis pipelines. We release the source code at the [official website](https://maurbe.github.io/ember2/). 


Monthly Notices of the Royal Astronomical Society, 2025, 538, 2, 1201


*Bernardini, Mauro; Feldmann, Robert; **Gensior, Jindra**; Anglés-Alcázar, Daniel; Bassini, Luigi; Bieri, Rebekka; Cenci, Elia; Tortora, Lucas; Faucher-Giguère, Claude-André*

[ADS](https://ui.adsabs.harvard.edu/abs/2025MNRAS.538.1201B/abstract) / [arXiv](https://arxiv.org/abs/2502.15875)

----------
## Inflow and outflow properties, not gas fractions, drive the evolution of the mass-metallicity relation ##

Observations show a tight correlation between the stellar mass of galaxies and their gas-phase metallicity (MZR). This relation evolves with redshift, with higher redshift galaxies being characterized by lower metallicities. Understanding the physical origin of the slope and redshift evolution of the MZR may provide important insight into the physical processes underpinning it: star formation, feedback, and cosmological inflows. While theoretical models ascribe the shape of the MZR to the lower efficiency of galactic outflows in more massive galaxies, what drives its evolution remains an open question. In this letter, we analyse how the MZR evolves over z = 0-3, combining results from the FIREbox cosmological volume simulation with analytical models. Contrary to a frequent assertion in the literature, we find that the evolution of the gas fraction does not contribute significantly to the redshift evolution of the MZR. Instead, we show that the latter is driven by the redshift dependence of the inflow metallicity, outflow metallicity, and mass loading factor, whose relative importance depends on stellar mass. These findings also suggest that the evolution of the MZR is not explained by galaxies moving along a fixed surface in the space spanned by stellar mass, gas-phase metallicity, and star formation rate. 


Monthly Notices of the Royal Astronomical Society: Letters, 2024, 532, 1, L14


*Bassini, Luigi; Feldmann, Robert; **Gensior, Jindra**; Faucher-Giguère, Claude-André; Cenci, Elia; Moreno, Jorge; Bernardini, Mauro and Liang, Lichen*

[ADS](https://ui.adsabs.harvard.edu/abs/2024MNRAS.532L..14B/abstract) / [arXiv](https://arxiv.org/abs/2401.13824)

----------
## Starburst-induced gas-stars kinematic misalignment ##

A kinematic misalignment of the stellar and gas components is a phenomenon observed in a significant fraction of galaxies. However, the underlying physical mechanisms are not well understood. A commonly proposed scenario for the formation of a misaligned component requires any pre-existing gas disc to be removed, via fly-bys or ejective feedback from an active galactic nucleus. In this Letter, we study the evolution of a Milky Way mass galaxy in the FIREbox cosmological volume that displays a thin, counter-rotating gas disc with respect to its stellar component at low redshift. In contrast to scenarios involving gas ejection, we find that pre-existing gas is mainly removed via the conversion into stars in a central starburst, triggered by a merging satellite galaxy. The newly-accreted, counter-rotating gas eventually settles into a kinematically misaligned disc. About 4.4 (8 out of 182) of FIREbox galaxies with stellar masses larger than 5e9 Msun at z=0 exhibit gas-star kinematic misalignment. In all cases, we identify central starburst-driven depletion as the main reason for the removal of the pre-existing co-rotating gas component, with no need for feedback from, e.g., a central active black hole. However, during the starburst, the gas is funneled towards the central regions, likely enhancing black hole activity. By comparing the fraction of misaligned discs between FIREbox and other simulations and observations, we conclude that this channel might have a non-negligible role in inducing kinematic misalignment in galaxies. 


*Cenci, Elia; Feldmann, Robert; **Gensior, Jindra**; Bullock, James S.; Moreno, Jorge; Bassini, Luigi and Bernardini, Mauro*

The Astrophysical Journal Letters, 2024, 961, 2, L40 

[ADS](https://ui.adsabs.harvard.edu/abs/2023arXiv231207334C/abstract) / [arXiv](https://arxiv.org/abs/2312.07334)

![Kinematic misalignment letter Fig. 2; face-on and edge-on projections of the galaxy as it undergoes kinematic misalignment. The starburst consumes the existing gas disc, forming a new stellar disc, whilst kinematically misaligned gas (180 degrees) is accreted from a nearby satellite.](/assets/images/KinMis_schematic.png#centre)

----------
## Starbursts driven by central gas compaction ##
Starburst (SB) galaxies are a rare population of galaxies with star formation rates (SFRs) greatly exceeding those of the majority of star-forming galaxies with similar stellar mass. It is unclear whether these bursts are the result of either especially large gas reservoirs or enhanced efficiencies in converting gas into stars. Tidal torques resulting from gas-rich galaxy mergers are known to enhance the SFR by funneling gas towards the centre. However, recent theoretical works show that mergers do not always trigger a SB and not all SB galaxies are interacting systems, raising the question of what drives a SB. We analyse a large sample of SB galaxies and a mass- and redshift-matched sample of control galaxies, drawn from the FIREbox cosmological volume at z=0-1. We find that SB galaxies have both larger molecular gas fractions and shorter molecular depletion times than control galaxies, but similar total gas masses. Control galaxies evolve towards the SB regime by gas compaction in their central regions, over timescales of about 70 Myr, accompanied by an increase in the fraction of ultra-dense and molecular gas. The driving mechanism behind the SB varies depending on the mass of the galaxy. Massive (M∗ > 10<sup>10</sup> M<sub>⊙</sub>) galaxies undergoing intense, long-lasting SBs are mostly driven by galaxy interactions. Conversely, SBs in non-interacting galaxies are often triggered by a global gravitational instability, that can result in a breathing mode in low-mass galaxies.


*Cenci, Elia; Feldmann, Robert; **Gensior, Jindra**; Moreno, Jorge; Bassini, Luigi and Bernardini, Mauro*

Monthly Notices of the Royal Astronomical Society, 2024, 527, 3, 7871

[ADS](https://ui.adsabs.harvard.edu/abs/2024MNRAS.527.7871C/abstract) / [arXiv](https://arxiv.org/abs/2309.09046)

![Starburst paper Fig. 15; a schematic summarising the main results of the paper.](/assets/images/SB_schematic_new.png#centre)

----------

## The inefficiency of stellar feedback in driving galactic outflows in massive galaxies at high redshift  ##
Recent observations indicate that galactic outflows are ubiquitous in high-redshift (high-z) galaxies, including normal star-forming galaxies, quasar hosts, and dusty star-forming galaxies (DSFGs). However, the impact of outflows on the evolution of their hosts is still an open question. Here, we analyse the star-formation histories and galactic outflow properties of galaxies in massive haloes (10<sup>12</sup>M<sub>⊙</sub> < M<sub>vir</sub> < 5×10<sup>12</sup>M<sub>⊙</sub>) at z ≳ 5.5 in three zoom-in cosmological simulations from the MassiveFIRE suite, as part of the Feedback In Realistic Environments (FIRE) project. The simulations were run with the FIRE-2 model, which does not include feedback from active galactic nuclei. The simulated galaxies resemble z > 4 DSFGs, with star-formation rates of ∼1000 M<sub>⊙</sub>yr<sup>−1</sup> and molecular gas masses of M<sub>mol</sub> ~ 10<sup>10</sup> M<sub>⊙</sub>. However, the simulated galaxies are characterized by higher circular velocities than those observed in high-z DSFGs. The mass loading factors from stellar feedback are of the order of ~0.1, implying that stellar feedback is inefficient in driving galactic outflows and gas is consumed by star formation on much shorter time-scales than it is expelled from the interstellar medium. We also find that stellar feedback is highly inefficient in self-regulating star formation in this regime, with an average integrated star formation efficiency (SFE) per dynamical time of 30 per cent. Finally, compared with FIRE-2 galaxies hosted in similarly massive haloes at lower redshift, we find lower mass loading factors and higher SFEs in the high-z sample. We argue that both effects originate from the higher total and gas surface densities that characterize high-z massive systems.  


*Bassini, Luigi; Feldmann, Robert; **Gensior, Jindra**; Hayward, Christopher C.; Faucher-Giguère, Claude-André; Cenci, Elia; Liang, Lichen and Bernardini, Mauro*

Monthly Notices of the Royal Astronomical Society, 2023, 525, 5, 3831


[ADS](https://ui.adsabs.harvard.edu/abs/2023MNRAS.525.5388B) / [arXiv](https://arxiv.org/abs/2211.08423)

![Outflow paper Figs. 6 & 7; showing the mass loading factor as a function of stellar mass colour coded by redshift, peak of the rotation curve velocity and gas surface density.](/assets/images/outflowsFIRE.png#centre)

----------

## FIREbox: simulating galaxies at high dynamic range in a cosmological volume ##
We introduce a suite of cosmological volume simulations to study the evolution of galaxies as part of the Feedback in Realistic Environments project. FIREbox, the principal simulation of the present suite, provides a representative sample of galaxies (~1000 galaxies with M∗ > 10<sup>8</sup>M<sub>⊙</sub> at z = 0) at a resolution (Δx∼20pc , m<sub>b</sub>∼6×10<sup>4</sup>M<sub>⊙</sub> ) comparable to state-of-the-art galaxy zoom-in simulations. FIREbox captures the multiphase nature of the interstellar medium in a fully cosmological setting (L = 22.1 Mpc) thanks to its exceptionally high dynamic range (≳10<sup>6</sup>) and the inclusion of multichannel stellar feedback. Here, we focus on validating the simulation predictions by comparing to observational data. We find that star formation rates, gas masses, and metallicities of simulated galaxies with M∗ < 10<sup>10.5−11</sup>M<sub>⊙</sub> broadly agree with observations. These galaxy scaling relations extend to low masses (M∗∼10<sup>7</sup>M<sub>⊙</sub>) and follow a (broken) power-law relationship. Also reproduced are the evolution of the cosmic HI density and the HI column density distribution at z ~ 0-5. At low z, FIREbox predicts a peak in the stellar-mass-halo-mass relation but also a higher abundance of massive galaxies and a higher cosmic star formation rate density than observed, showing that stellar feedback alone is insufficient to reproduce the properties of massive galaxies at late times. Given its high resolution and sample size, FIREbox offers a baseline prediction of galaxy formation theory in a ΛCDM Universe while also highlighting modelling challenges to be addressed in next-generation galaxy simulations. 


*Feldmann, Robert; Quataert, Eliot; Faucher-Giguère, Claude-André; Hopkins, Philip F.; Çatmabacak, Onur; Kereš, Dušan; Bassini, Luigi; Bernardini, Mauro; Bullock, James S.; Cenci, Elia; **Gensior, Jindra**; Liang, Lichen; Moreno, Jorge and Wetzel, Andrew*

Monthly Notices of the Royal Astronomical Society, 2023, 522, 3, 3831


[ADS](https://ui.adsabs.harvard.edu/abs/2023MNRAS.522.3831F) / [arXiv](https://arxiv.org/abs/2205.15325)


![FIREbox paper figure 1. A visualisation of the gas stars and dark matter at various redshifts.](/assets/images/FBox_fig1.jpeg#centre)
