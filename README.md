# Increasing Proteomic Depth of Single-Cell Analysis by Enhanced Feature Matching
This repository contains processed files, including protein and peptide tables, of searches conducted in the DIA-ME preprint (biorxiv.org/)
Proteomic data has been acquired on a timsTOF Pro and Fusion Orbitrap instrument. The resulting raw data sets can be found on PRIDE with the following extension numbers: ... .

# Project description
In the work, we present and evaluate the DIA-ME workflow for the proteomic analysis of scarce samples down to single cells. 
DIA-ME facilitates matching of peptide identifications from MEs (matching enhancer) to low-input samples to increase their proteomic depth and data completeness.

We first ensured that extensive feature matching using MBR (match-between-runs) does not result in elevated FDR (false-discovery rate) by misassigning peptides to wrong signals.
To this end, we conducted raw data searches of seven HeLa proteome replicates together with E.coli-spiked MEs of different injection amounts in DIA-NN and Spectronaut.

After having successfully verified the reliability of DIA-ME in DIA-NN, we applied the suggested approach to a time-course experiment, in which we treated human osteosarcoma cells (U-2 OS) with Interferon gamma (IFN-γ).
We compared biological findings of injection amounts as little as 200 pg (timsTOF) to a conventional bulk proteome analysis using 200 ng (Fusion Orbitrap) to investigate whether DIA-ME helps closing the gap between the results of these measurements. 

Finally, we applied DIA-ME to a single-cell experiment, co-analyzing individual U-2 OS cells with instances of 10 cell samples and assessed the effect of IFN-γ treatment on this cell type. 
Assisted by the benefical application of DIA-ME, we made interesting observations from co-expressed proteins, opening exciting novel avenues for the investigation of single cells.

# Folder Structure
According to strcuture of this project, folders are arranged as follows: 
