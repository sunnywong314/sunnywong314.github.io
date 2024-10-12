---
permalink: /code/
title: "Code"
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/DSC_5244.jpg
excerpt: >
  <br />
  <br />
  <br />
  <br />
  <br />
feature_row_athena:
  - image_path: /assets/images/athena_logo_temporary.png
    alt: "placeholder image 1"
    title: "Athena++"
    excerpt: "
    <big>
    Over the past year I have been using the [Athena++](https://github.com/PrincetonUniversity/athena) magnetohydrodynamics code. I perform 3D hydrodynamical simulations of supernova ejecta interacting with companion stars. I have experience with the adapative mesh refinement, MPI parallelization, multigrid self-gravity, and passive scalar features. Most recently I have started using the general equation-of-state capability. I input the MESA equation of state into Athena++ to allow for the effects of electron degeneracy, radiation, and Coulomb interactions. 
    "
feature_row_mesa:
  - image_path: /assets/images/mesa_logo2_100pt.png
    alt: "placeholder image 1"
    title: "Modules for Experiments in Stellar Astrophysics (MESA)"
    excerpt: "
    <big>
    [MESA](https://docs.mesastar.org/) is an open-source 1D stellar evolution code. I have been a long-term MESA user since 2017. I mainly use the MESA binary module to model white dwarfs in a binary, and occasionally I use the equation of state module and the opacity module independently, as well as the GYRE pulsations code. I have been a teaching assistant at MESA summer schools [2018](https://cococubed.com/mesa_summer_schools/mesa_summer_school_2018/index.html), [2019](https://cococubed.com/mesa_summer_schools/mesa_summer_school_2019/index.html), [2021](https://cococubed.com/mesa_summer_schools/mesa_summer_school_2021/index.html),
[2022](https://mesastar.org/summer-school-2022/), and
[MESA@Konkoly 2023](https://mesastar.org/summer-school-2023/), where we design hands-on labs for participants to apply MESA to various stellar evolution problems. In 2024 I lectured for [MESA Down Under](https://maygpedersen.github.io/mesa-down-under-2024/) in Sydney, Australia. Our lab is about double white dwarf binaries, and you can find our materials [here](https://courtcraw.github.io/mesadu_wdbinaries/).
    "
---

{% include feature_row id="feature_row_athena" type="left" %}

{% include feature_row id="feature_row_mesa" type="right" %}












