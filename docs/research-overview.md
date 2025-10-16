# Research Overview

## 1. Background
The Ishihara test was first introduced by Shinobu Ishihara in 1917.  
Its pseudoisochromatic plates use precise chromatic differences (ΔE) between figure and background to detect red–green color vision deficiencies.

## 2. Modern Digital Implementation
Digital methods replicate these colorimetric relationships using CIE LAB, LMS cone response models, and calibrated color difference metrics (ΔE\*ab).

Our generator applies:
- Controlled color contrast within 14 ± 3 ΔE range  
- Uniform distribution of randomized circular dots  
- Figure/background chromatic masking  
- LMS cone projection for protan and deutan simulation

## 3. Validation
Simulated observers (Protanopia/Deuteranopia) confirm visibility thresholds consistent with Ishihara 1917 and CIE 015:2018 standards.

## 4. References
See [`docs/references.md`](references.md)
