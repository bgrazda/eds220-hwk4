# False Color Mapping of 2017 Thomas Fire in SB County

## About: 


![images/sb-2017-thomas-fire.jpeg](images/sb-2017-thomas-fire.jpeg)

- Combine landsat dataset and outside shapefile to draw connections using false color imaging
- Practice using NetCDF dataset and dropping dimensions
- Visualize the lasting impact of secondary succession due to 2017 Thomas Fire using landsat data
- Filter a dataset and export a geometry shapefile based off filtered dataset

## Repository Structure

```bash
eds220-hwk4
│
├── data                        
│   ├──California_Fire_Perimters_(all).cpg
│   ├── California_Fire_Perimters_(all).dbf
│   ├── California_Fire_Perimters_(all).prj # Final choropleth map
│   ├── California_Fire_Perimters_(all).shp
│   ├── California_Fire_Perimters_(all).shp.xml
│   ├── California_Fire_Perimters_(all).shx
│   ├── landsat8-2018-01-26-sb-simplified.nc
│   ├── thomas_fire.cpg
│   ├── thomas_fire.dbf
│   ├── thomas_fire.prj
│   ├── thomas_fire.shp
│   ├──thomas_fire.shx
│
├── hwk4-task2-fire-perimeter-GRAZDA.ipynb # Jupyter notebook for analysis
├── hwk4-task2-false-color-GRAZDA.ipynb  # Jupyter notebook for analysis        
├── README.md  
├── LICENSE                      
├── .gitignore  
│
├── images/                       
│   ├── sb-2017-thomas-fire.jpeg  # Image used in the README
│                
```

## Data

All of the data is located in the data folder. The landsat data is located within the UCSB Bren workbench-1 server in the following filepath:
```bash
/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc
```
This landsat data was retrieved from the Microsoft Planetary Computer data catalogue. The Thomas Fire data can be directly accessed by selecting the shapefile using this [https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436](link.)

## References

Galaz García, Carmen.Assignment4 – EDS 220 - Working with Environmental Datasets. (n.d.). https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4.html

Microsoft Planetary Computer. (n.d.). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Publisher CAL FIRE. (2024, May 14). State of California - California Fire Perimeters (all). Catalog. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436 

