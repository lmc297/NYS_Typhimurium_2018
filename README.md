# NYS_Typhimurium_2018
Supplementary material for the 2018 New York state Typhimurium project

## NYS_Typhimurium_2018_beast_relaxed_skyline.xml

BEAST XML file used for the project; performed 5 independent runs with BEAST version 2.5.0

## NYS_Typhimurium_2018_beast_relaxed_skyline_combined.log

BEAST log file produced using LogCombiner-2 to combine log files from 5 independent BEAST runs with NYS_Typhimurium_2018_beast_relaxed_skyline.xml as input (using BEAST version 2.5.0); viewed using Tracer version 1.7.1

## NYS_Typhimurium_2018_beast_relaxed_skyline_10burnin_MCC_CA.tree

NEXUS file produced using TreeAnnotator-2 (10% burn-in, 0.0 posterior probability limit, maximum clade credibility target tree, Common Ancestor node heights) and the combined trees (produced using LogCombiner-2; see NYS_Typhimurium_2018_beast_relaxed_skyline_combined.log for log file) from 5 independent BEAST runs with NYS_Typhimurium_2018_beast_relaxed_skyline.xml as input (using BEAST version 2.5.0)

### To view node height 95% highest posterior density (HPD) intervals and posterior probabilities on branches, as well as other tree metrics, this file can be viewed in FigTree version 1.4.3.
