## ECOSTRESS Science and Application Team Meeting Workshop October 2024

This repository contains data required to interactively participate in the ECOSTRESS STM Workshop tutorials. The workshop is a collaboration between Jet Propulsion Laboratory (JPL) and the Land Processes Distributed Active Archive Center (LP DAAC). The LP DAAC faciliated portion of the workshop will include and a demonstrtion on using EarthData for ECOSTRESS data products. The JPL portion of the workshop includes a QGIS tutorial and a jupyter notebook tutorial using the ECOSTRESS Land Surface Temperature (LST) product. The QGIS tutorial will take place in the Opensource cross-platform QGIS application but will use auxillary vector data available in this repository. Auxillary data was pre-processed to limit file size, the text below includes the steps we took to prepare the auxillary data. The jupyter notebook portion of the tutorial will take place in GitHub codespaces using the ECOSTRESS Land Surface Temperature (LST) data included in this repository.   

The QGIS auxilliary data includes the files `California_Cities.geojson` and `CA_state_boudary.geojson`. The `California_Cities.geojson` was downloaded from [ArcGIS Hub](https://hub.arcgis.com/datasets/06ce85b6fdf349d78c471d7c2ee8cb66_0/explore), `CA_state_boudary.geojson` was streamed into QGIS using the following steps: 
1. Download HCMGIS Python Plugin: Plugins in tool bar > Manage and install Plugins > search for "HCMGIS" and select > Install Plugin
2. Download State Boundaries usinsg OpenData: HCMGIS in tool bar > Download OpenData > Global Administrative Areas by Country from GADM > select "United States" from drop down menu > Apply
3. Extract the State we want from the State boundadry layer: Run the "Extract by attributes" tool, selecting the `gadm41_USA_1` layer and setting the Selection Attribute field to "NAME_1" and the Value to "California"

#### Points of Contact: 
Claire Villanueva-Weeks (she/her) 
[claire.s.villanueva-weeks@jpl.nasa.gov](mailto:claire.s.villanueva-weeks@jpl.nasa.gov)

Quentin Delahane (he/him) 
[quentin.dehaene@jpl.nasa.gov](mailto:quentin.dehaene@jpl.nasa.gov)

Gregory Halverson (they/them) 
[gregory.h.halverson@jpl.nasa.gov](mailto:gregory.h.halverson@jpl.nasa.gov)
