# Projecting-seasonal-COVID-19-infection-based-on-the-evolution-of-coronavirus-seasonality
Supplemental Electronic Data files for: 

Projecting seasonal COVID-19 infection based on the evolution of coronavirus seasonality

Jeffrey P. Townsend PhD 1,2,3,4*, April D. Lamb MS 5, Hayley B. Hassler MS 1, Pratha Sah PhD 6, Aia Alvarex Nishio 6, Cameron Nguyen 5, Alex Dornburg PhD 5

1 Department of Biostatistics, Yale School of Public Health, New Haven, Connecticut 06510, USA
2 Department of Ecology and Evolutionary Biology, Yale University, New Haven, Connecticut 06525, USA
3 Program in Computational Biology and Bioinformatics, Yale University, New Haven, Connecticut 06511, USA
4 Program in Microbiology, Yale University, New Haven, Connecticut 06511, USA
5 Department of Bioinformatics and Genomics, University of North Carolina, Charlotte, NC 28223
6 Yale College, New Haven, Connecticut

*Corresponding author:
Jeffrey P. Townsend
135 College St, New Haven, CT 06510-2483. jeffrey.townsend@yale.edu, (203) 737-7042

Electronic Data Files prepared by:
April D. Lamb
alamb17@uncc.edu

###

This directory contains raw data of endemic coronavirus infections by month, newick formatted molecular and time tree files, and R Markdown files necessary for imputing and visualizing monthly proportions of SARS-CoV-2 infection using RPhylopars v0.2.12(Goolsby et al., 2017).

~/seasonality/data contains raw data of endemic coronavirus (HCoV-229E, HCoV-NL63, HCoV-HKU1, and HCoV-OC43) infections

~/seasonality/code contains R Markdown files necessary to generate proportions of infections by month

~/molecular_trees/ contains all molecular phylogenies based on the concatenated alignment (RAxML, IQTREE) and based on the non-recombining block of SARS-CoV-2 alignment (RAxML_non_recombinant, IQTREE_non_recombinant). Alignment information available in Townsend et al. 2021 Lancet Microbe and on Zenodo: 10.5281/zenodo.5146327.

~/rphylopars.zip/data contains formatted proportions of monthly infections for endemic coronaviruses (HCoV-229E, HCoV-NL63, HCoV-HKU1, and HCoV-OC43) for each location.

~/rphylopars.zip/code contains R Markdown files necessary to impute monthly proportions of SARS-CoV-2 infections using RPhylopars v0.2.12(Goolsby et al., 2017)

~/time_trees/ contains all time trees based on the concatenated alignment (IQTREE_time_tree, RAxML_RelTime, RAxML_TreeTime, IQTREE_RelTime, IQTREE_TreeTime) and based on the non-recombining block of SARS-CoV-2 alignment (IQTREE_time_tree_non_recombinant, RAxML_RelTime_non_recombinant, RAxML_TreeTime_non_recombinant, IQTREE_RelTime_non_recombinant, IQTREE_TreeTime_non_recombinant). Alignment information available in Townsend et al. 2021 Lancet Microbe and on Zenodo: 10.5281/zenodo.5146327.

~/visualization/data contains imputed monthly proportions of SARS-CoV-2 infections and monthly proportions of endemic coronaviruses HCoV-229E, HCoV-NL63, HCoV-HKU1, and HCoV-OC43 for each location and phylogeny.

~/visualization/code contains R Markdown files necessary to visualize imputed monthly proportions of SARS-CoV-2 infection.
