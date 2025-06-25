# Whole-Brain Dynamics Across the Menstrual Cycle

**MATLAB implementation for whole-brain node-metastability (ignition) analysis across menstrual phases in healthy women**

This repository supports the research study:

> Avila‑Varela, D. S., Hidalgo‑Lopez, E., Dagnino, P. C., Acero‑Pousa, I., del Agua, E., Deco, G., Pletzer, B., & Escrichs, A. (2024).  
> *Whole‑brain dynamics across the menstrual cycle: the role of hormonal fluctuations and age in healthy women*.  
> *npj Women's Health*, 2, 8. https://doi.org/10.1038/s44294-024-00012-4

This study investigates how menstrual cycle phases (early follicular, pre-ovulatory, mid-luteal), hormone levels (estradiol, progesterone), and age impact whole-brain and resting-state network (RSN) node-metastability in a cohort of 60 healthy women.

---

## Purpose & Scope

- Quantify changes in whole-brain dynamical complexity using node-metastability metrics.
- Examine effects of hormonal fluctuations (estradiol, progesterone) and age via multilevel modelling.
- Characterize dynamics across large-scale RSN: DMN, somatomotor, control, dorsal attention, limbic, salience, subcortical, visual.
- Aid precision neuroscience studies within neuroendocrinology and women’s brain health.

---

## Repository Structure

- `Ignition_SingleSubject.m`: Core MATLAB script computing node-metastability (ignition) per subject.

> **Note:** For privacy, no empirical data is included—use your own preprocessed datasets.

---

## Requirements

- MATLAB R2018a or later
- Preprocessed resting-state fMRI scans (in time series format)
- Hormonal data and age for each subject

---

## Usage Guide

1. Clone this repository and open it in MATLAB.
2. Run `Ignition_SingleSubject.m`.

## Citation

If you use this code or reproduce the analyses, please cite:

Avila‑Varela, D. S., Hidalgo‑Lopez, E., Dagnino, P. C., Acero‑Pousa, I., del Agua, E., Deco, G., Pletzer, B., & Escrichs, A. (2024).  
*Whole‑brain dynamics across the menstrual cycle: the role of hormonal fluctuations and age in healthy women*.  
npj Women’s Health, 2, 8. https://doi.org/10.1038/s44294-024-00012-4

---

## License

This project is licensed under the MIT License.  
© 2024 Anira Escrichs

---

## Contact

For code usage and questions please contact:  
**Anira Escrichs**  
📧 anira.escrichs@upf.edu
CNS, Pompeu Fabra University



