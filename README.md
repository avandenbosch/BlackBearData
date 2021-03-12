# BlackBearData
This README.md file was generated on 2021-02-25 by Adrienne VandenBosch



###GENERAL INFORMATION

1. Title of Dataset: Spatial Distribution of Black Bear Incident Reports in Michigan

2. Author Information
	
	A. Principal Investigator Contact Information
		
		Name: Jamie E. McFadden-Hiller
		
		Institution: Carnivore Ecology Laboratory, Forest and Wildlife Research Center, Mississippi State University,Starkville, Mississippi, United States of America
		
		Email: jem739@msstate.ed

	B. Associate or Co-investigator Contact Information
		
		Name: Dean E. Beyer Jr.
		
		Institution: Carnivore Ecology Laboratory, Forest and Wildlife Research Center, Mississippi State University,Starkville, Mississippi, United States of America
		
		Email: j.belant@msstate.edu

	C. Alternate Contact Information
		
		Name: Jerrold L. Belant
		
		Institution: Wildlife Division, Michigan Department of Natural Resources, Marquette, Michigan, United States of America

3. Date of data collection: Data compiled from reports dated from 2003 to 2015

4. Geographic location of data collection: Michigan, United States of America

5. Information about funding sources that supported the collection of the data: This study was supported by Mississippi State University and Michigan Department of Natural Resources. The funders had no role in study design, data collection and analysis, decision to publish, or preparation of the manuscript.



###SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: CC-BY-4.0 https://creativecommons.org/licenses/by/4.0/legalcode

2. Links to publications that cite or use the data: https://doi.org/10.1371/journal.pone.0154474

3. Links to other publicly accessible locations of the data: https://figshare.com/articles/dataset/Spatial_Distribution_of_Black_Bear_Incident_Reports_in_Michigan/3208564?file=5037811 

4. Recommended citation for this dataset: McFadden-Hiller, J. E., Beyer, D. E. Jr., & Belant, J. L. (2016) Spatial Distribution of Black Bear Incident Reports in Michigan [data set]. Available as Supporting Information for: PLoS ONE 11(4): e0154474. https://doi.org/10.1371/journal.pone.0154474



###DATA & FILE OVERVIEW

1. File List: 
BlackBearIR_Metadata.xml, 	metadata for the dataset

BlackBearIR_S1Dataset.xlsx, 	Black bear incident report dataset. Dataset contains selected black bear incident reports received by Michigan Department of Natural Resources during 2003–2011 for the state of Michigan used in the analysis.

BlackBearIR_S2Dataset.xlsx,	Independent dataset. Dataset contains selected black bear incident reports received by Michigan Department of Natural Resources during 2012–2015 for the state of Michigan used for the model evaluation.	

BlackBearIR_Report.docx, 	Profile of the dataset and original metadata, chosen repository profile, recommended citation, considerations for ling-term preservation, and copyright license.



####DATA-SPECIFIC INFORMATION FOR: BlackBearIR_S1Dataset.xlsx

1. Number of variables: 24

2. Number of cases/rows: 7,200

3. Variable List: 

	ID,		Unique ID for all data (i.e., bear incident reports and random units)

	recordnum,	Bear Report Number - ID number from MDNR database for bear incident reports

	randid,		Unique ID for random units

	hbc,		response variable: 1 = bear incident reports; 0 = random units

	region,		regional location: UP = Upper Peninsula; LP = Lower Peninsula

	centroidx,	X UTM of section centroids

	centroidy,	Y UTM of section centroids

	buffarea,	Area of clipped buffer (m^2)

	waterprop,	proportion of 2006 NLCD land cover: Open Water

	opendevprop,	proportion of 2006 NLCD land cover: Developed, Open Space

	highdevprop,	proportion of 2006 NLCD land cover: Developed, High Intensity

	barrenprop,	proportion of 2006 NLCD land cover: Barren Land

	decidprop,	proportion of 2006 NLCD land cover: Deciduous Forest

	evergreenprop,	proportion of 2006 NLCD land cover: Evergreen Forest

	mixprop,	proportion of 2006 NLCD land cover: Mixed Forest

	shrubprop,	proportion of 2006 NLCD land cover: Shrub/Scrub

	herbprop,	proportion of 2006 NLCD land cover: Grassland/Herbaceous

	haypastprop,	proportion of 2006 NLCD land cover: Pasture/Hay

	cropprop,	proportion of 2006 NLCD land cover: Cultivated Crops

	woodywetprop,	proportion of 2006 NLCD land cover: Woody Wetlands

	herbwetprop,	proportion of 2006 NLCD land cover: Emergent Herbaceous Wetlands

	usgsndvimean,	weighted-mean NDVI value (8-bit, 0-255); USGS EarthExplorer

	primary,	primary road density (km/km2)

	secondary,	secondary road density (km/km2)



####DATA-SPECIFIC INFORMATION FOR: BlackBeaIR_S2Dataset.xlsx

1. Number of variables: 24

2. Number of cases/rows: 2,026

3. Variable List: 

	ID,		Unique ID for all data (i.e., bear incident reports and random units)

	recordnum,	Bear Report Number - ID number from MDNR database for bear incident reports

	randid,		Unique ID for random units

	hbc,		response variable: 1 = bear incident reports; 0 = random units

	region,		regional location: UP = Upper Peninsula; LP = Lower Peninsula

	centroidx,	X UTM of section centroids

	centroidy,	Y UTM of section centroids

	buffarea,	Area of clipped buffer (m^2)

	waterprop,	proportion of 2006 NLCD land cover: Open Water

	opendevprop,	proportion of 2006 NLCD land cover: Developed, Open Space

	highdevprop,	proportion of 2006 NLCD land cover: Developed, High Intensity

	barrenprop,	proportion of 2006 NLCD land cover: Barren Land

	decidprop,	proportion of 2006 NLCD land cover: Deciduous Forest

	evergreenprop,	proportion of 2006 NLCD land cover: Evergreen Forest

	mixprop,	proportion of 2006 NLCD land cover: Mixed Forest

	shrubprop,	proportion of 2006 NLCD land cover: Shrub/Scrub

	herbprop,	proportion of 2006 NLCD land cover: Grassland/Herbaceous

	haypastprop,	proportion of 2006 NLCD land cover: Pasture/Hay

	cropprop,	proportion of 2006 NLCD land cover: Cultivated Crops

	woodywetprop,	proportion of 2006 NLCD land cover: Woody Wetlands

	herbwetprop,	proportion of 2006 NLCD land cover: Emergent Herbaceous Wetlands

	usgsndvimean,	weighted-mean NDVI value (8-bit, 0-255); USGS EarthExplorer

	primary,	primary road density (km/km2)

	secondary,	secondary road density (km/km2)
