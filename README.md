GatherWxStnData_POR downloads all data from the old and new ststions. It saves them in gzipped pkl files:
<troll | trollOld | taf | tafOld>_<start-year-month>_<end-year-month>.pkl.gz

QC_gatheredData removes some data with obvious problems. The resultats are saved in:
<troll | trollOld | taf>_<startYear>_<endYear>_QC.pkl.gz
I haven't tried to QC the old data from the airport.

QC’d data are showen in ClimatePlots.
