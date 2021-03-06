# GNAF File Geodatabase and Shapefiles
##### February 2021
## Product Information
GNAF is Australia’s authoritative, geocoded address dataset, containing over 15 million addresses. It is a large dataset with a complex architecture, requiring processing before being ready to use. This product supplies GNAF in common industry formats such as File Geodatabases and Shapefiles, reducing the need for end users to process the data themselves.<br/>
<br/>
The product is available in three different formats:<br/>
* Full GNAF File Geodatabase - This is a duplicate of the GNAF dataset supplied as a File Geodatabase. It keeps the normalised structure of GNAF and requires users to create table joins to link required information. Suitable for advanced users with a knowledge of the GNAF architecture.<br/>
Download: [GNAF_Full_FGDB_FEB21.zip](https://github.com/mosaicgeospatial/gnaf-file-geodatabase-shapefile/releases/download/FEB21/GNAF_Full_FGDB_FEB21.zip)
* Simple GNAF File Geodatabase - Simplified, consolidated feature classes supplied as a File Geodatabase. The main parts of the GNAF dataset have been combined into easy, ready to use feature classes. All states have been merged together and attributes reformatted and joined. Suitable for everyone who wants to get up and running with GNAF quickly.<br/>
Download: [GNAF_Simple_FGDB_FEB21.zip](https://github.com/mosaicgeospatial/gnaf-file-geodatabase-shapefile/releases/download/FEB21/GNAF_Simple_FGDB_FEB21.zip)
* Simple GNAF Shapefiles - Simplified GNAF data as above, but supplied as Shapefiles.<br/>
Download: [GNAF_Simple_Shapefile_FEB21.zip](https://github.com/mosaicgeospatial/gnaf-file-geodatabase-shapefile/releases/download/FEB21/GNAF_Simple_Shapefile_FEB21.zip)
## Key Details
* GNAF Data Source: February 2021
* Area of Coverage: Australia
* Coordinate System: GDA2020 EPSG:7844
## Considerations
* File Geodatabases have been compressed to save storage space and reduce download time. In order to directly edit the file geodatabase it must first be uncompressed using the Uncompress File Geodatabase Data tool.
* GNAF fields that were not populated have not been included.
* The file geodatabase structure and field definitions have been supplied in readable XML documents using the Export XML Workspace Document tool.
## Related Products and Datasets
GNAF Locator for ArcGIS Pro and Enterprise which converts addresses to map locations via geocoding has been created from GNAF. It can be used to interactively search for, and zoom to, addresses on a map or to batch geocode an entire table of addresses with latitude and longitude coordinates. See the [Mosaic Geospatial website](https://www.mosaicgeospatial.com) for more information.
## Support
Community support for the Open Edition of the GNAF Locator is provided at the GitHub site:<br/>
[https://github.com/mosaicgeospatial/gnaf-file-geodatabase-shapefile](https://github.com/mosaicgeospatial/gnaf-file-geodatabase-shapefile)
## Attribution
Incorporates or developed using G-NAF © Geoscape Australia licensed by the Commonwealth of Australia under the Open Geo-coded National Address File (G-NAF) End User Licence Agreement. The Geoscape Geocoded National Address File (G-NAF) dataset can be downloaded from: [https://data.gov.au/data/dataset/19432f89-dc3a-4ef3-b943-5326ef1dbecc](https://data.gov.au/data/dataset/19432f89-dc3a-4ef3-b943-5326ef1dbecc)
## Copyright and Licensing
This product is Copyright © 2020, Mosaic Geospatial.<br/>
<br/>
Use of this product is subject to the Open Geo-coded National Address File (G-NAF) End User Licence Agreement (EULA). A copy of this license has been provided with the product.<br/>
<br/>
The EULA terms are based on the Creative Commons Attribution 4.0 International license (CC BY 4.0). However, an important restriction relating to the use of the open G-NAF for the sending of mail has been added. The open G-NAF data must not be used for the generation of an address or the compilation of an address for the sending of mail unless the user has verified that each address to be used for the sending of mail is capable of receiving mail by reference to a secondary source of information. A fact sheet with more information about the usage restriction has been provided with the product.
