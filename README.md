FHa data was obtained from “Spectroscopy and abundances of SINGS galaxies” (Moustakas et al 2010).
Distance (Mpc) and logFUV data was obtained from “GALEX ultraviolet atlas of nearby galaxies” (Gil de Paz et al 2007).
SFR calibrations originate from “Star Formation in Galaxies Along the Hubble Sequence” (Kennicutt et al 1998).
Galaxies included in both datasets were used for this data analysis.


SFR from Ha was obtained from converting the flux into luminosity, and then inputting it into the SFR calibration 7.9e-42 * L_Ha (erg/s). The emission lines are corrected for dust reddening using the observed Balmer decrement.

SFR from FUV was obtained from converting the logarithmic value into power, and then using the SFR calibration 3.3e-44 * L_FUV (erg/s). Kennicutt et al’s calibration is 1.4e-28 * L_FUV (erg/s/Hz), but because the FUV data is “band-integrated luminosity”, the coefficient 1.4e-28 was divided by GALEX’s bandwidth.

The UV color proxy was simply calculated using logFUV - logNUV, which is equal to log(FUV/NUV). The data was corrected for dust attenuation by the Milky Way galaxy.

The error for the Ha flux and distances to the galaxies was given in the dataset. The error for FUV was calculated from the magnitude of the UV emission and converted into logFUV (which was the data used to calculate SFR). The errors were propagated by differentiating each formula by the inputs, squared, multiplied by the error of the input squared, summed, and square rooted.

Some galaxies are missing Ha measurements for certain regions. This is because the Ha flux could not be measured with certainty.

