This code uses astroquery for accessing catalogies on Gaia and Vizier.
A cone search of Gaia catalogues is included to isolate the eclipsing binaries in JWST's Continuous Viewing Zones (North and South CVZs).
The catalogues are manipulated using pandas.
The final list of 29 targets is then loaded into a MySQL database on my local machine. 