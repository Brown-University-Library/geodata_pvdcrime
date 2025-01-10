# TITLE

dct_title_s: 'Crime Incidents, Providence Rhode Island, 2024'

# DESCRIPTION

dct_description_sm:

- This is a point layer of crime incidents in Providence, Rhode Island from January to December 2024. This layer was created from the Providence Police Department's Case Log, which is updated nightly with the most recent 180 days of data. The purpose of this dataset is to archive data annually, add categories that are useful for classifying crimes, and provide geocoded locations that generally represent where an incident occurred; it is important to note that these locations are not precise. The logs include a general incident location such as a block range, street intersection, major landmark, or street name. Crime locations were geocoded using different methods based on the type of location, street intersections with the RIDOT geocoder to represent the intersection, block locations using the E911 shapefile provided by RIGIS to calculate the midpoint of a range of addresses in a block, and landmark centroid coordinates from a manually created points-of-interest file. Locations that fall outside these categories (e.g. street names) and locations which could not be geocoded were omitted from this dataset and stored in a separate tabular file. Each incident is assigned a unique case number; multiple offenses may be associated with the same incident/case number and are stored as separate data points. Each offense has a 'counts' attribute which indicates the number of instances of that offense. Offenses are uniquely identifiable by the 'unique_id' attribute, which is an extension of the associated case number. Offenses were categorized by type, where 'violent_cat' indicates the classification of violent crime, and 'property_cat' indicates the classification of property crime if applicable. Offenses are categorized using the 'offense_desc' (offense description) attribute according to the FBI's guidelines. This layer was created by the Brown University Library to allow for basic mapping and geospatial analysis of crime data. 

# LANGUAGE

dct_language_sm:

- eng

# CREATOR

dct_creator_sm:

- Brown University Library

# PUBLISHER

dct_publisher_sm:

- Providence Police Department

# PROVIDER

schema_provider_s: Brown

# RESOURCE CLASS

gbl_resourceClass_sm:

- Datasets

# RESOURCE TYPE

gbl_resourceType_sm:

- Point data

# LC SUBJECT

dct_subject_sm:

- Crime
- Criminal Statistics
- Police

# ISO THEME

dcat_theme_sm:

- Events
- Society

# TEMPORAL

dct_temporal_sm:

- '2024'

# DATE ISSUED

dct_issued_s: '2025-01'

# SPATIAL

dct_spatial_sm:

- 'Providence, Rhode Island, United States'

# BOUNDING BOX

dcat_bbox: 'ENVELOPE(-71.472667,-71.373614,41.861801,41.772435)'

# RIGHTS

dct_rights_sm:

- The data are licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. You are free to share and to adapt the work as long as you cite the source, do not use it for commercial purposes, and release adaptations under the same license.
- Disclaimer. Every effort was made to insure that the data, which was compiled from public sources, was processed and presented accurately. The creators and Brown University disclaim any liability for errors, inaccuracies, or omissions that may be contained therein or for any damages that may arise from the foregoing. Users should independently verify the accuracy and fitness of the data for their purposes.

# LICENSE

dct_license_sm:

- https://creativecommons.org/licenses/by-nc-sa/4.0/

# ACCESS RIGHTS

dct_accessRights_s: Public

# FILE FORMAT

dct_format_s: Shapefile

# UNIQUE ID

id: brown-08192024AAA

# IDENTIFIER

dct_identifier_sm:

- https://github.com/Brown-University-Library/geodata_pvdcrime/data

# METADATA MODIFIED

gbl_mdModified_dt: '2025-01-10'

# METADATA VERSION

gbl_mdVersion_s: Aardvark

# GEOREFERENCED

gbl_georeferenced_b: True