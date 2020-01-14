This is an example program to process digitised logbook data from Jamestown (1886) into IMMA records, using the lmrlib.py 
subroutine.

 Specifically for the Jamestown_1886 transcribed logbook:
 There are two input files used, one for the position of the ship and the other for the observations

 The format of the positions file is 7 columns of tab separated fields

 DD/MM/YYYY         Log lat        Log Long            Estimated Lat   Estimated Lon                Corrected Lat                Corrected Long
 12/03/1886         15 22 N         61 42 W              NA              NA                             NA                              NA

     * columns 2 and 3 the lat/lon are in degrees and minutes with additional character indicating North/South East/West
     * otherwise in degrees North and degrees East
     * all positions are assumed to be at 12noon local time
     * assumes no significant gaps in time for the positions

 The format of the observations file is 6 columns of tab separated fields

 DD/MM/YYYY      HR   air_temp  sfc_temp baro_temp Pressure Hg
 13/03/1886       3      78      78        81       30.03

     * All temperatures are in degrees Fahrenheit
     * Pressure are in inches Hg

  We have assumed that the ships logs have already adjusted their local time when crossing the international dateline.
