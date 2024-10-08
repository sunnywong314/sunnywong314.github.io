---
permalink: /SNIa/
title: "Type Ia/Iax Supernova Progenitors"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/sn2011fe.jpg
excerpt: >
  <br />
  Type Ia supernovae originate from thermonuclear explosions of carbon-oxygen white dwarfs, aided by mass transfer from a binary companion. <br />
  <br />
  Nevertheless, it has long been debated how the thermonuclear explosion happens, and what the nature of the binary companion is.  <br />
  <br />
  <small><a href="https://lco.global/news/lco-scientists-use-supernovae-to-make-a-new-measurement-of-the-hubble-constant/">Image courtesy of BJ Fulton/LCO/PTF</a></small>
feature_row_HeStar1:
  - image_path: /assets/images/HeStarTRho.png
    alt: "placeholder image 1"
    title: "Evolution of Helium Star-White Dwarf Binaries Leading up to Thermonuclear Supernovae"
    excerpt: In this paper ([Wong & Schwab 2019](https://ui.adsabs.harvard.edu/abs/2019ApJ...878..100W/abstract)), we investigate the parameter space of white dwarfs stably accreting from non-degenerate, 1-2 solar-mass helium star companions. Previous studies assumed that if the accreting white dwarf reaches Chandrasekhar mass, it will undergo core carbon ignition. We account for the possibility that an **off-center carbon ignition** could occur and convert the white dwarf into an **oxygen-neon white dwarf**. It could then undergo accretion-induced collapse and form a neutron star when reaching Chandrasekhar mass. 
feature_row_HeStar2:
  - image_path: /assets/images/HeStarHRD.png
    alt: "placeholder image 1"
    title: "Pre-explosion Properties of Helium Star Donors to Thermonuclear Supernovae"
    excerpt: In this followup paper ([Wong, Schwab & Götberg 2021](https://ui.adsabs.harvard.edu/abs/2021ApJ...922..241W/abstract)), we predicted the **observable properties** of helium star-white dwarf binary systems leading to Chandrasekhar-mass explosions. This is particularly relevant for **type Iax supernovae**, a class of thermonuclear transients that are subluminous and have slower ejecta velocities compared to normal type Ia supernova. Two Iax supernovae have helium emission lines in early spectra, and SN 2012Z had a pre-explosion detection consistent with a helium star progenitor.
feature_row_HeWD:
  - image_path: /assets/images/HeFlash_vorb.png
    alt: "placeholder image 1"
    title: "Dynamical He Flashes in Double White Dwarf Binaries"
    excerpt: In this paper ([Wong & Bildsten 2023](https://ui.adsabs.harvard.edu/abs/2023ApJ...951...28W/abstract)), we investigate the occurrence of double-detonations in double white dwarf binaries with a helium white dwarf donor. Unlike previous studies, we account for the impact of the cooling time of the helium white dwarf donor on the mass transfer rate. Our study sheds light on how AM CVn binaries could lead to type Ia supernovae, and our models reasonably explain the hypervelocity star D6-2.
feature_row_TDC:
  - image_path: /assets/images/MESA_TDC.png
    alt: "placeholder image 1"
    title: "Modules for Experiments in Stellar Astrophysics (MESA): Time-dependent Convection, Energy Conservation, Automatic Differentiation, and Infrastructure"
    excerpt: I was involved with the MESA VI instrument paper ([Jermyn et. al. 2023](https://ui.adsabs.harvard.edu/abs/2023ApJS..265...15J/abstract)), where we presented the new time-dependent convection capability. This is particularly important for dynamical nuclear burning where the heating timescale may become comparable or less than the convective eddy turnover timescale. We demonstrated this new capability using dynamical helium flashes on white dwarfs. 
---

## Helium White Dwarf Companions (sub-Chandrasekhar Mass Scenario)

One popular sub-Chandrasekhar mass scenario is the double-detonation mechanism, where a surface helium shell detonation leads to core carbon detonation. 

{% include feature_row id="feature_row_HeWD" type="left" %}

{% include feature_row id="feature_row_TDC" type="right" %}

## Helium Star Companions (Chandrasekhar Mass Scenario)

In the Chandrasekhar mass scenario, a carbon-oxygen white dwarf accretes material from a non-degenerate companion star and explodes via core carbon ignition when it reaches the Chandrasekhar mass. 

{% include feature_row id="feature_row_HeStar1" type="left" %}

{% include feature_row id="feature_row_HeStar2" type="right" %}




