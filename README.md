GatherWxStnData_POR laster ned alle data fra de gamle og nye stasjonene. De er lagret i gzipped pkl files:
<troll | trollOld | taf | tafOld>_<start-year-month>_<end-year-month>.pkl.gz

QC_gatheredData fjerner en del data med tydelige problemer. Resultatene er lagret i:
<troll | trollOld | taf>_<startYear>_<endYear>_QC.pkl.gz
Jeg prøvde ikke å QC gamle data fra flyplassen.

QC’d data vises i ClimatePlots.
