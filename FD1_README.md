FHa data was obtained from “Spectroscopy and abundances of SINGS galaxies” (Moustakas et al, 2010).
Distance (Mpc) and logFUV data was obtained from “GALEX ultraviolet atlas of nearby galaxies” (Gil de Paz et al, 2007).
SFR calibrations originate from “Star Formation in Galaxies Along the Hubble Sequence” (Kennicutt et al 1998).
Galaxies included in both datasets were used.


SFR from Ha was obtained from converting the flux into luminosity, and then inputting it into the SFR calibration 7.9e-42 * L_Ha (erg/s)

I will be honest, I do not 100% understand the motivation behind this SFR calibration. It was suggested by AI. SFR from FUV was obtained from converting the logarithmic value into power, and then using the SFR calibration 3.3e-44 * L_FUV (erg/s). Kennicutt et al’s calibration is 1.4e-28 * L_FUV (erg/s/Hz), but because the FUV data is “band-integrated luminosity”, the coefficient 1.4e-28 was divided by GALEX’s bandwidth.


“Data First Draft - Spiral.csv” contains the data analysis for spiral galaxies. 
“Data First Draft - Elliptical_Lenticular.csv: contains the data analysis for elliptical and lenticular galaxies.
Their appearances are very distinct, so I believe I didn’t miscategorize them.


Opinion
The data looks extremely off, especially for the spiral galaxies. The SFR values obtained by Ha and FUV were sometimes hundreds of orders of magnitudes apart, which I think isn’t supposed to happen. I feel as though this is something that will need to be accounted for in the final draft.
Errors for FHa were included in the dataset, but I was too caught up in the SFR discrepancy to include them in my data analysis.
