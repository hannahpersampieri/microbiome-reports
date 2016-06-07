# microbiome-reports
These programs were written for the BioSeq program at Tufts University.

R scripts to generate a class size set of pie charts and venn diagrams.
These materials are intended for classroom use.

Requirements: Installation of plotrix and extrafont packages

A CSV file containing the aggregate counts of each bacterial genus, with each column indicating a different sample, is required. There are usually over 600 different genuses found across samples-- However, since these counts aren't always significant, looking at the top ten is usually enough. 

A text file should also be written in order to indicate what samples are a "pair" with the other, for the venn diagram program. Usually students take two samples- one of their hard pallete, one of their retroauricular crease.

When generating pie charts:
User chooses CSV file, and a pdf of pie charts is created. The top ten genuses found are shown, along with their percent. An "Other" catagory is attached to the end.

When generating venn diagrams:
User chooses CSV file, then a text file that is a list of what samples are paired with one another. Then, a worksheet with three Venn Diagrams per page is produced. Only the top ten genuses in each sample are shown.

