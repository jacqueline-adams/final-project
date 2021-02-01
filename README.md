# Final Project Outline #

_Research Question:_ 
What is the relationship between water bill debt and geographic location in the state of California? 
Do certain demographic characteristics also coincide with these debt numbers (i.e. race and ethnicity, % owner versus renter, 
medium household income, and immigrant status). 

_Why It's Important:_ 
This research is extremly timely. Since the start of COVID, there has been a moratoria on water shutoffs, as issued by Governor Newsom. 
This means that water customers cannot have their water shut off during the pandemic due to their inability to pay. In order to better assess the extent of water 
bill debt, the California State Water Resources Control Board distriubted a survey in November to access the scale of unpaid debt across the state. As water systems 
become more strained under the weight of unpaid debt, the state will need to determine the extent of the debt in order to provide assistance and recovery
after the pandemic is over and moratoria on water shutoffs are lifted. 

_Spatial Scope:_ 
This project will look at statewide data (water bill debt and American Community Survey Data). The goal is to understand the statewide extent of bill debt.
The analysis will help determine in what regions, localities, and demographic areas the debt is concentrated (or spread out). Having a better sence of where debt 
is distributed across the state will help policymakers allocate aid and target their resources to water systems or regions most impacted by bill debt. 

**Edit:** I am also considering mapping COVID case data over this map to see if areas hardest hit by COVID are also suffering the most under water bill debt. 

_Sources:_
* The first data source is from a survey of water system bill debt across California
* The second source is American Community Survey data that has already been linked with the above dataset 
    * The first and second sources can be found [here](https://docs.google.com/spreadsheets/d/1Z9cMLu8CDtocVbhaceNgG4_ackWw-eGe7QOsM_JiXm0/edit?usp=sharing)
* The third source will be watersystem borders, which will be overlayed on the state map (tentative)
    * Shapefiles of public watersystems statewide can be downloaded [here](https://gis.data.ca.gov/datasets/fbba842bf134497c9d611ad506ec48cc_0/data)
    * **Edit**: I am keeping this dataset as a potential method of evaluation, but after talking with my research adviser, this dataset has already been used in
    a lot of analysis, so I will only use it if my analysis of COVID cases does not work. 
* A fourth, new source of data I am planning on using is COVID cases, by county, as tracked by Harvard, which you can find [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HIDLTK)
* I also added a dataset that outlines county borders in California (though, I might need to find a better dataset), you can find it [here](https://map.igismap.com/gis-data/united%20states-california/administrative_boundaries_level6_counties_polygon)

**Note** *this is a dataset I've been working on as part of my Graduate Student Researcher position. I am going beyond an intial analysis that was done for my 
position, and implementing the spatial analysis compoent, thus, this is why the ACS data is already merged with the debt data*

_Intended Analysis and Resulting Visualizations:_
After comparing water bill debt statewide to sociodemographic factors, the final visualization will show a color coded scale that determines water systems or 
areas most in need of assistance. Systems will be scaled based on (intensity of debt, median household income, % renter/owner occupied housing, and perhaps other
metrics that I will determine to create a sort of index that determines how "in need" an area is). This information will either be compared with, or overlayed with, 
number of COVID cases statewide, by county. 

_Conclusion:_
From this research, we will have a better idea of which regions are suffering the most under the burden of unpaid water bill debt. Ideally, this information 
can then be used to target aid and ensure that the water systems in these areas do no suffer financially from lost revenues and that the customers to not 
suffer from lowered quality drinking water from systems that lost resources due to debts. More broadly, this information could also explain which regions of 
Califorina have been most impacted economically by COVID, although more research will need to be done to bolster that claim. Further, with the added component of COVID cases statewide, this data will determine if there is any relationship between COVID cases themselves at water bill debt. 

