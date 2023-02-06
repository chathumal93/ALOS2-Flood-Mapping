# ALOS2-Flood-Mapping

This repositary includes an automatic statistical based flood mapping approch for ALOS2 Level 2.1 data.(Geometrically corrected and orthorectified data in .tif format).
Below chart gives a brief ooverview of ALOS2 L2.1 data.

<img src="./images/alos2.png"  width="400" height="250">
##### source: https://alos-pasco.com/en/alos-2/spec/

The flood extraction process is carried out in  a local machine with the help additional data coming from the Google Earth Engine. The picture below shows the carried out methodology to obtain flood layers.

<img src="./images/method.png"  width="400" height="500">

Jupyter notebooks in this repository uses Python version 3.9.7. Moreover, the requirement.txt includes all the necessary packages to be installed  to run thees notebooks. Helper_Functions.ipynb contains all the functions required for the ALOS2_Flood_Extraction.ipynb
