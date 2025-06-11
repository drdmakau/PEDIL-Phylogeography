# PEDIL-Phylogeography

This repository contains BEAST XML configuration files and related resources used for phylogeographic analyses of transboundary and endemic diseases, maintained by the **Population & Epidemiology Data Innovation Lab (PEDIL)**.

Our goal is to promote transparency, reproducibility, and regional collaboration in molecular epidemiology and spatial phylodynamics, with a focus on high-priority animal and zoonotic pathogens.

---

## Current Project

### Foot-and-Mouth Disease Virus (FMDV) in East and Horn of Africa

**Manuscript title:**  
*Tracing the Spread and Phylogeography of Foot-and-Mouth Disease Virus across East and the Horn of Africa*  
**Running title:** *Phylogeography of FMDV in Eastern Africa*

**Authors:**  
Dennis N. Makau (UTK, UMN), Jonathan Arzt (USDA-ARS), Kimberly VanderWaal (UMN)
Correspondence: dmakau@utk.edu

**Abstract:**  
Foot-and-mouth disease (FMD), a highly contagious viral infection affecting cloven-hoofed animals, has significant implications for global livestock production and trade. In this study we aimed to characterize and describe dispersal patterns and factors affecting pool 4 serotypes of FMD viruses (FMDV) in the East and Horn of Africa. The study area included 12 countries; 1,423 VP1 sequence data were used (serotypes A, O, SAT1, SAT2) obtained from NCBI GenBank. Using continuous and discrete space phylogeographic models in BEAST, we assessed viral dispersal, population dynamics, direction and velocity modeled against environmental, human and livestock demographic and trade data. We identified distinct viral clusters with Kenya and Sudan as major sources for intercountry spread. Our results underscore the importance of data-driven regional collaboration for outbreak prediction and control.

---

## Repository Structure
```
/FMDV-EastHornAfrica/
├── serotype_A/
├── serotype_O/
├── serotype_SAT1/
├── serotype_SAT2/
/[Other Pathogen - Region]/
/README.md
```


---

Each folder contains:
- XML configuration files used in BEAST v1.10.4
- Description of the model (GTR+Γ, relaxed clock, Skygrid coalescent)
- Notes on spatial trait setup (discrete/continuous)
- Optional metadata: sequence source, raster layers, and BEAUti templates

---

## Software Versions

- BEAST v1.10.4  
- BEAUti (part of BEAST package)  
- Tracer v1.7+  
- TreeAnnotator, SpreaD3, and R for post-processing

---

## How to Use

1. Open XML files using BEAST or BEAUti
2. Run BEAST with MCMC settings specified in the XML
3. Visualize outputs with Tracer, TreeAnnotator, SpreaD3, or your preferred tools

---

## Citation

If you use this repository or its contents, please cite the relevant publication (DOI to be added upon acceptance) and acknowledge the PEDIL GitHub repository:

> Makau DN, Arzt J, VanderWaal K. Tracing the Spread and Phylogeography of Foot-and-Mouth Disease Virus across East and the Horn of Africa. *[Journal, Year]*. DOI: [TBA]  
> GitHub: https://github.com/drdmakau/PEDIL-Phylogeography

---

## About PEDIL

The **Population & Epidemiology Data Innovation Lab (PEDIL)**, based at the University of Tennessee, Knoxville, advances population health and biosecurity through data-driven research in infectious disease epidemiology, zoonoses, and public health surveillance.

---

## Archive Notice

A version of this repository will be archived with a DOI on [Zenodo](https://zenodo.org/) upon manuscript publication.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).  
Attribution is encouraged: If you use or adapt these materials, please credit the **Population and Epidemiology Data Innovation Lab (PEDIL), University of Tennessee**.

