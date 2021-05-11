GIS Final Project Spring 2021 

Abstract
  12.7 percent of all Americans identify as being handicapped.  Those with disabilities often rely on public transportation.  Is there a higher percentage of individuals identifying as handicapped in the areas where high amount of public transportation is available?  Using the Census information by Congressional districts for both the district areas and the population of those identifying as disabled along with the US fixed transportaiton, a map of this information was created.  
  
Purpose
  Determine the population per Congressional District overall and the sub population that has identified as handicapped in those districts.  Compare this wqith the national average of 12.7 percent. This data will be compared to the national average of handicapped individuals to see how those match up.  The data can be used to determine funding needs, areas that should be redistricted, and areas where transportaiton is needed.  

Background/Rationale and Sources
  https://data.census.gov/cedsci/table?q=disability&tid=ACSST1Y2019.S1810
  https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=Congressional+Districts+%28116%29
  https://www.bts.gov/geography/geospatial-portal/NTAD-direct-download

Analysis Steps
  National Average for Disability is 12.7% +/-.1$ based on the 2019 Community Survey according to the US Census Bureau
  Article I, Section II of the Constitution says that each state shall have at least one U.S. Representative, while the total size of a state's delegation to the       House depends on its population. The number of Representatives also cannot be greater than one for every thirty thousand people.
  Useing this data, determine totals population per district and then the comparitive of that population as a shole and then the sub portion of the data for those identifying as being handicapped.  Determine by comparing those with the transportation availablifilty to determine how that compares to the areas of , 
  
Results and Discussion
  See Conclusion

Conclusions
  Unfortunately I didn't have much time to investigate the details as I was depending on merged table data and found out that I needed to have the 

Limitations
  I was unable to find good Rail information as the only information I was coming up had combined commuter, passenger, and freight lines.  

Future Research
  Additional data could be gathered to determine the volume of riders using reduced fare in on specific transit systems.
  Funding by State and/or Congressional district could be gathered and analyzed.
  Try to find some good passenger rail data.  
  
Work Process Log
  Gathered Census Data for Disability Characteristics from https://data.census.gov/cedsci/table?q=disability&tid=ACSST1Y2019.S1810
  ![image](https://user-images.githubusercontent.com/68611213/117737490-0297a400-b1c8-11eb-919f-300dfcf7d397.png)
  Gathered Data for Contressional Districts From https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=Congressional+Districts+%28116%29
  ![image](https://user-images.githubusercontent.com/68611213/117737859-b9941f80-b1c8-11eb-808e-1124f478a04d.png)
  Gathered Data for Fixed Transit https://www.bts.gov/geography/geospatial-portal/NTAD-direct-download
  ![image](https://user-images.githubusercontent.com/68611213/117738260-a03fa300-b1c9-11eb-8fba-741250b52133.png)
  Using QGIS
    created the base map with USGS Topgraphic Map
    created shapefile with the Congressional Districts Info
      updated to outline only, green, .56 milimeters
    created vector layer containing the Fixed Transit Info
      updated the Agencies to be blue dots and only 1mm
    added labeling 
    added scale 
    added title
    performed join attributes by nearest on the shape files----this is where I ran into trouble as I thought I could join the files because they were both the same  data type, but found out that you can't do that on shape files.  
    
    
    
      
  
  
