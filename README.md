# Interactive dashboard   
Have created Interactive Dasboard to explore the Belly Button Biodiversity datasetLinks to an external site.  
which catalogs the microbes that colonize human navels.  

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs,   
in the study) were present in more than 70% of people, while the rest were relatively rare.  
Following Screenshots are attached from my Work
#
![Screenshot 2024-06-10 192357](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/88db9861-db97-4feb-8fa2-7ae22aeaa8cc)
#
![Screenshot 2024-06-10 193040](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/3ec1c02e-b07c-4dae-9d96-2a0e3934cbd9)
#
![image](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/0ba0e80f-3adc-407e-91e1-f06817f19b78)
#
# Instructions
1. Used the D3 library to read in "samples.json" from the URL "https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json."  
2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.  
   - Used "sample_values" as the values for the bar chart.  
   - Used "otu_ids" as the labels for the bar chart.  
   - Used "otu_labels" as the hovertext for the chart.  
#
![image](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/a0f928c1-923e-4269-93c0-e83bab9ad8a2)
#
3. Created a bubble chart that displays each sample.   
   - Used "otu_ids" for the x values.   
   - Used "sample_values" for the y values.   
   - Used "sample_values" for the marker size.   
   - Used "otu_ids" for the marker colors.   
   - Used "otu_labels" for the text values.   
#
![image](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/64273613-acd3-40e5-bc7f-6ad4ac5e3d8e)
#
4. Displayed the sample's metadata, i.e., an individual's demographic information.   
   - Loopped through each key-value pair from the metadata JSON object and create a text string.   
   - Appended an html tag with that text to the "#sample-metadata" panel.   
#
![image](https://github.com/RoshniRanaDS/belly-button-challenge/assets/161755928/9587d445-4632-45fc-abc4-c82e5e43ad22)
#
5. Updated all the plots when a new sample is selected.
6. Deployed app to a free static page hosting service,
   such as GitHub Pages. 
  
