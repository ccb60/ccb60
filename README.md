# State of Casco Bay 2020 Github Archive

## Introduction
This collection of repositories is principally a working archive of data
**sources**, **analysis**, and **graphics** used in preparation of Casco
Bay Estuary Partnership's 2020 **State of Casco Bay** report.

The primary purpose of the archive is to provide transparency with regards to
data sources and data analyses used to conduct the 2020 **State of Casco Bay**
review. A secondary purpose is to act as an archive of methods used for 
analyses of locally available environmental data, to facilitate future projects.

This is currently a working archive.  It contains only a portion of the data
and code used to prepare the **State of Casco Bay** Report.  Some repositories
are in active development, others are complete, and more or less static 
at this time. Some sections remain blank, as no relevant code has been used in
developing relevant sections of the Report.  These remaining sections will be
populated gradually as analyses are finalized, and time permits.

## Repository Contents
<a name="Contents"></a>
## State of Casco Bay 2020
The 2020 State of Casco Bay Report is structured into multiple Chapters.
Each chapter is based on one to several data sources.  The Github
repositories are built around the data sources (with some variation).
The following section provides a cross-walk from topics to specific
repositories.

### A. DRIVERS AND STRESSORS; "WHAT'S AFFECTING THE BAY?"  
*  A1	Population and Land Use  
    *  Population / Census  
	*  Land Use  
*  A3	Stormwater  
    *  Ten years of water quality monitoting data from Long Creek, 
	  provided by the Long Creek Watershed Management District. .......... [LCWMD_Monitoring](https://github.com/ccb60/LCWMD_Monitoring)
    *  Geospatial data on locations of areas formally included in the
       "Municipal Seperate Storm Sewer System" or MS4 program. .......... 
	   [MS4-Regulated_Areas](https://github.com/ccb60/MS4-Regulated_Areas)  
*  A4	Combined Sewer Overflows  
    *  Maine DEP, City of Portland, and Portland Water District data
		on CSO discharges. .......... 
		[Casco_Bay_CSOs](https://github.com/ccb60/Casco_Bay_CSOs)  
*  A5 	Inland Water Quality  
    *  Accessing Maine Department of Environmental Protection (DEP)
	   biomonitoring data over the internet .......... 
	   [access_biomonitoring](https://github.com/ccb60/access_biomonitoring)  
    *  Analyzing DEP  Stream Invertebrate biomonitoring data. .......... 
	   [Analysis_Biomonitoring](https://github.com/ccb60/Analysis_Biomonitoring) 
    *  Maine DEP geospatial information on impaired waters.......... 
	   [Impaired_waters](https://github.com/ccb60/Impaired_waters)	 
    *  Water Quality in Casco Bay Watershed Lakes ..........
	   [Lake_Water_Quality](https://github.com/ccb60/Lake_Water_Quality)  
	*  Representing data from Portland Water District's Lake 
	   Vulnerability Index. .......... 
	   [PWD_Lake_WQ_Index](https://github.com/ccb60/PWD_Lake_WQ_Index)
    *  Geographic Information on Maine Lakes. ..........
	   [Maine_Lakes_MIDAS](https://github.com/ccb60/Maine_Lakes_MIDAS)  
    *  Presumpscot River Water Quality Monitoring Data. ..........
	   [Presumpscot_Water_Quality](https://github.com/ccb60/Presumpscot_WQ)  
*  A6	Climate Change  
    *  Analysis of eight decades of weather data from the Portland Jetport.
	   Data accessed through NOAA online data APIs.  ..........
	   [CDO-Portland-Jetport](https://github.com/ccb60/CDO-Portland-Jetport)  
	*  Analysis of nearly a century of sea levels at the Portland
	   tide gage and forcasts of future tidal flooding frequencies. .......... 
	   [Portland-SLR](https://github.com/ccb60/Portland-SLR)  
*  A7	Invasive Species 
    *  Preliminary review of MIMIC data on prevalence of selected invasive
	   marine invertebrates in Casco Bay. .......... 
	   [CB_Invasives](https://github.com/ccb60/CB_Invasives)
### B. CONDITION OF THE BAY; "HOW IS THE BAY DOING?"	
*  B8	Bay Water Quality  
    * Friends of Casco Bay (FOCB) water quality monitoting data .......... 
	FOCB_Data](https://github.com/ccb60/FOCB_Data)  
*  B9	Nutrients  
*  B10	Aquatic Connectivity  
*  B11	Eelgrass  
*  B12	Living Resources  
*  B13	Coastal Acidification  
    * Analysis of data collected by UNH, on behalf of CBEP, measuring
	OA-related parameters at the Southern Maine Community College pier,
	in South Portland.  .......... 
	[CBEP_OA](https://github.com/ccb60//CBEP_OA)  
	* Analysis of a four years of Friends of Casco Bay (FOCB) water quality
	data that pertians to ocean acidification.  Data is from data loggers
	deployed off Chebeague Island. .......... 
	[FOCB_OA](https://github.com/ccb60//FOCB_OA)  
*  B14	Swimming Beaches and Shellfish Beds  
    *  Maine Department of Marine Resources (DMR) data on bacteria in
	shellfish. .......... 
	[Shellfish_Bacteria](https://github.com/ccb60//Shellfish_Bacteria)  
	*  Maine Beaches Program data on bacteria at monitored beaches. ..........  
	[Beaches_Bacteria](https://github.com/ccb60//Beaches_Bacteria)  
*  B15	Toxics  
    * CBEP historical data on toxics in Casco Bay Sediments. .......... 
	[CBEP_Sediments](https://github.com/ccb60//CBEP_Sediments)  
	* Maine Surface Water Ambient Toxics (SWAT) data on toxic
	contaminants in blue mussels. ..........
	[SWAT_Mussels](https://github.com/ccb60//SWAT_Mussels)  
	* Portland Harbor Commission data on toxic contaminants in Portland
	harbor sediments. .......... 
	[PortlandHarborToxics](https://github.com/ccb60//PortlandHarborToxics)  
	* Maine Board of Pesticides Control data on pyrethroid pesticides in
	intertidal sediments. .......... 
	[BPC_Pesticides](https://github.com/ccb60//BPC_Pesticides)  

### C. HUMAN CONNECTIONS; "WHY DO WE CARE?"	  
*  C16	Conserved Lands  
*  C17	Coastal Habitats  
*  C18	Economics  
    *  Analysis of recent data on number of cruise ships and cruise ship
	visitors visiting Portland, Maine. .......... 
	[PortlandCruiseShips](https://github.com/ccb60//PortlandCruiseShips)  
*  C19	Education  
*  C20	Stewardship  
*  C21	Climate Preparedness  

### General Data Sources and Information
*  Watershed Boundary
*  Impervious Cover
*  NHD hydrography
*  Others

### Reuseable Code and Utilities
*  Small package to facilitate use of maximum likelihood estimates of 
   (unobserved) left censored values in left censored data, such as
   observations of concentrations of contaminants or bacteria.
   ..........  [LCensMeans](https://github.com/ccb60//LCensMeans)
*  Utility package to facilitate uniformaty in graphic design for 
   the 2020 **State of Casco Bay** report.  Defines a default
   graphic style, and six preferred colors.  ..........  [CBEP_graphics](https://github.com/ccb60//CBEP_graphics)

## Side Projects
*  Analysis of the relationship between measured chloride concentrations
   and observed conductivity in Long Creek. Conducted on behalf of the 
   Long Creek Watershed Management District, specifically to evaluate
   the impact of outliers on the accuracy of chloride estimates derived
   from high frequency conductivity data.    ..........  [LCWMD_2020_Chloride](https://github.com/ccb60/LCWMD_2020_Chloride)  
*  Analysis of microhabitat frequencies in a recently restored and a 
   reference reach reach of Long Creek.  Conducted on behalf of the 
   Long Creek Watershed Management District.  ..........  [LCWMD_2020_microhabitat](https://github.com/ccb60/LCWMD_2020_microhabitat)  
*  Exploratory code looking at OA monitoring data from multiple 
   National Estuary Programs.  ..........  [NEP_OA](https://github.com/ccb60//NEP_OA)
*  Notebooks examining thermodynamic relationships among OA
   parameters, temperature and salinity., especially the relationship
   between pCO~2~, [CO~2~] and temperature. Developed to help us
   understand the underlying chemistry for the OA chapter of
   **State of Casco Bay**. ..........  [OA_Calculations](https://github.com/ccb60//OA_Calculations)
*  Derivation of spatially-balanced sampling design for studying presence
   of pesticides in wells near Maine's iconic wild blueberry fields.
   Project conducted  to assist Maine's Board of Pesticides Control, which
   conducts surveillance of groundwater for pesticides every few years.
   Surveillance near blueberry fields has long been a priority because of 
   a combination of highly permiable soild and sensitive aquatic environments
   in the part of the state where blueberries are grown commercially.
   ..........  [Blueberry_Sampling](https://github.com/ccb60//Blueberry_Sampling)
*  Small Python (3) program providing a simple GUI for playing streaming video
   on a Raspberry Pi.  Simplistic program with limited functionality. Can
   also be used on a Windowns computer.  not tested on Apple or other Unix
   systems. ..........  [radiostreamer](https://github.com/ccb60//radiostreamer)
*  Wastewater Disposal 
    * Data on wastewater discharges from major Casco Bay Wastewater Treatment  
	  Facilites, via Maine DEP. (prelimnary analysis for chapter that was
	  dropped from State of Casco Bay). .......... 
	  [WWTF_Discharges](https://github.com/ccb60/WWTF_Discharges)  


## Description of Contents
Most repositories emphasize R notebooks, as a way to intersperse 
R data analysis code with commentary and results of analyses.  Some also 
make use of Python (3), principally for data access from online repositories. 
In some cases, data preparation relied on non-open source tools, especially 
Microsoft Excel and ESRI's ArcGIS.  Where included, spreadsheet and GIS files
are either provided as is (as *.xlsx files), use industry standard formats(e.g., 
shapefiles for geospatial data) or are provided as CSV files.

Original data files are in the format in which they were recieved, which
included spreadsheets, CSV files, tab delimited text files, shapefiles,
XML files, and more.  Derived data files are principally presented as CSV files,
although some geospatial data are provided in other formats.

## Data Provenance and Repository Structure
Wherever possible, we have included raw data sources, or (more rarely)
code or instructions for how to access raw data. Orignal data, and often
related metadata or access code, are located in the **"Original_Data"** folder
of each repository.  Our goal, not 100% achieved as yet, is to document 
sources of data, and "show our work". Therefore, "cleaned", "rearranged"
or "transformed" data (on which subsequent analyses are based) are included in a
**"Derived_Data"** folder, often with documentation of data review and QA/QC.
Formal statistical analysis (if deamed necessary) is in an **"Analysis"** folder,
while code generating draft **State of Casco Bay** graphics are in the
**"Graphics"** folder (usually with final drafts in a subfolder named 
**"figures"**).  Not all four folders are present in each repository,
and a few repositories contain additional folders, where that made the 
organization of information a bit easier to follow.

## About Casco Bay and Casco Bay Estuary Partnership
Casco Bay Estuary Partnership (CBEP) is one of twenty eight National
Estuary Programs.  Each National Estuary Program is a locally led,
non-regulatory, science-based collaborative organization that works
to address challenges facing Estuaries of National Significance and
the communities on their shores.

CBEP works with dozens of partner organizations, including federal, state, and local
government; colleges and universities; non-profits and interest groups; local
businesses and private citizens on behalf of Casco Bay, a coastal embayment in
southern Maine. 

You can find more information about CBEP on our [web site](http://cascobayestuary.org).

Casco Bay is approximately 160 square miles in size, dotted with hundreds of
islands. The roughly 980 square mile watershed is long and narrow, extending 
as far as the mountains of Western Maine.  Fourty eight towns and cities touch
the watershed.  Twelve are coastal communities with marine shorelines. Our largest
urban center is Portland, Maine, located on the South West corner of the Bay.
Dozens of lakes dot the watershed including Sebago Lake, Maine's deepest, and second
largest.  The climate is cool-temperate. On the order of a meter of 
precipitation falls in most years, spread more or less evenly over twelve months.
Most of that precipitation falls as rain, but snow predominates in the winter
months.

The Casco Bay watershed represents on the order of four and a half  percent of the
land area of Maine, but close to a quarter of the state's population, and a third of 
employment and economic activity.  The regional economy is dominated by the service
economy of Portland, but marine-related industries represents about four percent of
jobs and economic activity in the region. That share is substantially higher for our
island and peninsula communities.

Casco Bay supports a robust lobster fishery, substantial clam harvests, a growing
aquaculture industry(principally blue mussels, american oyster, and sugar kelp). 
Portland harbor handles both container ships and oil tankers. Land-based businesses
on the waterfront support Maine's fishing industry, but also support a burgeoning 
restaurant scene.  In fact, tourism (including restuarants, lodging, cruise ships,
tour operations, etc., but omitting property rentals and real estate) represents
close to three quarters of all marine-related economic activity of the region.

## The Team
The primary author of this archive is Curtis C. Bohlen, Director and lead
scientist of the Casco Bay Estuary Partnership. Other members of the CBEP
staff, including Marti Blair, Victoria Boundy, Matthew Craig, and and Thomas
Gilmartin have made additional contributions.

You can find more informaiton about us at the [CBEP website](http://cascobayestuary.org).

---
[Back up to to Repository Contents](# Contents)



