# SCOR_WG142_O2_conversions
This is a github copy of the Matlab code supplement to: 

SCOR WG 142 Recommendations on the conversion between oxygen quantities for Bio-Argo floats and other autonomous sensor platforms. Bittig, H., A. Körtzinger, K. Johnson, H. Claustre, S. Emerson, K. Fennel, H. Garcia, D. Gilbert, N. Gruber, D.-J. Kang, W. Naqvi, S. Prakash, S. Riser, V. Thierry, B. Tilbrook, H. Uchida, O. Ulloa, and X. Xing 
(2016) https://dx.doi.org/10.13155/45915

Note that O2 concentration is used per volume of solution, i.e., µmol L-1. If O2 concentration is desired / supplied per mass of solution, i.e., µmol kg-1 (standard unit for GO-SHIP or Biogeochemical-Argo), it needs to be converted by dividing / multiplying with the seawater density (kg L-1), e.g., calculated using the seawater toolbox. For seawater, the difference between µmol L-1 and µmol kg-1 is about 2-3 % and not negligible.
