# os_intra-annual
DataSet for manuscript "Decomposing the intra-annual variability of flushing characteristics in a tidal bay along the North Sea"
Authors: Long Jiang, Karline Soetaert, Theo Gerkema

This respository includes data of 30 model scenarios used in the manuscript . Due to the file size limit, we have splitted data each scenario into several sub-files, which should be merged upon usage. Each file name is named "scenario name"+".7z."+"subfile number". For example, "STA10.7z.011" means the 11th file of the scenario STA10. The scenario names and other details could be found in Table 1 of the manuscript (see below). The model setup is available on request. The contact person is Long Jiang long.jiang@nioz.nl.

The master branch contains the scenario G1. Other scenarios are placed in 29 branches named after the scenario names. 

Run name	Startup time	Initial basin volume (km3)	Startup Temperature / Salinity	Tides	Winds	Density calculation
Realistic intra-annual runs
R1	1 Jan. 0:00	2.68	Realistic	Realistic	Realistic	Baroclinic
R4	1 Apr. 0:00	2.48	Realistic	Realistic	Realistic	Baroclinic
R7	1 Jul. 0:00	2.88	Realistic	Realistic	Realistic	Baroclinic
R10	1 Oct. 0:00	3.15	Realistic	Realistic	Realistic	Baroclinic
Sensitivity runs of the startup tidal phase
STP1	1 Jan. 06:00	3.37	No	Realistic	No	Barotropic
STP2	1 Jan. 09:00	2.82	No	Realistic	No	Barotropic
STP3	1 Jan. 12:00	2.39	No	Realistic	No	Barotropic
STP4	1 Jan. 15:00	2.59	No	Realistic	No	Barotropic
STP5	1 Jan. 18:00	3.29	No	Realistic	No	Barotropic
Sensitivity runs of the startup tidal amplitude
STA4	1 Jan. 09:00	2.82	No	Realistic starting on 1 Apr.	No	Barotropic
STA7	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jul.	No	Barotropic
STA10	1 Jan. 09:00	2.82	No	Realistic starting on 1 Oct.	No	Barotropic
STAsp	1 Jan. 09:00	2.82	No	Realistic starting on 13 Jan.	No	Barotropic
STAne	1 Jan. 09:00	2.82	No	Realistic starting on 20 Jan.	No	Barotropic
Sensitivity runs of winds
W1	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Realistic	Barotropic
W4	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Realistic starting on 1 Apr.	Barotropic
W7	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Realistic starting on 1 Jul.	Barotropic
W10	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Realistic starting on 1 Oct.	Barotropic
Wsw5	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Southwesterly 5 m/s	Barotropic
Wsw10	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Southwesterly 10 m/s	Barotropic
Wsw15	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Southwesterly 15 m/s	Barotropic
Wne10	1 Jan. 09:00	2.82	No	Realistic starting on 1 Jan.	Northeasterly 10 m/s	Barotropic
Sensitivity runs of gravitational flow
G1	1 Jan. 09:00	2.82	Realistic	Realistic starting on 1 Jan.	No	Baroclinic
G4	1 Jan. 09:00	2.82	Realistic starting on 1 Apr.	Realistic starting on 1 Jan.	No	Baroclinic
G7	1 Jan. 09:00	2.82	Realistic starting on 1 Jul.	Realistic starting on 1 Jan.	No	Baroclinic
G10	1 Jan. 09:00	2.82	Realistic starting on 1 Oct.	Realistic starting on 1 Jan.	No	Baroclinic
GF1h	1 Jan. 09:00	2.82	25 Feb. “fixed”	Realistic starting on 1 Jan.	No	Baroclinic
GF2h	1 Jan. 09:00	2.82	26 Aug. “fixed”	Realistic starting on 1 Jan.	No	Baroclinic
GF3h	1 Jan. 09:00	2.82	21 Sep. “fixed”	Realistic starting on 1 Jan.	No	Baroclinic
GF4h	1 Jan. 09:00	2.82	21 Dec. “fixed”	Realistic starting on 1 Jan.	No	Baroclinic
