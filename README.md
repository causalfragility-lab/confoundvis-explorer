# confoundvis-explorer

Interactive visualization system for sensitivity analysis to unmeasured confounding. This tool explores ITCV, slope nullification, and “fragile mass” over nonlinear SES–time surfaces.

## Live App
https://causalfragility-lab.github.io/confoundvis-explorer/

## Overview
`confoundvis-explorer` provides an interactive environment for understanding how unmeasured confounding affects estimated relationships in nonlinear and multilevel settings.

The app moves beyond scalar sensitivity metrics by visualizing:
- Local gradients (∂f/∂SES)
- ITCV-based sensitivity thresholds
- Confound-induced slope attenuation and nullification
- Fragile regions across the SES–time surface
- Fragile mass: the proportion of the surface vulnerable to confounding

## Purpose
Traditional sensitivity analysis focuses on single-number summaries (e.g., ITCV, E-value).  
This tool introduces a **spatial and dynamic perspective**, showing where effects are fragile and how confounding propagates across the surface.

## Relation to confoundvis
This interactive system complements the `confoundvis` R package by providing a visualization layer for sensitivity geometry and fragility analysis.

## Repository
This repository contains the source code for the live interactive explorer.

##  Citation
If you use this tool, please cite the repository (see CITATION.cff).
