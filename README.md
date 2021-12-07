# rhizobium-infection

Repository for analyses of phage-rhizobium interactions, as well as indirect effect on plant fitness. 

##Data files: 

*20210929_InfectionMatrix.csv:* Infection matrix where 1 indicates successful infection, 0 indicates no infection, and 0.5 indicates partial lysis. Columns are phages, and rows are host strains. 

*Metadata_QuantFitness_scaled2.csv:* Metadata on strains, indicating treatment, mutualistic quality, and other fitness indicators.

*phage_pilot.csv:* Results of pilot greenhouse study looking for indirect effects of phage on plant fitness. 


##Scripts:

*pilot_analysis.Rmd:* Statistical analysis of greenhouse data, looking at differences between control, rhizobium, and phage treatments. 

*calgary_net.R:* Analysis of phage-host interactions of rhizobiophages from Hynes lab at the University of Calgary and Rhizobium leguminosarum from KBS. Includes regression of host resistance against partner quality, as well as analysis of ntework nestedness and modularity.  
