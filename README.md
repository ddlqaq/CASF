1、The overall overview of the paper "Investigating the spatiotemporal pattern for the comprehensive accessibility of service facilities using location-based service big data (2016 to 2022)".
Understanding the dynamic development of urban service facilities is one of the critical issues related to urban development and change monitoring, urban health assessment, and the implementation assessment of service facility planning. However, the annual spatiotemporal variation for the comprehensive accessibility of service facilities (CASF) has not been routinely monitored adequately. Through LBS big data, establishing the evaluation framework for the CASF can reveal the spatiotemporal variance characteristics of urbanization and regional development. The evaluation framework that is based on the utility-improved gravity accessibility model focuses on the comprehensive index of service facilities and the CASF that refers to comprehensive potential and utility quality, respectively. We have employed four distinct spatiotemporal analysis and visualization methods to interpret the results of CASF in Nanjing from 2016 to 2022. Spatially, however, the CASF exhibited a pattern of multi-regional intersection and the coexistence of multiple centers. The emergence of new hotspots, as well as the persistence of existing ones, were predominantly located in the central part of Jiangbei. Sustained cold spots were mainly identified in the northern part of the Qixia District. The results can provide a scientific basis, and brand-new monitoring means for constituting regional planning policy of facilities in the human-oriented background of new-type urbanization.

2、The generation of data
	Collect and preprocess LBS data, including POI data, traffic travel data, and population distribution data, to generate multi-year statistical values at the block level. Then the CISF is introduced, and the accessibility model is enhanced to calculate the CASF.
 
3、Processing and opening of data.
	De-encryption of data is achieved through thinning and shifting at the ArcGIS node, and then converting it to json format through SuperMap, this process ensures the privacy protection of the data. The data can be opened through SuperMap.
 
4、The meaning of the field.
CASF：Comprehensive accessibility of service facilities.
CISF：Comprehensive index of service facilities.
POP：Population.
SUM_ Y17T16: Represents the total number of POIs of Type 16 within the unit for the year 2017

