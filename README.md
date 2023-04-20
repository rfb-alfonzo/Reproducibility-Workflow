# Reproducibility project-
Reproducibility project with our own data 

Before starting the project, have your data formatted like the data [here](https://github.com/rfb-alfonzo/Reproducibility-Workflow/tree/main/Data)
The data has been formatted to include mean, sd, and tukey values
To get tukey values, use program StatistiX 8.1, copy and paste data sets for your groups and follow the program instructions for tukey values
The [bar graph codes](https://github.com/rfb-alfonzo/Reproducibility-Workflow/tree/main/Codes) are designed to work around this data format.

There are multiple strains of Xylella Fastidios and this project is observing the interactions of these strains grown in co-cultures.  
There are four groups that need to be graphed:
    Strains grown on Chloramphenicol plates extracted from the Planktonic Layer
    Strains grown on Chloramphenicol plates extracted from the Biofilm Layer
    Strains grown on Kanamycin plates extracted from the Planktonic Layer 
    Strains grown on Kanamycin plates extracted from the Biofilm Layer
    
    
Follow protocols to grow the strains in co-cultures and count the colonies on your spot plates
once the LOG(10) CFU/mL is calculated format a cvs file to the data shown above and the codes will work.  
This is the protocol used for my project
     the bacteria are grown on CmR 10ug/ml and KmR 30ug/ml (cite Prems paper for antibiotic concentrations). They are grown on PWA ammended with antibiotic and later re-streaked.

So bacteria are adjusted to OD600: 0.8 and 10ul are added to 2ml of Pd2 media on a 24 well plate. Plate is incubated at 28 degrees celsius for 5-7 days.

Later an aliquot of 200ul is taken and serially diluted tenfold using a 96 well plate.

Dilution is as follows: 20ul of dilution added to 180ul of PD2 media. This is done serially and later spot plated on PWA with antibiotics to distinguish strains by their selection of resistance.

Plates are incubated for 10-14 days until colonies start forming.
Once colonies are visible and no clumped together the number of colonies is counted in each dilution.
<20 is Too few to count
>250 is Too many to count

Controls
WM1-1 (CmR) 
AlmaEm3 (CmR) 
EB92-1 (CmR) 
AlmaEm3 (KmR)
EB92-1 (KmR)
BB08-1 (KmR)

Co-Cultures
Group 1 
WM1-1 (CmR) + AlmaEM3 (KmR)
WM1-1 (CmR) + EB92-1 (KmR)
WM1-1 (CmR) + BB08-1 (KmR)
Group 2 
AlmaEM3 (CmR) + EB92-1 (KmR)
AlmaEM3 (CmR) + BB08-1 (KmR) 
Group 3 
EB92-1 (CmR) + BB08-1 (KmR) 


