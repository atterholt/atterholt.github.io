---
layout: default
---

<h2 align="center" style="color:SeaGreen">
  Research Blog
</h2>

* * *

<h3 style="color:SeaGreen">
  Describing the Garlock Fault Zone with a Fiber (July 2024)
</h3>

Earthquake ruptures happen within fault zones. The structure of fault zones and the physics of earthquakes are thus necessarily intertwined. The structure of fault zones at depth, where large earthquakes typically happen, is difficult to image because fault zones are narrow and seismic imaging resolution degrades with depth. Dense seismic arrays deployed across faults can help resolve important properties of fault zones at depth. Fiber optic seismology allows for the deployment of dense arrays across faults for long periods of time with low logistical burden. In our new study, we use a fiber-optic array that crosses the Garlock Fault, a major fault in Southern California, to explore important characteristics of the fault zone at different depths, and we notice several peculiar things. We find that there is no extensive low velocity feature at depth, which is unusual for a mature fault like the Garlock, potentially suggesting healing of the fault damage zone. Additionally, when we remove the contribution of the complicated velocity structure of the shallow crust, we recover a sharp velocity contrast across the fault which may have implications for the propagation behavior of future ruptures. Check out the study [here](https://doi.org/10.1029/2024JB028900).

| ![Garlock_Schematic.png](/assets/img/Garlock_Schematic.png) | 
|:--:| 
| *Schematic of the Garlock Fault Zone summarizing this study's results.* |

<h3 style="color:SeaGreen">
  Finding patterns in strike-slip ruptures (November 2023)
</h3>

Earthquake ruptures are complicated processes, and their behavior depends on encompassing structure. Characterizing this dependence is valuable, but it is challenging because it requires the systematic evaluation of rupture properties for many events. In this work, we apply a low-dimensional, Bayesian rupture inversion framework to every large strike-slip earthquake of the past three decades. This technique allows us to obtain objective, probabilistic characterizations of all these sources, so that we can confidently identify patterns in rupture behavior with structure. We make several interesting observations, including observations about the directivity of ruptures, the rheology of faults that host large oceanic earthquakes, and the sources of weakness in the oceanic crust that allow for large ruptures in the interior of oceanic plates. Check out the paper [here](https://doi.org/10.1093/gji/ggad459).

| ![Params_FIG.png](/assets/img/Params_FIG.png) | 
|:--:| 
| *Distributions of source quantities computed in this study organized by tectonic region.* |

<h3 style="color:SeaGreen">
  Finding and describing little faults (November 2022)
</h3>

Fault zones are structures that control where and how earthquakes happen. These structures span many scales, and better characterizing faults across these scales contributes to our understanding of these important structures. Small-scale fault zones occupy an observational gap that has historically been challenging to bridge. We develop and implement an approach for finding and characterizing small-scale fault zones using locally scattered surface waves in the earthquake wavefield recorded by distributed acoustic sensing arrays. In this study, we project scattered surface waves backwards in time to locate their source, and we find that the locations of these scatterers are correlated with mapped fault locations. We then develop a fault model and perform synthetic tests to see what we can learn about these faults. We find that by comparing our synthetics with our data, we can constrain the dimensions of these small fault zones. Check out the full paper [here](https://doi.org/10.1029/2022JB025052). This paper pairs nicely with another paper that I helped with that uses scattered waves in the ambient noise wavefield. That paper can be found [here](https://doi.org/10.1029/2022JB024329).

| ![RBNov2022.png](/assets/img/RBNov2022.png) | 
|:--:| 
| *Amplitude of the backprojected scattered wavefield at different frequencies on the left and comparison of these amplitude profiles to mapped faults in the area on the right.* |

<h3 style="color:SeaGreen">
  Robustly describing earthquake ruptures (Mar 2022)
</h3>

Earthquake ruptures mostly happen deep within the Earth, and seismologists try to describe these ruptures using wiggles produced by seismometers that are usually far away and at the surface of the Earth. So, data coverage in seismology is inherently deficient, and this makes solving for rupture parameters challenging. Typically, seismologists try to infer rupture parameters using complicated optimization problems that are poorly constrained. To get more robust estimates of rupture parameters, we developed a framework to solve for so-called stress glut second moments using a fully Bayesian inverse scheme. In short, this framework can yield a low-dimensional, probabilistic description of an earthquake rupture’s spatial extent, propagation direction, and duration. We successfully test this technique on the 2019 Mw 7.1 Ridgecrest Earthquake. Check out the article [here](http://doi.org/10.1029/2021JB023780 ).

| ![RBJul2021.png](/assets/img/RBmar2022.jpg) | 
|:--:| 
| *Representation of the second moments of the stress glut for the 2019 Mw 7.1 Ridgecrest Earthquake.* |

<h3 style="color:SeaGreen">
  Exploring ground shaking variability (Dec 2021)
</h3>

Earthquake hazards estimation is complicated and requires the consideration of numerous important variables. One such important variable is local geology. For example, sedimentary basins like the Los Angeles Basin, which hosts most of the city’s population, are known to amplify ground motion. These geologic structures occur at many scales, including the scale of city blocks. For this reason, identical houses just a few blocks apart could experience highly variant damage from the same earthquake. In this work led by my fellow graduate student, Yan Yang, we leverage the high spatial sampling of distributed acoustic sensing (DAS) to image shallow Earth structure at high resolution near Ridgecrest, CA. We show that the subsurface varies significantly over the distance of a few kilometers. We also find that this structural variability is highly correlated with ground motion variability observed from earthquakes recorded near the array. Check out the EOS feature of this work [here](https://eos.org/research-spotlights/fiber-optic-cables-can-produce-high-resolution-underground-maps). Check out the manuscript [here](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021GL096503).

| ![RBoct2021.png](/assets/img/RBDec2021.png) | 
|:--:| 
| *Summary image showing the velocity model and ground motion variability in the context of the 2021 Ridgecrest Earthquake sequence (from EOS article)* |

<h3 style="color:SeaGreen">
  Illuminating blurry signals (Oct 2021)
</h3>

Distributed acoustic sensing (DAS) is an emergent technology that converts fiber optic cables into dense arrays of strainmeters. This technology may prove transformational because it makes deploying dense seismic arrays relatively easy. But the sensitivity of DAS as a measurement tool is limited by both random noise (instrumental deficiencies) and nonrandom noise (nearby traffic and construction). In pursuit of a technique to remove these sources of noise, we look to curvelets, functions that are very good at representing images with curved boundaries. Using curvelets, we define a framework through which we can partition the DAS-measured wavefield so that we may isolate our desired signal from noise. We show that this technique works by illuminating many Southern California earthquakes that were previously masked by noise. Check out the manuscript [here](https://academic.oup.com/gji/advance-article/doi/10.1093/gji/ggab407/6382997).

| ![RBoct2021.png](/assets/img/RBoct2021.png) | 
|:--:| 
| *Examples of curvelets (affectionately called "little plane waves") in the frequency-wavenumber and spatiotemporal domains.* |

<h3 style="color:SeaGreen">
  Sensing the fabric of rocks (Jan 2021)
</h3>

Many metamorphic rocks have a so-called "fabric." This fabric exists because these rocks are smushed so much during metamorphism, the crystals in the rocks become systematically aligned. This alignment makes these rocks anisotropic, meaning their elastic properties change with orientation. Although we expect anisotropy in rocks to affect our seismic observations at all scales, there have been few studies that examine how anisotropy might affect seismic observations at scales in between those of hand-samples and large crustal models. In our recent study, which includes the bulk of my undergraduate thesis, we set out to better understand anisotropy at these intermediate scales. To do this, we examined directional variability in P-wave travel-times and particle-motions using high frequency data from an active source experiment performed in the Homestake Mine in South Dakota. Check out the full paper [here](https://academic.oup.com/gji/article/224/1/121/5900977?login=true).

| ![RBJun2021.png](/assets/img/RBJun2021.png) | 
|:--:| 
| *Illustration of the scales of heterogeneities that may influence the anisotropy measurements in this study.* |
