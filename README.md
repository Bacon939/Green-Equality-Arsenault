# Green-Equality-Arsenault
Matthew Arsenault University of Calgary
November 25, 2024
The location of the data complied in this repository centers around Calgary, Alberta, Canada
Tree Density Distribution of Calgary.lpkx is a feature layer showing the different levels of tree densities thorughout Calgary. Dark green is high densities and light green is low densities.
Tree Density Map.jpg is an image of the Tree Density Distribution of Calgary.lpkx
Commmunity Districts.lpkx is a feature layer dividing Calgary into different sectors based on land use.
Areas of Unideal for Equality or Inadequacy.jpg is an image of the the Commmunity Districts.lpkx layer however only highlighting the sectors unideal for tree planting.
Optimal Locations Map.lpkx is a feature layer showing the best locations to plant trees in Calgary. The grey areas are areas already above the target density goals and are not prioirty areas. The light blue areas are under the target but by not much, the dark blue areas are signifcantly under the target 9% density and a top priority areas.
Optimal Locations Map.jpg is an image of the Optimal Locations Map.lpkx feature layer
Constraint Map.jpg is the overlay of the community districts not that are Unideal layed on top of the Optimal areas of Calgary for tree planting. 
Calgary_Equity_Index_Overlay_Statistics_20241125.csv is a csv file that I used to compared meadian income distribution to tree densities in Calgary.
Green Equality.ppkx is the packed ArcGIS pro map containing all feature layers.
The creative liscense on this repository is a Creative Commons Zero v1.0 Universal lisences. 
All feature layers and images were finalized on November 25, 2024
The data used in this repository was all gathered from Open Calgary database portal
The Tree densities were produced by using point data of trees in Calgary then using a Point Density geospatial technique using 1kmx1km cells to build the feautre layer Tree Density Distribution of Calgary.lpkx
The community district data gave four layers being Residential, Sub-Residential, Industrial, and Major Parks. I built the Commmunity Districts.lpkx by removing Residential and Sub-Residential as those areas are ideal for tree planting. Industrial was stayed in because it would eliminate the high energy zones in Calgary and Major Parks was also kept as it would eliminate areas that are not representing areas of Calgary that are different in tree densities with people living in that area.
The Optimal Locations Map.lpkx feature layer was created by inversing the tree density map to now having areas of low densities in dark blue and areas above the target to be greyed out. This acts as the base layer for the constrait map for other layers to be layed over such as the Commmunity Districts.lpkx feature layer.
