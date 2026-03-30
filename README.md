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

## Theoretical Foundation

This tool implements a differential sensitivity framework for unobserved confounding (Hait, in preparation), which reconceptualizes robustness as a local geometric property of the confounding path. The framework extends classical threshold-based approaches (e.g., ITCV, E-values) by introducing local sensitivity slopes, curvature, and cumulative fragility as core diagnostics.

## Relation to confoundvis
This interactive system complements the `confoundvis` R package by providing a visualization layer for sensitivity geometry and fragility analysis.

## Repository
This repository contains the source code for the live interactive explorer.

##  Citation
cff-version: 1.2.0
title: "confoundvis-explorer: Interactive Sensitivity Geometry"
message: "If you use this software, please cite it."
type: software
authors:
  - family-names: Hait
    given-names: Subir
    orcid: "https://orcid.org/0009-0004-9871-9677"
repository-code: "https://github.com/causalfragility-lab/confoundvis-explorer"
url: "https://causalfragility-lab.github.io/confoundvis-explorer/"
doi: "10.5281/zenodo.19337307"
version: "0.1.0"
date-released: "2026-03-30"
license: "MIT"
