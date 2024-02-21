# chemical-uncertainties
Repository for code relating to paper entitled "Reducing greenhouse gas emissions uncertainties for chemical production" output from the [C-THRU project](https://www.c-thru.org/).\

Pipeline: data_extraction -> data_processing -> data_combination -> analysis\

Project structure:
- Data extraction\
Code for extracting data from ICIS, IHS, EcoInvent and CarbonMinds.

- Data processing\
Code for transforming data into consistent units.

- Data combination\
Code for assembling data sources\
i. Material mass + Conversion factors -> Material emissions\
ii. Material emissions allocation -> Process emissions\
iii. Process emissions + Production -> Total emissions\

- Analysis\
Code for generating outputs\
i. Compare emissions for same product via different processes\
ii. Plot magnitude of uncertainty against the magnitude of production for different products\
iii. Plot uncertainty reduction scenarios\
