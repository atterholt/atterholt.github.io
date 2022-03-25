---
layout: default
---

<h2 align="center" style="color:SteelBlue">
  Research Blog
</h2>

* * *

<h3 style="color:SteelBlue">
  Exploring ground shaking variability (Dec 2021)
</h3>

Earthquake hazards are controlled by many competing variables such as earthquake size, earthquake proximity, and building integrity. Another competing variable is local geology. For example, sedimentary basins like the Los Angeles Basin, which hosts most of the city’s population, are known to amplify ground motion. These geologic structures occur at many scales, including the scale of city blocks. For this reason, identical houses just a few blocks apart could experience highly variant damage from the same earthquake. In this work led by my fellow graduate student, Yan Yang, we leverage the high spatial sampling of distributed acoustic sensing (DAS) to image shallow Earth structure at high resolution near Ridgecrest, CA. We show that the subsurface varies significantly over the distance of a few kilometers. We also find that this structural variability is highly correlated with ground motion variability observed from earthquakes recorded near the array. Check out the EOS feature of this work [here](https://eos.org/research-spotlights/fiber-optic-cables-can-produce-high-resolution-underground-maps). Check out the manuscript [here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021GL096503).

| ![RBoct2021.png](/assets/img/RBdec2021.png) | 
|:--:| 
| *Summary image showing the velocity model and ground motion variability in the context of the 2021 Ridgecrest Earthquake sequence (from EOS article)* |

<h3 style="color:SteelBlue">
  Illuminating blurry signals (Oct 2021)
</h3>

Distributed acoustic sensing (DAS) is an emergent technology that converts fiber optic cables into dense arrays of strainmeters. This technology may prove transformational because it makes deploying dense seismic arrays relatively easy. But the sensitivity of DAS as a measurement tool is limited by both random noise (instrumental deficiencies) and nonrandom noise (nearby traffic and construction). In pursuit of a technique to remove these sources of noise, we look to curvelets, functions that are very good at representing images with curved boundaries. Using curvelets, we define a framework through which we can partition the DAS-measured wavefield so that we may isolate our desired signal from noise. We show that this technique works by illuminating many Southern California earthquakes that were previously masked by noise. Check out the manuscript [here](https://academic.oup.com/gji/advance-article/doi/10.1093/gji/ggab407/6382997).

| ![RBoct2021.png](/assets/img/RBoct2021.png) | 
|:--:| 
| *Examples of curvelets (affectionately called "little plane waves") in the frequency-wavenumber and spatiotemporal domains.* |

<h3 style="color:SteelBlue">
  Robustly describing earthquake ruptures (Jul 2021)
</h3>

Earthquake ruptures mostly happen deep within the Earth, and seismologists try to describe these ruptures using wiggles produced by seismometers that are usually far away and at the surface of the Earth. So, data coverage in seismology is inherently deficient, and this makes solving for rupture parameters challenging. Typically, seismologists try to infer rupture parameters using complicated optimization problems that are poorly constrained. To get more robust estimates of rupture parameters, we developed a framework to solve for so-called stress glut second moments using a fully Bayesian inverse scheme. In short, this framework can yield a low-dimensional, probabilistic description of an earthquake rupture’s spatial extent, propagation direction, and duration. We successfully test this technique on the 2020 Mw 7.7 Caribbean Earthquake. Check out the preprint [here](https://www.essoar.org/doi/10.1002/essoar.10507583.1).

| ![RBJul2021.png](/assets/img/RBJul2021.png) | 
|:--:| 
| *Representation of the second moments of the stress glut for the 2020 Mw 7.7 Caribbean Earthquake.* |

<h3 style="color:SteelBlue">
  Sensing the fabric of rocks (Jan 2021)
</h3>

Many metamorphic rocks have a so-called "fabric." This fabric exists because these rocks are smushed so much during metamorphism, the crystals in the rocks become systematically aligned. This alignment makes these rocks anisotropic, meaning their elastic properties change with orientation. Although we expect anisotropy in rocks to affect our seismic observations at all scales, there have been few studies that examine how anisotropy might affect seismic observations at scales in between those of hand-samples and large crustal models. In our recent study, which includes the bulk of my undergraduate thesis, we set out to better understand anisotropy at these intermediate scales. To do this, we examined directional variability in P-wave travel-times and particle-motions using high frequency data from an active source experiment performed in the Homestake Mine in South Dakota. Check out the full paper [here](https://academic.oup.com/gji/article/224/1/121/5900977?login=true).

| ![RBJun2021.png](/assets/img/RBJun2021.png) | 
|:--:| 
| *Illustration of the scales of heterogeneities that may influence the anisotropy measurements in this study.* |
