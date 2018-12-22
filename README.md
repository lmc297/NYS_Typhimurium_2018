# NYS_Typhimurium_2018
Supplementary material for the 2018 New York state Typhimurium project

## NYS_Typhimurium_2018_beast_relaxed_skyline.xml

BEAST XML file used for the project; performed 5 independent runs with <a href="http://www.beast2.org/">BEAST version 2.5.0</a>

## NYS_Typhimurium_2018_beast_relaxed_skyline_combined.log

BEAST log file produced using <a href="http://www.beast2.org/programs/">LogCombiner-2</a> to combine log files from 5 independent BEAST runs with NYS_Typhimurium_2018_beast_relaxed_skyline.xml as input (using <a href="http://www.beast2.org/">BEAST version 2.5.0</a>); viewed using <a href="http://beast.community/tracer">Tracer version 1.7.1</a>

## NYS_Typhimurium_2018_beast_relaxed_skyline_10burnin_MCC_CA.tree

NEXUS file produced using <a href="http://www.beast2.org/programs/">TreeAnnotator-2</a> (10% burn-in, 0.0 posterior probability limit, maximum clade credibility target tree, Common Ancestor node heights) and the combined trees (produced using <a href="http://www.beast2.org/programs/">LogCombiner-2</a>; see NYS_Typhimurium_2018_beast_relaxed_skyline_combined.log for log file) from 5 independent BEAST runs with NYS_Typhimurium_2018_beast_relaxed_skyline.xml as input (using <a href="http://www.beast2.org/">BEAST version 2.5.0</a>)

### This tree can be viewed using <a href="http://tree.bio.ed.ac.uk/software/figtree/">FigTree version 1.4.3</a>. By default, node bars indicate node height 95% highest posterior density (HPD) intervals, branches are colored by posterior probability, and the time scale in years is plotted along the x-axis.
