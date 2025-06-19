# Circos-Research-Visualizations
In collaboration with faculty at the School of Data Science at UVA

![6_12_25 __numpub raw](https://github.com/user-attachments/assets/1cbfdd37-be3b-495b-bae2-c11c511dd820)
![6_10_25 __unlogged](https://github.com/user-attachments/assets/04d533b5-e184-45f4-80cc-3a5714fe4ac8)


## Project Description
This project uses Circos, a software package for visualizing data and information. Initially created for visualizing genomic data and sequences, Circos is used here to visualize data on research publishings at research institutions. By taking this data from OpenAlex, the aim of this project is to have a more clear analysis on which fields of research at UVA have the most publishings and how well UVA does as a research institution compared to other R1 institutions. The metrics used in this study are the raw number of publishings and the mean normalized number of publishings compared to all R1 institutions.

## How to Run
Download Circos and follow the instructions on the Circos website accordingly. Within the example file, input data files in data and put all .conf files in the etc folder. Within the circos.conf file, replace karyotype and file variables with the respective files for each institution. 

To run, use the command: ./bin/circos -conf example/etc/circos.conf within the Circos folder.
