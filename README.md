# Quasar-Diameter-Beaming
i Calculation of the diameter of a Quasar using the formulation of realtivistic beaming effect.

The Lightcurve data file of the Quasar is obtained from the MAST Archival repository in the form of a processed FITS file of a lightcurve. 
Then I carry out the following steps with the FITS file:
1. The FITS file is converted into a readable CSV file using the Pandas Dataframes and the ascii package from AstroPy.
2. Then the CSV file is plotted with the lightkurve library in Python. 
3. The light curve's time period is taken by the averaging the time period of individual waves and the overall average over a short region. 
4. The data is taken and put into the theoretical formula derived in the paper uploaded as a pdf (report_pdf.pdf)). 
5. Diameter of the Quasar is found (both non-relativistically and relativistically)! 

 have uplaoded the CSV file as well as the FITS file (if someone wantes to start from the scratch of the 3C 273 Quasar from the Kepler 2 mission.)

Comments are appreciated. More appreciated if they can be used to expand the project further. Thanks!

