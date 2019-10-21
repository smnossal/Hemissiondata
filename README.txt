We have included data in this repository that were used in the following jgr pubication:

"Geocoronal Hydrogen Emission Variation Over Two Solar Cycles" [Paper #2019JA026903R]

When using the data we recommend contacting Susan Nossal (nossal@physics.wisc.edu) to discuss analysis approach and to address 
quesitons.

In figures 3a, 3b and 6, we plotted the geocoronal hydrogen Balmer-alpha intensity versus the shadow altitude of the observations.  In fgure 4, data are binned and plotted at a mid-range shadow altitude.  The methodology for doing so is described in the publication.  The data files are in mulitple formats and we indicate below which columns correspond to the shadow altitude and the Balmer-alpha column emission intensity.  These intensities are corrected for atmospheric extinction, but not for tropospheric scattering.

Wisconsin H-alpha Mapper Fabry-Perot observations from Kitt Peak, AZ:

whamint_1997presort.dat    column 1 - shadow altitude; column 2 - intensity
whamint_2000_presort.dat   column 1 - shadow altitude; column 2 - intensity
whamint_2001presort.dat    column 1 - shadow altitude; column 2 - intensity
whamint_2004presort.dat    column 1 - shadow altitude; column 2 - intensity
whamint_2006presort.dat    last column - shadow altitude; first column - intenstiy
whamint_2008presort.dat    last column - shadow altitude; second column - intensity

Fabry-Perot observations from Pine Bluff, WI - 2000

ns_out_02-02-00_midpt.pltdat   column 1 - shadow altitude; column 2 - intensity


Refit spectra from winter 1990 and 1991:

rfspjan272890.dat
rfspfeb1291.dat 
rfspjan2191.dat

In these three files, the last column is the shadow altitude.
The second to last column is the area of the fit.

An example calculation for the intensities is as follows.  The first factor is the correction 
for atmospheric extinction and the second is the calibration for R8 = 130R, R8 = 153 R; and NANN = 850R

INTRSR8130jan2191 = A(11, *) * 1.15027 * 0.002516
INTRSR8153jan2191 = A(11, *) * 1.15027 * 0.002939 
INTRSNANjan2191 = A(11, *) * 1.15027 * 0.002540

Pre-WHAM data from the 1970s and 1980s:

LGBASELINE1.DAT

The second column is the local date, the third column is the local time, the fourth is the zenith angle of the observations,
the sixth is the solar depression angle and the seventh is the Balmer-alpha column emission intensity.  This intensity has not 
been corrected for tropospheric scattering.
