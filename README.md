# Influenza-Surveillance-Thesis
I am completing my Master's degree in Bioinformatics and my thesis covers the expansion of our influenza genomic surveillance. I am simulating the deployment of 100, 250, and 500 rapid sequencing sites to see the impact on infection peak prediction and to watch the evolution of novel subclades across the US. You will see my progress chronologically as I work through this project. 

The first file will be code for compiling 2024 population data by county FIPS codes from US census data. In this first file, I also combined this data with the geographic center of each county using Gazetteer files. 

File 2 is how I set the baseline surveillance scenario in the United States. 
I decided to use 57 established sites in the US. These site designations have been recognized in the Influenza Virologic Surveillance Right Size Roadmap 2nd Ed. published by the APHL. This roadmap included multiple levels of sequencing sites: 
  1) CDC NCIRD (CDC Headquarters in DeKalb County GA) 
  2) CDC NIRCs (3 - Wadsworth Center in Albany NY, Wisconsin State Laboratory of Hygiene in Madison WI, and Cali. Dept. of Public Health VRDL in Richmond, CA)
  3) ISCs (6 - CDPHE Lab in Denver CO, Florida Bureau of Public Health Labs in Jacksonville FL, Mass. State Public Health Lab in Jamaica Plain MA, MDHHS Bureau of Labs in Lansing MI, MDH Public Health Lab in St. Paul MN, and Texas DSHS Lab in Austin TX)
  4) Directly Funded Municipal Public Health Laboratories (5 - NYC DOHMH in New York County NY, Chicago Dept. of Public Health in Cook County IL, Houston Health Dept. Lab in Harris County TX, Philadelphia Dept. of Public Health in Philadelphia County PA, and Los Angeles County PHL in Los Angeles County CA)
  5) State Central and DC PHL (51)
## NOTE: You may notice that these numbers do not total to 57. You are correct! There is some overlap in these groups and the same facility can serve as a state PHL and directly funded PHL. The CDC NCIRD is also doubly represented giving us our total of 57 facilities.
