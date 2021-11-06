---
title: "Pre-Amplifier"
excerpt: "This is a repository of general-purpose low-noise amplifiers"
permalink: /MIT-MGH_Preamp/
layout: single
header:
  teaser: /assets/images/Projects/Preamp/ModPreamp_render.png
sidebar:
  - title: "Low-Noise Preamplifier"
    image: /assets/images/Projects/Preamp/ModPreamp_render.png

  - title: "Specifications"
    text: "<1nV/sqrt(Hz)"
  - title: "Funding"
    text: "This project was made possible by the following grant numbers: NIBIB U01EB025121 NIMH R24106053 and NSF GRFP 1122374"
  - title: "License"
    text: "MIT"

    
gallery:
  - url: /assets/images/Projects/Preamp/ModPreamp_render.png
    image_path: /assets/images/Projects/Preamp/ModPreamp_render.png
    alt: "Rendering of the modular preamp"
  - url: /assets/images/Projects/Preamp/Par_Inputs.png
    image_path: /assets/images/Projects/Preamp/Par_Inputs.png
    alt: "The front-end board"
  - url: /assets/images/Projects/Preamp/Par_Inputs_Shield.png
    image_path: /assets/images/Projects/Preamp/Par_Inputs_Shield.png
    alt: "The optional shield to go over the front-end"
  - url: /assets/images/Projects/Preamp/INA_Preamp.png
    image_path: /assets/images/Projects/Preamp/INA_Preamp.png
    alt: "Rendering of the INA-based preamp"
---

This project is meant to provide access to a high-quality low-noise preamplifier to those who may not have the resources to design one in-house. It was designed for magnetic particle imaging applications, but it can be modified for most applications that require signal processing in the range of ~20kHz-500kHz.

There a few preamps included, one of which is the "Modular preamp" and the goal is to be easily modified without needing to design a new board each time. It also has the ability to be easily shielded with header pins. That way different sections of the amplifier cannot easily interfere with eachother. 

The other main preamp is the INA-based preamp. That one is much more self-contained and has means for a filter to be place on the board-- it was designed to be an AC-coupled notch filter, but that could be simply modified. 
 
# [Link to Files](https://github.com/OS-MPI/MPI_Preamp)
# [Link to Wiki](https://github.com/OS-MPI/MPI_Preamp/wiki)

{% include gallery caption="This is a set of representative rendering and images of the system" %}








