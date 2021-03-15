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


_Sources:_
* The first data source is from a survey of water system bill debt across California
* The second source is American Community Survey data that has already been linked with the above dataset 
    * The first and second sources can be found [here](https://docs.google.com/spreadsheets/d/1BDMh89Eh4BCAB-DpOLeQb518IZX-dTbhFQRlWWTEeSU/edit?usp=sharing). 
* A third source of data is a GeoJson file of Zip Code borders in California, which can be found [here](https://github.com/OpenDataDE/State-zip-code-GeoJSON/blob/master/ca_california_zip_codes_geo.min.json)
* Finally, I'm using a dataset that contains Latitude and Longitude coordinates for every zip code in California, which can be found [here](https://public.opendatasoft.com/explore/dataset/us-zip-code-latitude-and-longitude/table/)

_Intended Analysis and Resulting Visualizations:_
After comparing water bill debt statewide to sociodemographic factors, the final visualization will show a color coded scale that determines
areas most in need of assistance. Systems will be scaled based on (intensity of debt, median household income, % poverty, and racial or ethnic makeup, and a number of household characteristics such as vehicle access, living in overcrowded housing, etc). The metrics that I will determine to create a sort of index that determines how "in need" an area is. 

_Conclusion:_
From this research, we will have a better idea of which regions are suffering the most under the burden of unpaid water bill debt. Ideally, this information 
can then be used to target aid and ensure that the water systems in these areas do no suffer financially from lost revenues and that the customers to not 
suffer from lowered quality drinking water from systems that lost resources due to debts. This research will help lawmakers determine where they need to target aid once the moratorium on water shutoffs has been lifted, and will help provide a safety net so thousands are not left without water. More broadly, this information could also explain which regions of Califorina have been most impacted economically by COVID, although more research will need to be done to bolster that claim. Further, with the added component of COVID cases statewide, this data will determine if there is any relationship between COVID cases themselves at water bill debt. 

