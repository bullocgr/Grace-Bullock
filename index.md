## About me

I am a fourth year computer science student at Oregon State University. My degree focus is in mobile application and website development. 

Related to my field, I enjoy working with graphics and have experience in OpenGL, OpenSL, and Unreal. I also enjoy solving parallel processing problems as well as optimizing software for hardware.

## Projects

[Geospatial Analysis for Disaster Planning](https://github.com/bullocgr/capstone)

Currently, I am working with three other computer science students on a project titled "Geospatial Analysis for Disaster Planning."

The project creates a geospatial analysis tool that will provide emergency managers with a system level view of the impact of disasters on their jurisdiction’s lifeline networks. This means the software helps them in creating robust response plans by identifying critical intersections of lifeline networks that may cause bottlenecks in recovery, as well as by providing estimates of time and resources required for debris clearance. The team is partnered with Dr. Joseph Louis, an Oregon State civil engineering professor.

The project currently runs within ArcGIS Pro, a tool used by civil engineers and emergency managers as well as people who do work with geographical data (or geo data). ArcGIS uses a feature called [toolboxes](https://pro.arcgis.com/en/pro-app/latest/tool-reference/analysis/an-overview-of-the-analysis-toolbox.htm) which allows for the user to select areas, create buffers, and perform certain calculations. ArcGIS also provides the functionality of creating custom toolboxes which can be paired with [scripts](https://pro.arcgis.com/en/pro-app/latest/help/analysis/geoprocessing/basics/create-a-python-script-tool.htm) that give the user the same functionalities but can perform specialized calculations that ArcGIS Pro does not offer. The scripts can take in certain data types defined by the user and then print out the calculations.

The team has collectively created three scripts. The first one is a [random raster generator](https://github.com/bullocgr/capstone/blob/main/scripts/CreateRandomRaster.PY). The rest of our scripts require [raster data](https://desktop.arcgis.com/en/arcmap/10.3/manage-data/raster-and-images/what-is-raster-data.htm) in order to run. Originally, our team wanted to find raster data that simulated what debris spread would look like if the town of Astoria, OR was hit with an earthquake but we were not able to find any that was widely available. Instead, we created a script to simulate debris spread so that we could test the other tools with this data.

The next script is a [clearance time script](https://github.com/bullocgr/capstone/blob/main/scripts/DetermineClearanceTime.PY). This script takes in the previous raster data as well as an area to clear (in polygon format) and determines how long it will take to clean up the area. The calculations are based on equations that Dr. Louis provided the team with. The last script is a [debris volume script](https://github.com/bullocgr/capstone/blob/main/scripts/DetermineDebrisVolume.PY). This script determines just how much debris there is given the raster data. The raster data does not provide us with exact numbers so we needed to find a way to calculate certain cells within the raster data. This script achieves that and gives the output of how much debris there is as a hard value.

My role in the project has been managerial. I have been in charge of keeping track of progress and relaying that information to Dr. Louis as well as facilitating meetings. The docs for our github and drive have been polished by me and maintaining them when there are updates has been done by me. Our team has met with outside resources and making sure we are prepped for and with questions as well as guiding the meetings so they are useful and efficient. I have also been the main person to test and merge pull requests in the github repository. 



## Links
[Linkedin](https://www.linkedin.com/in/grace-m-bullock/)

[Github](https://github.com/bullocgr)
