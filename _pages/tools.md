---
layout: basic
title: Tools
permalink: /tools/
---

The following open-source software are freely available for all. These are precious tools for any ATM researcher.

---

## BlueSky, an open air traffic simulator

BlueSky is an open air traffic simulator provided for anybody who wants to visualize, analyze or simulate air traffic. It is commonly used to perform research on Air Traffic Management and Air Traffic Flows.

<https://github.com/TUDelft-CNS-ATM/bluesky>  
GNU General Public License v3.0  

---

## OpenAP, Open Aircraft Performance Model and Toolkit

<img src="https://img.shields.io/badge/isbn-978 94 6384 030 9-brightgreen"/>

This repository contains all OpenAP databases and a Python implementation which facilitates data access and performance computation. It includes the following key modules:

- `openap.prop`: a module for accessing aircraft and engine properties
- `openap.thrust`: a module for computing aircraft thrust
- `openap.drag`: a module for computing aircraft drag
- `openap.fuel`: a module for computing fuel consumption
- `openap.kinematic`: a utility library to access WRAP data
- `openap.traj`: a module contains a set of tools related with trajectory generation


<https://github.com/junzis/openap>  
GNU General Public License v3.0

---

## pyModeS, a decoder for ADS-B and Mode-S downlink messages

<img src="https://img.shields.io/badge/doi-10.1109/TITS.2019.2914770-brightgreen"/>

pyModeS is a Python library designed to decode Mode-S (including ADS-B) messages. 
It can be imported to your python project to decode Mode S messages, or used as a standalone tool to view and save live traffic data.

<https://github.com/junzis/pyModeS>  
<http://pymodes.readthedocs.io>  
GNU General Public License v3.0

---

## pyopensky, the Python interface for OpenSky Impala database with integrated pyModeS decoder

<img src="https://img.shields.io/badge/doi-10.29007/mmsb-brightgreen"/>


This Python library connects the pyModeS decoder and OpenSky Impala data interface.
It aims at making the Enhance Mode-S information from OpenSky network more accessible for researchers.
It can be used for:

- Query and download ADS-B state vectors and raw Mode S messages from OpenSky Impala database.
- Decode OpenSky Comm-B information automatically using pyModeS.

<https://github.com/junzis/pyopensky>  
GNU General Public License v3.0


---

## traffic, a toolbox for processing and analysing air traffic data

<img src="https://img.shields.io/badge/doi-10.21105/joss.01518-brightgreen"/>

The traffic library helps working with common sources of air traffic data.

Its main purpose is to offer basic cumbersome data analysis methods commonly applied to trajectories and ATC sectors. When a specific function is not provided, the access to the underlying structure is direct, through an attribute pointing to a pandas dataframe.

The library also offers facilities to parse and/or access traffic data from open sources of ADS-B traffic like the OpenSky Network or Eurocontrol DDR files. It is designed to be easily extendable to other sources of data.

Static visualisation (images) exports are accessible via Matplotlib/Cartopy. More dynamic visualisation frameworks are easily accessible in Jupyter environments with ipyleaflet and altair; or through exports to other formats, including CesiumJS or Google Earth.

Xavier Olive,  
"traffic, a toolbox for processing and analysing air traffic data",  
*Journal of Open Source Software*, 2019  

<https://github.com/xoolive/traffic>  
<https://traffic-viz.github.io/>  
MIT License

---

## openSkies, an R package for aviation data retrieval, analysis and visualization

openSkies aims to provide the data structures and functionalities required to analyze and visualize aviation data in R. 

The package provides a system of classes with associated methods representing the most common entities related to aviation data, such as aircrafts, airports, flights or routes.

It also includes a client interface to the OpenSky live API, and a decoder of ADSB messages.

Finally, functions to process and plot aircraft and flight data are also provided.

A full, detailed list of the available features can be found in the manual and the vignette of the package.

<https://CRAN.R-project.org/package=openSkies>
<https://github.com/Rafael-Ayala/openSkies>
CC BY-NC 4.0 License
