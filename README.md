# AI-ML-Assisted-Statistical-Spatio-Temporal-Prospectivity-Modelling-for-Critical-Minerals-Hackathon
(Project Team Members: (1) * Dr Debashis Chatterjee (Assistant Professor, Department of Statistics, Visva Bharati University),  **Team Correspondence
                       (2)   Mr. Sumit Kumar (Geological Survey of India, Kolkata Center)
                       (3)  Dr Amlan Banerjee, Geological Studies Unit, Indian Statistical Institute

Description: 
AI/ML-Assisted Statistical Spatio–Temporal Prospectivity Modelling for Critical Minerals with Application to Karnataka &amp; Andhra Pradesh Zone Hackathon 2025 Proposal

This document outlines a two-part approach for discovering concealed and deep-seated ore bodies in a 39,000 km$^2$ corridor across Karnataka and Andhra Pradesh, India, focusing on REE, Ni–PGE, Cu, and associated commodities.

Part 1: Describes a computationally efficient and statistically robust pipeline.

Data Integration: Converts multi-layer 1:25,000 geological vector data from the Geological Survey of India (GSI) into a unified voxel data cube. This is further enriched with satellite-derived spectral indices and public aeromagnetic grids.
Prospectivity Estimation (Two-Stage):
Stage 1: Uses a log-Gaussian Cox process to establish a smooth Bayesian baseline, accounting for spatial clustering and depth.
Stage 2: Employs a stacked ensemble of gradient-boosted trees, random forests, and a graph neural network to refine local details and determine covariate importance.
Validation: Achieves an AUROC of 0.86 through block cross-validation in 10 km folds, successfully identifying previously unknown targets beneath metasedimentary cover.
Implementation: The entire workflow is scripted in Python, from data ingestion to map production, ensuring transparency and re-execution for the IndiaAI Hackathon evaluation.
Part 2: Proposes an uncertainty-aware, dual-track workflow.

Methodology: Combines Bayesian geostatistics with deep 3-D convolutional and graph neural networks (CNN–GNN) for mineral prospectivity modeling.
Data Enhancement: Incorporates newly released GSI multi-parametric layers and a four-method radiometric geochronology map (K–Ar, Rb–Sr, Sm–Nd, U–Pb).
Outputs: Generates predictive probability volumes for a wider range of minerals including REE, Ni–PGE, Cu, Fe, Au, diamond, and Mn, explicitly modeling the depth of concealed ore bodies.
Deliverables: The primary deliverables for the IndiaAI × GSI Hackathon 2025 will be a reproducible, Dockerized codebase and an interactive Web-GL atlas.
