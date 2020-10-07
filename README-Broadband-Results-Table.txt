The 2BIGB catalog (arxiv:xxxxxx)

Here we have a description for the columns in table "2BIGB-3HSP-Broadband-500MeV-500GeV-11yrs.txt" (.ascii format).

Column 1 "2BIGB_name(J2000)": The source name in 2BIGB calalog, based in names from 3HSP sources (see https://arxiv.org/abs/1909.08279).

Columns 2 and 3 with "R.A." and "Dec" are the Right Ascension and Declination given in degrees (J2000).  These are the multifrequency seed positions corresponding to 3HSP sources.

=================

Next columns, from 4 to 10, are the outputs from Fermi Science Tools when fitting the gamma-ray signature with a power-law. Columns 11 and 12 are parameters related to the analysis setup.  

Columns 4 and 5 with "N0(E-13)_2bigb" and "N0_err(E-13)_2bigb": These corresponds to the Normalization parameter and its uncertainty, in units of [photons/cm^2/s/MeV]. It is the actual flux density calculated at the pivot energy "E0".

Columns 5 and 7 with "Gamma_2bigb" and "Gamma_err_2bigb": These corresponds to the Photon Spectral Slope and its uncertainty at the pivot energy "E0".

Columns 8 and 9 with "Flux(0.5-500GeV)_2bigb" and "Flux_err(0.5-500GeV)_2bigb": These corresponds to the integrated photon flux and its uncertainty along the 500 MeV to 500 GeV energy band. 

Column 10 with "TS_2bigb": This is the Test Statistic parameter, showing the statistical strength of the gamma-ray signature compared to the local background.

Column 11 with "4FGLv20_name": This is the 4FGL_J name according to the catalog version gll-psc-v20. Whenever a 3HSP is within the 4FGL 95% containment region, they are considered associated. In this case, the 4FGL source is erased from the analysis, and replaced by a new source, center at 3HSP position. Therefore, the 4FGL fitting parameters are all updated, not only considering 11 years of data but also assuming a better position for the gamma-ray source.

Column 12 with "PivotEnergy_2BIGB": This is the pivot energy "E0" in [MeV] used as reference energy at which both the Normalization and Photon Spectral Slope are estimated during the analysis. The pivot energy is optimized to reduce uncertainties associated with Normalization and Photon Spectral Slope. For 3HSP sources having a 4FGL counterpart, E0 is read from 4FGL gll-psc-v20. In case the source is new concerning 4FGL, we have scanned over E0 (for the following energies: 1000, 3000, 5000, and 10000 MeV) and select the one which leads to the lowest uncertainties.  

=================

Next columns, from 13 to 21, we list parameters from the 3HSP catalog (see https://arxiv.org/abs/1909.08279) 

Column 13 with "5BZcat": This is the source name according to 5BZ Catalog (see https://arxiv.org/abs/1502.07755), meaning the source is a confirmed blazar, with optical identification. Nevertheless, the 3HSP catalog lists plenty of sources beyond 5BZcat, which have optical identification and are newly confirmed blazars. 

Column 14 with "sflag_3HSP": This is a quality flag for the overall SED from 3HSP sources. This flag goes from 1 to 4. From 3HSP paper: "Some of the 3HSPs sources have sparse non-thermal data, poor quality data, or somewhat peculiar flux ratios. These sources need a careful follow-up in future versions of the HSP catalog. 
These objects were assigned a flag value that reflects the reason for the uncertainty. 
For sources with only a few non-thermal data or with fairly large X-ray positional error, we gave a flag value of 1. Flag 2 is for cases with one or two doubtful data points (due to large positional uncertainty or problematic photometry) but still providing a reasonable HSP-like SED. Sources with a low ratio between synchrotron peak flux and radio flux (possibly due to jet misalignment) were given source flag 3. Source flag 4 is for cases where the observed IR or optical emission cannot be safely attributed to the host galaxy or synchrotron emission." Cases signed with flag 0 have relatively good multifrequency coverage. 

Column 15, 16 and 17 with "log(nu)_3HSP[Hz]" "log(nufnu)_3HSP[erg/cm2/s]" "nuflag_3HSP": These are the parameters associated to the Synchrotron Peak, as listed in 3HSP catalog. Respectively they represent the log of the peak frequency (in Hz), the log of flux (in erg/cm^2/s), and a quality flag. (1) for robust estimate, (2) for uncertain value, (3) for lower limit value.   


Column 18 and 19 with "z_3HSP" and "zflag_3HSP": These are the redshift and redshift-flag according to 3HSP paper. Considering the entire 3HSP sample (with all its 2013 sources), the flags break down to the 31.8% of 3HSPs with firm redshift (flag 1); The 5.3% of 3HSPs with uncertain redshift (flag 2); The 4.7% of 3HSPs with lower limit redshift (flag 3); The 7.2% of 3HSPs with photometric redshift and featureless optical spectrum (flag 4); The 39.0% of 3HSPs with photometric redshift and without optical spectrum (flag 5); The 11.9% of 3HSPs without any redshift estimation or measurements.    


Column 20 with "FOM_3HSP": This is the figure of merit parameter, which is related to the likelihood of GeV/TeV detectability. 

Column 21 with "WHSPnames": This is the name of the corresponding 3HSP source in previous 1WHSP (arxiv:1504.02801) and 2WHSP (arxiv:1609.05808) catalogs. 


================

Next columns, from 22 to 30, are read from 4FGL catalog, version gll-psc-v20 (4FGLv20). 

Columns 22, 23 and 24 with "4FGL_Name_v20" "R.A.4FGL_v20" and "Dec_4FGL_v20": These are the names, R.A. and Declination (in degrees) associated to the 4FGL sources. 

Column 25 with "Signif_4FGL_v20": This is the significance of the detection in 4FGL_v20 (can be approximated to the square root of the TS value).

Column 26 with "Pivot_Energy_4FGL_v20": This is the pivot energy (in MeV) as listed in 4FGLv20. 

Column 27 and 28 with "N0_4FGL_v20" and "N0_err_4FGL_20": This is the Normalization parameter and its uncertainty (in photon/cm^2/s/MeV). 

Columns 29 and 30 with "PL_Index_4FGL_v20" and "PL_Index_err_4FGL_v20": This is the Photon Spectral Index and its uncertainty according to 4FGLv20. 

================

Columns 30 and 31 with "GAL_LONG" and "GAL_LAT" are respectively the galactic longitude and latitude (in degrees).   
