# Overview                 

## Problem    

<hr/>

**Geographical Text Analysis**    

<hr/>
The shapefiles of different jurisdictions have unclean data and therefore need to be cleaned for proper analysis and insights. The shapefiles supplied here are as follows :        
* District Boundary          
* State Boundary       
* Subdistrict Boundary      

The state name in each of the shapefiles have special character such as `| and >` . These needed to be replaced by correct letters       

<hr/>

**Conflation**    

<hr/>       

The CRS of different shapefiles are different. They need to be the same so that the different shapefiles can be overlayed on top of each other.          
    

  

## Solution / Idea 

<hr/>

**Geographical Text Analysis**    

<hr/>

The state name in each of the shapefiles have special character such as `| and >` . These needed to be replaced by correct letters. We use Regular expressions and Python to clean the data. 


<hr/>

**Conflation**    

<hr/> 

The CRS of different shapefiles are different. They need to be the same so that the different shapefiles can be overlayed on top of each other. This is accomplished through the use of GeoPandas and Python            


# Current Implementation    

The Current Implementation uses Python to clean the Text and GeoPandas to read the shapefiles . Matplotlib and folium are used for data visualizations.     


# Technology      

Technology used        
* Python           
* Jupyter Notebooks           
* GeoPandas           
        

# Key Implementation Steps for the Full Solution   

We would use the same techniques and technologies for the full solution. We would use the Data Storage as Azure Blob Storage and put the cleaned shape files again in Azure Blob Storage   

