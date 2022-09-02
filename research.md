---
layout: default
permalink: /research/
---

Cosmology has gone through a radical transformation during the last decades; what once was a data-starved science with challenging model testing is now a data-driven precision science where there is a consensus cosmological model, &Lambda;CDM well supported by observations.  However, precision does not mean accuracy, and there are some tensions between experiments that show potential cracks in the model. Moreover, there are many unknowns to be answered yet: what is the nature of dark matter? What is driving the accelerated expansion of the late Universe? What physics drove the first instants of the Universe? Broadly speaking, I am interested in all this (and in extragalactic physics such as reionization and galaxy evolution), though of course I cannot work in all of it.

Although my research is quite broad and I always like to dip my toes in new fields and studies, my main areas of research are:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Line-Intensity Mapping]({{ site.url }}/research/#line-intensity-mapping){: .button}  &nbsp; &nbsp;  [Dark Matter]({{ site.url }}/research/#dark-matter){: .button} &nbsp; &nbsp;  [Cosmological tensions]({{ site.url }}/research/#cosmological-tensions){: .button}

We only have one Universe to probe, hence the experiments in cosmology are intrinsically different than in other sciences. Therefore, it is of radical importance to exhaust the information out there, deriving new formalisms to improve the prediction of the theoretical models, statistical tools to maximize the understanding obtained from observations, as well as innovative paths to use existing observations and measurements to probe new physics. In particular, what I enjoy the most is studying novel ways to access the information that we can gather from cosmological observations.

![Picture]({{ site.url }}/assets/imgs/LIMEpochsCut.png)

<center> Different epochs in the history of the Universe and the cosmological observables to directly probe them. (from Bernal & Kovetz, 2022) </center>

<br/>

# Line-Intensity Mapping

Line-intensity mapping (LIM) is a technique that employs low-aperture instruments to quickly scan the sky and collect all the incoming radiation, targetting identifiable spectral lines to recover radial information through good experimental spectral resolution. Since it does not requires to resolve individual sources, LIM provides access to redshifts well beyond the reach of galaxy surveys and is also sensitive to the population of faint sources that are hard to resolve individually. This provides direct access to epochs of the history of the Universe and regimes that are unaccessible otherwise.

Since overall fluxes are measured, LIM is both sensitive to the large-scale matter distribution and the astrophysical processes that drive the emission of each line in atomic and molecular gas clouds within and around galaxies. Thus, targetting several spectral lines provides a more complete picture of the interstellar and intergalactic media. In summary, studying intensity fluctuations with LIM promises to deepen our understanding of various questions related to galaxy formation and evolution, cosmology, and fundamental physics, while being complementary to other techniques and cosmological probes.

![Picture]({{ site.url }}/assets/imgs/LIM_maps.png)

<center> Simulated projected maps at redshift 5 of all galaxies, those that would be observed with a galaxy survey and LIM observations of CO and [CII]. (from <a href="https://arxiv.org/abs/2206.15377">Bernal & Kovetz, 2022</a>) </center>

<br/>

If you are new to LIM, maybe you want to check the recent [LIM theory review](https://arxiv.org/abs/2206.15377) I wrote with Ely Kovetz for The Astronomy and Astrophysics Review journal, focused on spectral lines related with star formation, like CO, [CII], Lyman-&alpha;, etc. There you can read about the primary target lines and the astrophysical processes that drive their emission, different approaches to model their intensities and analyze the data, the scientific prospects for the forthcoming experiments, and the synergies with other cosmological observables. 

![Picture]({{ site.url }}/assets/imgs/footprints_mosaic1.png)

<center> Observing fields of a selection of current and forthcomin LIM surveys, galaxy surveys and CMB experiments, with zoom-in regions in hte bottom panels. Purple circular regions correspond to SPHEREx deep fields. (from <a href="https://arxiv.org/abs/2206.15377">Bernal & Kovetz, 2022</a>) </center>

<br/>

My main work in LIM has been improving the formalism to measure summary statistics from the line-intensity maps and get a theoretical prediction and the development of new science cases to employ LIM observations beyond the straightforward applications. Some examples of my work in LIM formalism include an improvement of the LIM power spectrum formalism and the derivation of the first analytic covariance between 1- and 2-point statistics of line-intensity maps (with Gabriela Sato-Polito). I have also motivated LIM surveys for probing new physics, such as the nature of dark energy extending the cosmic distance ladder to much higher redshifst, or developing strategies to detect the product of exotic radiative decays (such as dark matter or neutrinos) from line-intensity maps. 

<p float="left">
<img src="{{ site.url }}/assets/imgs/DA_constraints-1.png" style="width:375px;height:245px;float:left;margin:20px"/>  
<img src="{{ site.url }}/assets/imgs/Hz_constraints-1.png" style="width:375px;height:245px;float:left;margin:20px"/>
</p>

<center> 68% confidence level marginalized current and forecasted constraints on the angular diameter distance (left) and the Hubble expansion rate (right) as function of redshift for eBOSS and DESI (galaxy surveys), and the forthcoming LIM measurements with SPHEREx, COMAP and a futuristic stage 3 CO LIM survey. (from <a href="https://arxiv.org/abs/1907.10065">Bernal, Breysse & Kovetz, 2019</a>)</center>

<br/>


Finally, I am currently working with Gabriela Sato-Polito and Nickolas Kokron in the development of [SkyLine](), a flexible code to generate and analyze mock LIM observations in a lightcone, including observational effects, continuum foregrounds and contributions from line interlopers (spectral lines that redshift to the same observed frequency than the target line) and with general astrophysical halo properties inherited from [UniverseMachine](https://arxiv.org/abs/1806.07893). More interestingly, this will be the first time that LIM mocks belong to a coherent simulated sky including a plethora of other observables, such as galaxy clustering (maps generated also within SkyLine) and CMB secondary anisotropies, cosmic infrared background, weak lensing, and radio galaxies from the catalogues from [MDPL2 synthetic sky simulation](https://yomori.github.io/mdpl2synsky/index.html) by Yuuki Omori. The simulated maps shown in this page are done with SkyLine.

![Picture]({{ site.url }}/assets/imgs/CO_CII_maps.png)

<center> Three-dimensional mock CO and CII intensity mapps in observed frequency bands such as both correspond to the same volume at redshifts between 2.5 and 3.5, applying COMAP-like and FYST-like resolutions, respectively. (from <a href="">Sato-Polito, Kokron & Bernal, 2022</a>)</center>

<br/>

**Related talks**: 

- [Exploring the Universe with Line-Intensity Mapping]({{ site.url }}/assets/docs/ICC.pdf) - Institute of Cosmos Sciences, University of Barcelona (ICC-UB) - 2022.
- [The Cosmic Expansion History from Line-Intensity Mapping]({{ site.url }}/assets/docs/JLB_CosmicContro.pdf) - Cosmic Controversies conference, Kavli Institute for Cosmological Physics, University of Chicago (KICP-UChicago) - 2019

# Dark Matter

Dark matter is a key component of our understanding of the Universe presumed to interact with visible matter primarily through gravity, making up to &sim;26% of the current energy density of the Universe. However, a microscopic model backed by observational and experimental evidence is yet to be found. The standard, cold dark matter is modeled as a non-relativistic, pressure-less fluid only sensitive to gravity. Nonetheless, most of existing dark matter candidates involve additional (faint) interactions with baryons. These faint interactions, of all kind of flavors, results in an extremely rich phenomenology that enables a variety of search strategies, ranging from collider searches, to ground experiments, to astrophysical and cosmological probes (either seeking directly the products of the dark matter-baryon interactions or indirect signatures of them).

My main work in dark matter searches involves the phenomenological impact of dark matter interactions beyond gravity in astrophysical and cosmological observables, and the development of strategies to detect the signatures of such processes in the observations. The dark matter candidate I have studied the most is the axion (a particle initially proposed to solve the strong-CP problem that can also act as dark matter) and axion-like particles (ALPs). Depending on their mass, ALPs can be searched through their impact in the small-scale matter clustering, photon-axion oscillations in the presence of magnetic fields, and direct or indirect surveys of their decay into photons. 

<center>
<img src="{{ site.url }}/assets/imgs/AxionPhoton.png" style="width:500px;height:400px"/>  </center>
<center> Current (opaque) and projected (transparent) constraints on the axion-photon coupling from laboratory, astrophysical and cosmological searches, in 2021. Ultra-light axions (an extremely interesting dark-matter candidate that modifies small-scale clustering) is &sim;15 orders of magnitude to the left limit of this plot. (from <a href="https://arxiv.org/abs/2203.14923">Adams et al, 2022</a>; you can find data and figures in <a href="https://cajohare.github.io/AxionLimits/docs/ap.html">this website</a>)</center>

<br/>

I have mostly focused on the decay of ALPs in the multielectronvolt mass range. This mass range is surprisingly hard to probe, as seen in the figure above. However, contributions from radiative decay of ALPs in this mass range may contribute to the recent 4&sigma; excess in the cosmic optical background measured by the LORRI camera in the New Horizons spacecraft. In order to test that possibility, I have searched for contributions from these decays to the extragalactic background light in the attenuation of flux of &gamma;-ray from distant blazars. Furthermore, I have developed novel strategies to detect the signatures from exotic radiative decays like these or neutrino decays in LIM measurements, with very promising prospects. I will continue to develop this program with other strategies.

<center>
<img src="{{ site.url }}/assets/imgs/constraints_zoom_3sigma-1.png" style="width:500px;height:400px"/>  </center>
<center> 68%, 95% and 99% confidence level constraints on the
ALP parameters from &gamma;-ray attenuation (dark blue contours), along with current strongest 95% con-
fidence level bounds and preferred region to explain the cosmic optical background
excess and the QCD axion band. This analysis returns the strongest constraints on the photon-ALP coupling in the multi-electronvolt mass range. (from <a href="https://arxiv.org/abs/2208.13794">Bernal et al, 2022</a>)</center>

<br/>

I have also worked in other dark matter models. One example involves dark matter-baryon scattering, which suppresses matter clustering at small scale but also changes the baryon temperatures. My collaborators and I have derived for the first time the temperature perturbation equations including the contributions from this exotic scattering. We found that accounting for these effects further suppresses clustering at small scales at early times, which, together with the modified temperature perturbations, would affect the formation of the first galaxies and modify the signal of HI LIM from cosmic dawn. Finally, I have also studied primordial black holes, which could be part of the dark matter, and could also be the seeds of the supermassive black holes that are observed at very high redshifts and are too massive to be explained with standard astrophysical mechanisms. 

**Related talks**:
- [Looking for multi-electronvolt axion-like particle dark matter on the sky]({{ site.url }}/assets/docs/IFCA.pdf) - Instituto de Fisica de Cantabria, IFCA - 2022.
- [Dark matter and neutrino decays with line-intensity mapping]({{ site.url }}/assets/docs/FermiLab.pdf) - FermiLab - 2021.

# Cosmological tensions

&Lambda;CDM is a model that successfully reproduces most of the observations that we have available today, with some of its cosmological parameters constrained below the percent level precision. However, as observations, experiments and the formalism to treat and analyze the data improves and final measurements become more precise, tensions between experiments and cosmological observables have arised. In particular, the most remarkable tensions involve the Hubble constant, *H*<sub>0</sub>, which quantifies the current expansion rate of the Universe, and *&sigma;*<sub>8</sub> (and its combination with the matter density parameter *&Omega;*<sub>m</sub>: *S*<sub>8</sub>=*&sigma;*<sub>8</sub>*&Omega;*<sub>m</sub><sup>1/2</sup>), which quantifies the amplitude of the matter perturbations today smoothed over scales of 8 Mpc/*h*. In particular, in the late Universe we measure a faster expansion and reduced clustering with respect to the expectations of &Lambda;CDM from the measurements of the early Universe.

Although these tensions may be smoking guns for the need of physics beyond the standard cosmological model, they may also rise due to unaccounted for systematics in the observations or their analysis. Strikingly enough, nonetheless, there seems to be a trend in both cases, in which the tension arises between probes of the early and the late Universe. On the other hand, most of the models aiming to solve one of the tensions tend to worsen the other.

Most of my work regarding cosmological tensions has been on the Hubble constant tension, performing model-agnostic analyses (analyses with as-general-as-possible parametrizations, independent on any specific cosmologicla model) to find the features in the data that drive the tension. That way, I highlight that the tension can be reframed as a mismatch between the anchors of the direct distance ladder (*H*<sub>0</sub>), and the inverse distance ladder (which uses the sound horizon *r*<sub>d</sub> at radiation drag to calibrate the expansion history using BAO measurements), with their product very well constraint from BAO+SNeIa. This has led theoretical research, as the most promising models aiming to solve this tension depend on the reduction of *r*<sub>d</sub> to succeed. I have experience working with some of these models, such as early dark energy or hot QCD axions as additional relativistic particles in the early Universe.

<p float="left">
<img src="{{ site.url }}/assets/imgs/H0_gaussians-1.png" style="width:375px;height:300px;float:left;margin:20px"/>  
<img src="{{ site.url }}/assets/imgs/Picture1-1.png" style="width:375px;height:300px;float:left;margin:20px"/>
</p>

<center> <em>Left</em>: Summary of constraints on <em>H</em><sub>0</sub> from probes of the early (<em>Planck</em>, P18; Baryon acoustic oscillations with a prior from Big Bang nucleosynthesis, BAO+BBN), the late (cosmic chronometers, CC; strong lensing time delays from TDCOSMO) and the local Universe (local distance ladder with supernovae calibrated from the CCHP and SHOES temas). Gaussian posteriors are assumed, and note that ach result is subject to different model assumptions <em> Right</em>: Without an absolute distance scale, BAO+SNeIa constrain the product <em>r</em><sub>d</sub><em>H</em><sub>0</sub> (pink); here it is clear the mismatch between the two anchors of the distance ladder. (from <a href="https://arxiv.org/abs/2102.05066">Bernal et al, 2021</a> and <a href="https://arxiv.org/abs/1607.05617">Bernal et al, 2016</a>, respectively)</center>

<br/>

No matter how exciting the perspective of physics beyond &Lambda;CDM may be, systematic errors must be considered, both in the analysis of the observations and in the theoretical considerations of potential new physics explored. with that in mind, I have checked that the standard BAO measurements (which assume &Lambda;CDM) are robust for models that modify the standard cosmological model before recombination, and I have developed a methodology to combine data sets and likelihoods to obtain conservative constraints, no matter the degree of tension between them. 

In addition, I have also collaborated with scientists from TDCOSMO in obtaining a more model-independent constraint on *H*<sub>0</sub> from strong lensing time delays, and with the SH0ES team to obtain a measurement of *H*<sub>0</sub> discarding SNeIa and using cepheids as the last step in the local distance ladder. Regarding alternative measurements of *H*<sub>0</sub> or related quantities, I have collaborated in a novel analysis of globular clusters to infer the age of the oldest ones, and using it to infer the age of the Universe marginalizing over other cosmological parameters. Since the age of the Universe *t*<sub>U</sub>&sim;1/*H*<sub>0</sub>, this constraint informs potential solutions to the Hubble constant tension. Although current systematic errors limit this measurement, it hints to the need of modifying both the early and late Universe to reconcile all measurements.

<p float="left">
<img src="{{ site.url }}/assets/imgs/triangle_rsh-1.png" style="width:280px;height:250px;float:left;margin:10px"/>  
<img src="{{ site.url }}/assets/imgs/triangle_H0t-1.png" style="width:280px;height:250px;float:left;margin:10px"/>
<img src="{{ site.url }}/assets/imgs/legend-1.png" style="width:210px;height:210px;float:left;margin:40px 10px"/>
</p>

<center> The new cosmic triangles. 68% confidence level marginalized constraints, showing triads corresponding to the sound horizon at radiation drag and the reduced Hubble constant (left) and the age of the Universe and the Hubble constant (center). All points in each ternary plot sum up to 0, while the ticks in the axes determine the direction of equal values for each axis. (from <a href="https://arxiv.org/abs/2102.05066">Bernal et al, 2021</a>)</center>

<br/>

I am starting to think now in the clustering tension, since there are more observations, probes and analyses focused on these quantities and the tension keeps growing. At the moment, I am exploring different models of interactions in the dark sector that may explain the reduced clustering in the late Universe with respect to the predictions from the evolution of the observed CMB.

**Related talks**:

- [The trouble with *H*<sub>0</sub> (and beyond)]({{ site.url }}/assets/docs/KICP_JLB.pdf) - Kavli Institute for Cosmological Physics, KICP, UChicago - 2021.

