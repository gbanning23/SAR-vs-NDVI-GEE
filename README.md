# SAR-vs-NDVI-GEE
JavaScript codes created for the acquisition and filtering of USGS National Land Cover Database, Sentinel-1 SAR C-band, and Landsat 8 OLI imagery data in Google Earth Engine. 
This was created for GEOG 5070 Remote Sensing II Spring 2026 term project; "Comparative Analysis of SAR and NDVI Sensitivity to Vegetation Regrowth Post-Wildfire."
Code was debugged utilzing Google Gemini AI.

Important: this code utilizes a spatial boundary filter .filterBounds(CamPeakDay1). This was created as a shapfile in ArcGIS Pro prior to being uploaded to GEE as an asset.
Be sure to create and upload your own boundary asset prior to running this code.
Otherwise, remove the boundary filters to pull global data.
