
# Bath & North East Somerset Geographic Data

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Introduction](#introduction)
- [Subsetting](#subsetting)
- [Spatial Reference System](#spatial-reference-system)
- [Licencing & Attribution](#licencing-attribution)
- [How To Use These Files](#how-to-use-these-files)
- [Data Sources & Files](#data-sources--files)
	- [Bath & North East Somerset Council](#bath--north-east-somerset-council)
	- [Department for Communities & Local Government](#department-for-communities--local-government)
		- [Green Belt boundaries for England 2013-2014](#green-belt-boundaries-for-england-2013-2014)
	- [Department of Energy & Climate Change](#department-of-energy--climate-change)
		- [Domestic Electricity Consumption](#domestic-electricity-consumption)
		- [Domestic Gas Consumption](#domestic-gas-consumption)
	- [Department for the Environment, Food & Rural Affairs](#department-for-the-environment-food--rural-affairs)
		- [Strategic noise mapping 2012](#strategic-noise-mapping-2012)
	- [National Trust](#national-trust)
		- [Bath Skyline Walk Route](#bath-skyline-walk-route)
	- [Natural England](#natural-england)
	- [Office for Low Emission Vehicles](#office-for-low-emission-vehicles)
		- [National Charge Point Registry](#national-charge-point-registry)
	- [Office for National Statistics](#office-for-national-statistics)
		- [Administrative Boundaries](#administrative-boundaries)
		- [Output Area Classifications 2011](#output-area-classifications-2011)
		- [Indices of Mass Deprivation 2015](#indices-of-mass-deprivation-2015)
	- [Ordnance Survey](#ordnance-survey)
		- [Open Map Local](#open-map-local)
		- [Code-Point Open](#code-point-open)
	- [Police](#police)
		- [Street Level Crimes](#street-level-crimes)

<!-- /TOC -->

## Introduction

As part of our work at [Bath: Hacked](http://www.bathhacked.org) we try to publish all of our data in our [Datastore](https://data.bathhacked.org). While that goes some way to working with & presenting geographic data, much facility is lost. This repository is designed to make it easier to share, create and work with data which has a geographic basis.

We have collected together subsets of many national datasets & joined them together with geographic data, where necessary.

[Bath & North East Somerset Council](http://www.bathnes.gov.uk/) have also kindly provided us with some of their own data about the area.

**Feel free to submit pull requests.**

## Subsetting

Where needed, all files were subsetted (clipped) to the area of Bath & North East Somerset, using the file `os_boundary.geojson` or, where available in the data, using the ONS code for BANES (E06000022).

## Spatial Reference System

All files use the WGS 84 / EPSG:4326 spatial reference system. This is to provide maximum compatibility with common web-based mapping tools.

## Licencing & Attribution

Where attribution is marked as **Mandatory** you **must** display the relevant attribution prominently alongside your use of the data. Typically by overlaying on a map or, where impractical, via a prominent link.

Where attribution is marked as **Optional** we strongly encourage you to include the attribution. It's only fair to credit the source.

For bonus points we'd like it if you'd add a **"Powered by Bath: Hacked"** attribution.

While we have endeavoured to provide consistent & accurate information about licencing & attribution of the data, we advise that you perform your own checks & due diligence in using the data, especially if you use the data commercially. Your use of this data is at your own risk.

We believe to the best of our knowledge that all data can be published as open data. If you believe that we have made an error please contact us immediately to remedy the situation.

## How To Use These Files

The files provided in this repository are intended for use with web-based mapping tools and geographical information systems.

Some recommended web tools include [CartoDB](https://cartodb.com/), [Mapbox](https://www.mapbox.com/), [Leaflet](http://leafletjs.com/), [OpenLayers](http://openlayers.org/), [Google Maps](https://www.google.co.uk/maps).

For manipulating the files we strongly recommend use of [QGIS](http://www.qgis.org/en/site/) software. It is tremendously powerful & available for many platforms.

## Data Sources & Files

### Bath & North East Somerset Council

| Item        | Description                                                                                                                                                |
|:------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                  |
| Source      | Provided by [Bath & North East Somerset Council](http://www.bathnes.gov.uk/)                                                                               |
| Retrieved   | 2016-01                                                                                                                                                    |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                           |
| Attribution | **(Mandatory)** Contains OS data &copy; Crown copyright and database right \[year\]<br>**(Mandatory)** Data provided by Bath & North East Somerset Council |

| File                                   | Description                          |
|:---------------------------------------|:-------------------------------------|
| banes_circuit_of_bath_walk.geojson     | Circuit of Bath Walk route           |
| banes_conservation_ar.geojson          | Conservation areas                   |
| banes_green_belt.geojson               | Green belt land                      |
| banes_gss_allotments.geojson           | Allotments                           |
| banes_gss_amenity_grass.geojson        | Amenity grass areas                  |
| banes_gss_churchyards_cem.geojson      | Churchyards & cemeteries             |
| banes_gss_education_greenspace.geojson | Education green space                |
| banes_gss_natural_greenspace.geojson   | Natural green space                  |
| banes_gss_outdoorsport_fixed.geojson   | Fixed outdoor sport areas            |
| banes_gss_outdoorsport_pitches.geojson | Outdoor sport pitches                |
| banes_gss_outdoorsport_private.geojson | Private outdoor sport areas          |
| banes_gss_parks_recreation.geojson     | Park & recreational areas            |
| banes_gss_playspace_children.geojson   | Play spaces for children             |
| banes_gss_playspace_youth.geojson      | Play spaces for youth                |
| banes_landscharareas.geojson           | Rural landscape character areas      |
| banes_local_shops.geojson              | Local shops                          |
| banes_prow_bath.geojson                | Public rights of way in Bath         |
| banes_prow_somerset.geojson            | Public rights of way in Somerset     |
| banes_tpos.geojson                     | Tree preservation orders & TPO areas |


### Department for Communities & Local Government

#### Green Belt boundaries for England 2013-2014

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | dclg_greenbelt_2013_14.geojson                                                                                                                                                                                              |
| Source      | [Open Data Communities - Greenbelt](http://opendatacommunities.org/data/geography/greenbelt)                                                                                                                                |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | **(Mandatory)** Contains OS data &copy; Crown copyright and database right \[year\]<br>(Optional) Data provided by Department for Communities & Local Government                                                            |
| See also    | [Green Belt boundaries for England have been released as open data](http://mapgubbins.tumblr.com/post/99635819470/green-belt-boundaries-for-england-have-been)                                                              |

### Department of Energy & Climate Change

#### Domestic Electricity Consumption

Domestic electricty consumption 2013 by postcode.

| Item        | Description                                                                                                                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | decc_dom_elec_pc_2013.geojson                                                                                                                                                                                   |
| Source      | [Postcode level electricity estimates:2013 (experimental)](https://www.gov.uk/government/statistics/postcode-level-electricity-estimates-2013-experimental)                                                     |
| Retrieved   | 2016-01-24                                                                                                                                                                                                      |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                                                                |
| Attribution | (Optional) Data provided by Department of Energy & Climate Change                                                                                                                                               |
| See also    | [Sub-national electricity and gas consumption statistics](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/388960/Subnational_electricity_and_gas_consumption_summary_report_2013.pdf) |

#### Domestic Gas Consumption

| Item        | Description                                                                                                                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | decc_dom_gas_pc_2013.geojson                                                                                                                                                                                    |
| Source      | [Postcode level gas estimates: 2013 (experimental)](https://www.gov.uk/government/statistics/postcode-level-gas-estimates-2013-experimental)                                                                    |
| Retrieved   | 2016-01-24                                                                                                                                                                                                      |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                                                                |
| Attribution | (Optional) Data provided by Department of Energy & Climate Change                                                                                                                                               |
| See also    | [Sub-national electricity and gas consumption statistics](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/388960/Subnational_electricity_and_gas_consumption_summary_report_2013.pdf) |

### Department for the Environment, Food & Rural Affairs

#### Strategic noise mapping 2012


| Item        | Description                                                                                                        |
|:------------|:-------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                          |
| Source      | [Open data: strategic noise mapping](https://www.gov.uk/government/publications/open-data-strategic-noise-mapping) |
| Retrieved   | 2016-01-20                                                                                                         |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                   |
| Attribution | (Optional) Data provided by Department for the Environment, Food & Rural Affairs                                   |

| File                        | Description                                                                                         |
|:----------------------------|:----------------------------------------------------------------------------------------------------|
| defra_noise_rd_lden.geojson | 24 hour annual average road noise level with separate weightings for the evening and night periods. |
| defra_noise_rd_lngt.geojson | Night time annual average road noise level results in dB, where night is defined as 2300 - 0700.    |
| defra_noise_rd_lq16.geojson | Annual average road noise levels for the 16-hour period between 0700 – 2300.                        |
| defra_noise_rl_lden.geojson | 24 hour annual average rail noise level with separate weightings for the evening and night periods. |
| defra_noise_rl_lngt.geojson | Night time annual average rail noise level results in dB, where night is defined as 2300 - 0700.    |
| defra_noise_rl_lq16.geojson | Annual average rail noise levels for the 16-hour period between 0700 – 2300.                        |

#### Risk of Flooding from Rivers & Sea

| Item        | Description                                                                                                                       |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------|
| Files       | defra_rofrs.geojson                                                                                                               |
| Source      | [Environment Agency Geostore](http://www.geostore.com/environment-agency/WebStore?xml=environment-agency/xml/ogcDataDownload.xml) |
| Retrieved   | 2016-01-24                                                                                                                        |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                  |
| Attribution | (Optional) Data provided by Environment Agency                                                                                    |

### National Trust

#### Bath Skyline Walk Route

| Item        | Description                                                                      |
|:------------|:---------------------------------------------------------------------------------|
| Files       | nt_bath_skyline.geojson                                                          |
| Source      | Provided by BANESC                                                               |
| Retrieved   | 2016-01-25                                                                       |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) |
| Attribution | (Optional) Data provided by National Trust                                       |

### Natural England

| Item        | Description                                                                                                                                                 |
|:------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                   |
| Source      | [Environment Agency - Download Environmental Open Data](http://www.geostore.com/environment-agency/WebStore?xml=environment-agency/xml/ogcDataDownload.xml) |
| Retrieved   | 2016-01-25                                                                                                                                                  |
| Licence     | [OGL NE-OS](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/391764/OGL-NE-OS.pdf)                                                 |
| Attribution | **(All Mandatory)**<br>&copy; Natural England copyright.<br> Contains Ordnance Survey data &copy; Crown copyright and database right \[year\]               |

| File                                  | Description                                                                                                                                                                                                                                                                            |
|:--------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ne_ag_landc_p1988.geojson             | Agricultural Land Classification                                                                                                                                                                                                                                                       |
| ne_agricultural_land_class.geojson    | Agricultural Land Classification Post 1988                                                                                                                                                                                                                                             |
| ne_ancient_woodland.geojson           | Ancient Woodlands                                                                                                                                                                                                                                                                      |
| ne_aonb.geojson                       | Areas of Outstanding Natural Beauty                                                                                                                                                                                                                                                    |
| ne_crow_access_layer.geojson          | Countryside and Rights of Way Act 2000                                                                                                                                                                                                                                                 |
| ne_crow_s15_land.geojson              | Countryside and Rights of Way Act 2000 - Section 15 Land                                                                                                                                                                                                                               |
| ne_local_nature_reserves.geojson      | Local Nature Reserves<br>Local Nature Reserves (LNRs) are a statutory designation made under Section 21 of the National Parks and Access to the Countryside Act 1949 by principal local authorities.                                                                                   |
| ne_national_trails.geojson            | National Trails                                                                                                                                                                                                                                                                        |
| ne_special_areas_conservation.geojson | Special Areas of Conservation<br>A Special Area of Conservation (SAC) is the land designated under Directive 92/43/EEC on the Conservation of Natural Habitats and of Wild Fauna and Flora.                                                                                            |
| ne_special_protection_areas.geojson   | Special Protection Areas<br>A Special Protection Area (SPA) is the land classified under Directive 79/409 on the Conservation of Wild Birds.                                                                                                                                           |
| ne_sssi.geojson                       | Sites of Special Scientific Interest<br>SSSI are the finest sites for wildlife and natural features in England, supporting many characteristic, rare and endangered species, habitats and natural features the land notified as an SSSI under the Wildlife and Countryside Act (1981). |

### Office for Low Emission Vehicles

#### National Charge Point Registry

Publicly Accessible PiV (plugged-in vehicle) Charge Points within the UK.

| Item        | Description                                                                                  |
|:------------|:---------------------------------------------------------------------------------------------|
| File        | olev_ncpr_charge_points.geojson                                                              |
| Source      | [National Charge Point Registry](https://data.gov.uk/dataset/national-charge-point-registry) |
| Retrieved   | 2016-01-25                                                                                   |
| API         | http://chargepoints.dft.gov.uk/api/help                                                      |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)             |
| Attribution | (Optional) Data provided by Office for Low Emission Vehicles                                 |

### Office for National Statistics

#### Administrative Boundaries

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                                                                                   |
| Source      | [ONS Geoportal](https://geoportal.statistics.gov.uk/geoportal/catalog/content/filelist.page?&pos=3&cat=#BD)<br>(If you are thrown to the home page click on Downloads > Boundaries)                                         |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | **(All Mandatory)**<br>Contains National Statistics data &copy; Crown copyright and database right \[year\]<br>Contains OS data &copy; Crown copyright and database right \[year\]                                          |

| File                  | Description                            |
|:----------------------|:---------------------------------------|
| ons_lsoa_2011.geojson | 2011 Lower Super Output Areas (LSOAs)  |
| ons_msoa_2011.geojson | 2011 Middle Super Output Areas (MSOAs) |
| ons_oa_2011.geojson   | 2011 Output Areas (OAs)                |
| ons_ward_2011.geojson | 2011 Wards                             |
| ons_wmc_2014.geojson  | 2014 Westminster Constituencies        |
| ons_wz_2011.geojson   | 2011 Workplace Zones                   |

#### Output Area Classifications 2011

Area classifications group together geographic areas according to key characteristics common to the population in that grouping. These groupings are called clusters and are derived using census data. The area classifications are hierarchical classifications, consisting of three tiers: Supergroups, Groups and Subgroups.

| Item        | Description                                                                                                                                                                                                                                                                                                                                                                                                                    |
|:------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | ons_oac_2011.geojson                                                                                                                                                                                                                                                                                                                                                                                                           |
| Source      | [2011 Area Classifications](http://www.ons.gov.uk/ons/guide-method/geography/products/area-classifications/ns-area-classifications/ns-2011-area-classifications/index.html)                                                                                                                                                                                                                                                    |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)<br>[OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)<br>[ODbL](http://opendatacommons.org/licenses/odbl/)                                                                                                                                              |
| Attribution | **(All Mandatory)**<br>Contains National Statistics data &copy; Crown copyright and database right \[year\].<br>Contains ONS data &copy; Crown copyright and database right \[year\].<br>Contains NRS data &copy; Crown copyright and database right \[year\].<br>Contains NISRA data &copy; Crown copyright and database right \[year\].<br>Contains Ordnance Survey data &copy; Crown copyright and database right \[year\]. |
| Granularity | Output Area                                                                                                                                                                                                                                                                                                                                                                                                                    |

#### Indices of Mass Deprivation 2015

Statistics on relative deprivation in small areas in BANES. For full descriptions of fields see below.

| Item        | Description                                                                                                         |
|:------------|:--------------------------------------------------------------------------------------------------------------------|
| File        | ons_imd_2015.geojson                                                                                                |
| Source      | [English Indices of deprivation 2015](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2015) |
| Retrieved   | 2016-01-17                                                                                                          |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                    |
| Attribution | (Optional) Data provided by DCLG & ONS.                                                                             |
| Granularity | Lower Super Output Area                                                                                             |

| Field      | Description                                                                                        |
|:-----------|:---------------------------------------------------------------------------------------------------|
| lsoa11cd   | LSOA code (2011)                                                                                   |
| lsoa11nm   | LSOA name (2011)                                                                                   |
| lsoa11nmw  | LSOA name (2011)                                                                                   |
| lsoa name  | LSOA name (2011)                                                                                   |
| local auth | Local Authority District code (2013)                                                               |
| local aut2 | Local Authority District name (2013)                                                               |
| index of m | Index of Multiple Deprivation (IMD) Score                                                          |
| index of 2 | Index of Multiple Deprivation (IMD) Rank (where 1 is most deprived)                                |
| index of 3 | Index of Multiple Deprivation (IMD) Decile (where 1 is most deprived 10% of LSOAs)                 |
| income sco | Income Score (rate)                                                                                |
| income ran | Income Rank (where 1 is most deprived)                                                             |
| income dec | Income Decile (where 1 is most deprived 10% of LSOAs)                                              |
| employment | Employment Score (rate)                                                                            |
| employmen2 | Employment Rank (where 1 is most deprived)                                                         |
| employmen3 | Employment Decile (where 1 is most deprived 10% of LSOAs)                                          |
| education, | Education, Skills and Training Score                                                               |
| education2 | Education, Skills and Training Rank (where 1 is most deprived)                                     |
| education3 | Education, Skills and Training Decile (where 1 is most deprived 10% of LSOAs)                      |
| health dep | Health Deprivation and Disability Score                                                            |
| health de2 | Health Deprivation and Disability Rank (where 1 is most deprived)                                  |
| health de3 | Health Deprivation and Disability Decile (where 1 is most deprived 10% of LSOAs)                   |
| crime scor | Crime Score                                                                                        |
| crime rank | Crime Rank (where 1 is most deprived)                                                              |
| crime deci | Crime Decile (where 1 is most deprived 10% of LSOAs)                                               |
| barriers t | Barriers to Housing and Services Score                                                             |
| barriers 2 | Barriers to Housing and Services Rank (where 1 is most deprived)                                   |
| barriers 3 | Barriers to Housing and Services Decile (where 1 is most deprived 10% of LSOAs)                    |
| living env | Living Environment Score                                                                           |
| living en2 | Living Environment Rank (where 1 is most deprived)                                                 |
| living en3 | Living Environment Decile (where 1 is most deprived 10% of LSOAs)                                  |
| income dep | Income Deprivation Affecting Children Index (IDACI) Score (rate)                                   |
| income de2 | Income Deprivation Affecting Children Index (IDACI) Rank (where 1 is most deprived)                |
| income de3 | Income Deprivation Affecting Children Index (IDACI) Decile (where 1 is most deprived 10% of LSOAs) |
| income de4 | Income Deprivation Affecting Older People (IDAOPI) Score (rate)                                    |
| income de5 | Income Deprivation Affecting Older People (IDAOPI) Rank (where 1 is most deprived)                 |
| income de6 | Income Deprivation Affecting Older People (IDAOPI) Decile (where 1 is most deprived 10% of LSOAs)  |
| children a | Children and Young People Sub-domain Score                                                         |
| children 2 | Children and Young People Sub-domain Rank (where 1 is most deprived)                               |
| children 3 | Children and Young People Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                |
| adult skil | Adult Skills Sub-domain Score                                                                      |
| adult ski2 | Adult Skills Sub-domain Rank (where 1 is most deprived)                                            |
| adult ski3 | Adult Skills Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                             |
| geographic | Geographical Barriers Sub-domain Score                                                             |
| geographi2 | Geographical Barriers Sub-domain Rank (where 1 is most deprived)                                   |
| geographi3 | Geographical Barriers Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                    |
| wider barr | Wider Barriers Sub-domain Score                                                                    |
| wider bar2 | Wider Barriers Sub-domain Rank (where 1 is most deprived)                                          |
| wider bar3 | Wider Barriers Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                           |
| indoors su | Indoors Sub-domain Score                                                                           |
| indoors s2 | Indoors Sub-domain Rank (where 1 is most deprived)                                                 |
| indoors s3 | Indoors Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                                  |
| outdoors s | Outdoors Sub-domain Score                                                                          |
| outdoors 2 | Outdoors Sub-domain Rank (where 1 is most deprived)                                                |
| outdoors 3 | Outdoors Sub-domain Decile (where 1 is most deprived 10% of LSOAs)                                 |
| total popu | Total population: mid 2012 (excluding prisoners)                                                   |
| dependent  | Dependent Children aged 0-15: mid 2012 (excluding prisoners)                                       |
| population | Population aged 16-59: mid 2012 (excluding prisoners)                                              |
| older popu | Older population aged 60 and over: mid 2012 (excluding prisoners)                                  |
| working ag | Working age population 18-59/64: for use with Employment Deprivation Domain (excluding prisoners)  |



### Ordnance Survey

#### Open Map Local


| Item        | Description                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                       |
| Source      | [OS Open Map - Local](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-map-local.html) |
| Retrieved   | 2016-01-21                                                                                                      |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                                    |
| Attribution | **(Mandatory)** Contains OS data &copy; Crown copyright \[and database right\] \[year\]                         |

| File                           | Description                         |
|:-------------------------------|:------------------------------------|
| os_boundary.geojson            | Bath & North East Somerset boundary |
| os_buildings.geojson           | Buildings                           |
| os_electricity_lines.geojson   | Electricity lines                   |
| os_functional_sites.geojson    | Functional sites                    |
| os_important_buildings.geojson | Important buildings                 |
| os_parishes.geojson            | Parishes                            |
| os_place_names.geojson         | Place names                         |
| os_rail_track.geojson          | Rail track                          |
| os_roads.geojson               | Roads                               |
| os_settlements.geojson         | Settlements                         |
| os_surface_water_area.geojson  | Surface water polygons              |
| os_surface_water_line.geojson  | Surface water lines                 |
| os_woodland.geojson            | Woodland                            |

#### Code-Point Open

Postcode centroids within BANES, with administrative area lookup.

| Item        | Description                                                                                                                                                                                                                                                                |
|:------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| File        | os_postcodes.geojson                                                                                                                                                                                                                                                       |
| Source      | [Code-Point Open](https://www.ordnancesurvey.co.uk/business-and-government/products/code-point-open.html)                                                                                                                                                                  |
| Retrieved   | 2016-01-21                                                                                                                                                                                                                                                                 |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                                                                                                                                                                                               |
| Attribution | **(All Mandatory)**<br>Contains OS data &copy; Crown copyright \[and database right\] \[year\]<br>Contains Royal Mail data &copy; Royal Mail copyright and Database right \[year\]<br>Contains National Statistics data &copy; Crown copyright and database right \[year\] |

### Police

#### Street Level Crimes

| Item        | Description                                                                                                                                                                |
|:------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | police_crimes.geojson                                                                                                                                                      |
| Source      | [Police API](https://data.police.uk/docs/) via [BANES Street Level Crimes Dataset](https://data.bathhacked.org/Government-and-Society/BANES-Street-Level-Crimes/cujy-zqnk) |
| Retrieved   | 2016-01-25                                                                                                                                                                 |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                           |
| Attribution | (Optional) Date provided by data.police.uk                                                                                                                                 |
