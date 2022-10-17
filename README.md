# Covertype_dataset
Data Preprocessing and Classification

About Dataset:

What is Covertype dataset about?

The Forest CoverType dataset
1. Title of Database: Forest Covertype data
2. Number of instances (observations):  581,012 
3. Number of Attributes: 12 measures, but 54 columns of data (10 quantitative variables, 4 binary wilderness areas and 40 binary soil type variables)
4. Attribute information:
Given is the attribute name, attribute type, the measurement unit anda brief description.  The forest cover type is the classification problem.
The order of this listing corresponds to the order of numerals along the rows of the database.Name Data Type Measurement DescriptionElevation quantitative meters Elevation in meters
Aspect quantitative azimuth Aspect in degrees azimuth Slope quantitative degrees Slope in degrees Horizontal_Distance_To_Hydrology quantitative meters Horz Dist to nearest surface water features
Vertical_Distance_To_Hydrology quantitative meters Vert Dist to nearest surface water features Horizontal_Distance_To_Roadways quantitative meters Horz Dist to nearest roadway
Hillshade_9am  quantitative 0 to 255 index Hillshade index at 9am, summer solstice Hillshade_Noon quantitative 0 to 255 index Hillshade index at noon, summer soltice
Hillshade_3pm quantitative 0 to 255 index Hillshade index at 3pm, summer solstice Horizontal_Distance_To_Fire_Points quantitative meters Horz Dist to nearest wildfire ignition points
Wilderness_Area (4 binary columns) qualitative 0 (absence) or 1 (presence) Wilderness area designation Soil_Type (40 binary columns) qualitative 0 (absence) or 1 (presence) Soil Type designation
Cover_Type (7 types) integer 1 to 7 Forest Cover Type designation


Code Designations:
Wilderness Areas:   
1 -- Rawah Wilderness Area
2 -- Neota Wilderness Area
3 -- Comanche Peak Wilderness Area
4 -- Cache la Poudre Wilderness Area

Soil Types: 1 to 40 : based on the USFS Ecological
Landtype Units for this study area.

Forest Cover Types: 
1 -- Spruce/Fir
2 -- Lodgepole Pine
3 -- Ponderosa Pine
4 -- Cottonwood/Willow
5 -- Aspen
6 -- Douglas-fir
7 -- Krummholz

NOTE:  Summary statistics not included in this documentation.
8. Missing Attribute Values:  None.


9. Class distribution:
Number of records of Spruce-Fir         : 211840 
Number of records of Lodgepole Pine     : 283301 
Number of records of Ponderosa Pine     : 35754 
Number of records of Cottonwood/Willow  : 2747 
Number of records of Aspen              : 9493 
Number of records of Douglas-fir        : 17367 
Number of records of Krummholz          : 20510 
Number of records of other              : 0 
Total records                           : 581012
