
# Bath & North East Somerset Geographic Data

- [Introduction](#introduction)
- [Subsetting](#subsetting)
- [Spatial Reference System](#spatial-reference-system)
- [Licencing & Attribution](#licencing--attribution)
- [How To Use These Files](#how-to-use-these-files)
- [Data Sources & Files](#data-sources--files)
	- [Bath & North East Somerset Council](#bath--north-east-somerset-council)
		- [BANES INSPIRE](#banes-inspire)
	- [Bath: Hacked](#bath-hacked)
		- [Accessible Bath Project](#accessible-bath-project)
	- [Department for Communities & Local Government](#department-for-communities--local-government)
		- [Green Belt boundaries for England 2013-2014](#green-belt-boundaries-for-england-2013-2014)
	- [Department of Energy & Climate Change](#department-of-energy--climate-change)
		- [Domestic Electricity Consumption](#domestic-electricity-consumption)
		- [Domestic Gas Consumption](#domestic-gas-consumption)
	- [Department for the Environment, Food & Rural Affairs](#department-for-the-environment-food--rural-affairs)
		- [Strategic noise mapping 2012](#strategic-noise-mapping-2012)
		- [Risk of Flooding from Rivers & Sea](#risk-of-flooding-from-rivers--sea)
	- [Historic England](#historic-england)
		- [Listed Buildings](#listed-buildings)
		- [Scheduled Monuments](#scheduled-monuments)
	- [National Trust](#national-trust)
		- [Bath Skyline Walk Route](#bath-skyline-walk-route)
	- [Natural England](#natural-england)
	- [Ofcom](#ofcom)
		- [Broadband Survey June 2013](#broadband-survey-june-2013)
		- [Connected Nations 2016](#connected-nations-2016)
	- [Office for Low Emission Vehicles](#office-for-low-emission-vehicles)
		- [National Charge Point Registry](#national-charge-point-registry)
	- [Office for National Statistics](#office-for-national-statistics)
		- [Administrative Boundaries](#administrative-boundaries)
		- [Census 2011](#census-2011)
		- [Output Area Classifications 2011](#output-area-classifications-2011)
		- [Indices of Mass Deprivation 2015](#indices-of-mass-deprivation-2015)
	- [Ordnance Survey](#ordnance-survey)
		- [Open Map Local](#open-map-local)
		- [Open Greenspace](#open-greenspace)
		- [Code-Point Open](#code-point-open)
		- [Terrain 50](#terrain-50)
	- [Police](#police)
		- [Street Level Crimes](#street-level-crimes)

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

You **must** display the relevant attribution prominently alongside your use of the data. Typically by overlaying on a map or, where impractical, via a prominent link.

For bonus points we'd like it if you'd add a **"Powered by Bath: Hacked"** attribution.

While we have endeavoured to provide consistent & accurate information about licencing & attribution of the data, we advise that you perform your own checks & due diligence in using the data, especially if you use the data commercially. Your use of this data is at your own risk.

We believe to the best of our knowledge that all data can be published as open data. If you believe that we have made an error please contact us immediately to remedy the situation.

## How To Use These Files

The files provided in this repository are intended for use with web-based mapping tools and geographical information systems.

Some recommended web tools include [CartoDB](https://cartodb.com/), [Mapbox](https://www.mapbox.com/), [Leaflet](http://leafletjs.com/), [OpenLayers](http://openlayers.org/), [Google Maps](https://www.google.co.uk/maps).

For manipulating the files we strongly recommend use of [QGIS](http://www.qgis.org/en/site/) software. It is tremendously powerful & available for many platforms.

## Data Sources & Files

### Bath & North East Somerset Council

| Item        | Description                                                                                                                |
|:------------|:---------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                  |
| Source      | Provided by [Bath & North East Somerset Council](http://www.bathnes.gov.uk/)                                               |
| Retrieved   | 2016-01 unless specified                                                                                                                   |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                           |
| Attribution | Contains OS data &copy; Crown copyright and database right \[year\]<br>Data provided by Bath & North East Somerset Council |

| File                                          | Description                          |
|:----------------------------------------------|:-------------------------------------|
| banes_burial_grounds.geojson                  | Burial grounds (Retrieved 2017-10)   |
| banes_circuit_of_bath_walk.geojson            | Circuit of Bath Walk route           |
| banes_city_farms.geojson                      | City farms (Retrieved 2017-10)                           |
| banes_community_agriculture.geojson           | Community agriculture (Retrieved 2017-10)                |
| banes_community_gardens.geojson               | Community gardens (Retrieved 2017-10)                    |
| banes_community_orchards.geojson              | Community orchards (Retrieved 2017-10)                   |
| banes_community_supported_agriculture.geojson | Community supported agriculture      |
| banes_conservation_ar.geojson                 | Conservation areas                   |
| banes_education_colleges.geojson              | Colleges (Retrieved 2017-10)            |
| banes_education_secondary_schools.geojson     | Schools (Retrieved 2017-10)            |
| banes_education_special_schools.geojson       | Special schools (Retrieved 2017-10)            |
| banes_education_universities.geojson          | Universities (Retrieved 2017-10)            |
| banes_defibrillators.geojson                  | Defibrillators (Retrieved 2017-10)                   |
| banes_gp_surgeries.geojson                    | GP surgeries                         |
| banes_green_belt.geojson                      | Green belt land (Historic data from 2007)                      |
| banes_grit_bins.geojson                       | Grit bins (Retrieved 2017-10)                            |
| banes_gss_allotments.geojson                  | Allotments                           |
| banes_gss_amenity_grass.geojson               | Amenity grass areas                  |
| banes_gss_churchyards_cem.geojson             | Churchyards & cemeteries             |
| banes_gss_education_greenspace.geojson        | Education green space                |
| banes_gss_natural_greenspace.geojson          | Natural green space                  |
| banes_gss_outdoorsport_fixed.geojson          | Fixed outdoor sport areas            |
| banes_gss_outdoorsport_pitches.geojson        | Outdoor sport pitches                |
| banes_gss_outdoorsport_private.geojson        | Private outdoor sport areas          |
| banes_gss_parks_recreation.geojson            | Park & recreational areas            |
| banes_gss_playspace_children.geojson          | Play spaces for children             |
| banes_gss_playspace_youth.geojson             | Play spaces for youth                |
| banes_landscharareas.geojson                  | Rural landscape character areas (Retrieved 2017-10)      |
| banes_local_shops.geojson                     | Local shops                          |
| banes_park_bbq_disposal.geojson               | BBQ disposal bins (Retrieved 2017-10)                    |
| banes_park_dog_bin.geojson                    | Dog waste disposal bins (Retrieved 2017-10)              |
| banes_park_litter_bin.geojson                 | Litter bins (Retrieved 2017-10)                          |
| banes_park_picnic_tables.geojson              | Picnic tables (Retrieved 2017-10)                        |
| banes_park_recycling_bin.geojson              | Recycling bins (Retrieved 2017-10)                       |
| banes_park_seats_and_benches.geojson          | Seats & benches (Retrieved 2017-10)                      |
| banes_prow_bath.geojson                       | Public rights of way in Bath (Retrieved 2017-10)         |
| banes_prow_somerset.geojson                   | Public rights of way in Somerset (Retrieved 2017-10)     |
| banes_river_rescue_cabinets.geojson           | River rescue cabinets (Retrieved 2017-10)                |
| banes_tpos.geojson                            | Tree preservation orders & TPO areas (Retrieved 2017-10) |
| banes_wedding_venues.geojson                  | Wedding venues (Retrieved 2017-10) |


#### BANES INSPIRE

European Directive 2007/2/EC is known as 'INSPIRE'. INSPIRE establishes an infrastructure for spatial information in the European Union and it was transposed into UK law in December 2009. These datasets are released as part of the INSPIRE programme.

| Item        | Description                                                                                                                                                               |
|:------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                                 |
| Source      | Provided by [Bath & North East Somerset Council](http://www.bathnes.gov.uk/) via [data.gov.uk](http://data.gov.uk)                                                        |
| Retrieved   | 2016-02-11                                                                                                                                                                |
| Licence     | **FOR PERSONAL, NON-COMMERCIAL USE ONLY**<br>[OS INSPIRE](https://www.ordnancesurvey.co.uk/business-and-government/public-sector/mapping-agreements/inspire-licence.html) |
| Attribution | Contains OS data &copy; Crown copyright and database right \[year\]<br>Data provided by Bath & North East Somerset Council                                                |

| File                                             | Description                                                                                                                                                                                                                                                                                                                                                                                                                          |
|:-------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| banes_inspire_allotments.geojson                 | **INSPIRE allotments** (Retrieved 2017-10)<br><small>Allotments owned and managed by Bath and North East Somerset Council.<small>|
| banes_inspire_aqma_bath_major_roads.geojson      | **INSPIRE AQMA Bath** (Retrieved 2017-10)<br><small>Air Quality Management Areas: Areas within Bath & North East Somerset which exceed the Government's air quality standards for nitrogen dioxide. Bath, declared July 2010. See also Keynsham and Saltford AQMA</small>                                                                                                                                                                            |
| banes_inspire_aqma_keynsham.geojson              | **INSPIRE AQMA Keynsham** (Retrieved 2017-10)<br><small>Air Quality Management Areas: Areas within Bath & North East Somerset which exceed the Government's air quality standards for nitrogen dioxide. Keynsham, declared July 2010. See also Bath and Saltford AQMA</small>                                                                                                                                                                            |
| banes_inspire_aqma_saltford.geojson              | **INSPIRE AQMA Saltford**<br><small>Air Quality Management Areas: Areas within Bath & North East Somerset which exceed the Government's air quality standards for nitrogen dioxide. Saltford, declared July 201. See also Bath and Keynsham AQMA</small>                                                                                                                                                                             |
| banes_inspire_aq_stations.geojson                | **INSPIRE Air Quality Monitoring Stations** (Retrieved 2017-10)<br><small>Continuous air pollution monitoring stations within Bath & North East Somerset area. These sites provide hourly monitoring data for nitrogen dioxide or particulate matter for comparison with the Government's air quality objectives.</small>                                                                                                                                |
| banes_inspire_cil_hotel_cz.geojson               | **INSPIRE CIL Hotel Charging Zone** (Retrieved 2017-10)<br><small>Community Infrastructure Levy (CIL) Charging Zones maps for new development in Bath & North East Somerset. These identify the locations and boundaries to which the residential and non-residential CIL charges apply.</small>                                                                                                                                                         |
| banes_inspire_cil_residential_cz.geojson         | **INSPIRE CIL Residential Charging Zones** (Retrieved 2017-10)<br><small>Community Infrastructure Levy (CIL) Charging Zones maps for new development in Bath and North East Somerset. These identify the locations and boundaries to which the residential and non-residential CIL charges apply.</small>                                                                                                                                                |
| banes_inspire_cil_retail_cz.geojson              | **INSPIRE CIL Retail Charging Zone** (Retrieved 2017-10)<br><small>Community Infrastructure Levy (CIL) Charging Zones maps for new development in Bath and North East Somerset. These identify the locations and boundaries to which the residential and non-residential CIL charges apply.</small>                                                                                                                                                      |
| banes_inspire_cil_wr.geojson                     | **INSPIRE CIL Bath Western Riverside** (Retrieved 2017-10)<br><small>Community Infrastructure Levy (CIL) Charging Zones maps for new development in Bath and North East Somerset. These identify the locations and boundaries to which the residential and non-residential CIL charges apply.</small>                                                                                                                                                    |
| banes_inspire_civic_amenity.geojson              | **INSPIRE Civic Amenity Sites** (Retrieved 2017-10)<br><small>Recycling Centres offering recycling and waste disposal services for local residents.</small>                                                                                                                                                                                                                                                                                              |
| banes_inspire_gdslp_2007.geojson                 | **INSPIRE General Development Sites Local Plan 2007 Policy GDS1**                                                                                                                                                                                                                                                                                                                                                                    |
| banes_inspire_libraries.geojson                  | **INSPIRE Libraries** (Retrieved 2017-10)<br><small>Libraries within Bath and North East Somerset Council</small>                                                                                                                                                                                                                                                                                                                                        |
| banes_inspire_llfa_assets.geojson                | **INSPIRE Lead Local Flood Authority (LLFA) Register of Assets (Line Data)**<br><small>Lead Local Flood Authority (LLFA) Register of assets associated with flood risk (Line Data) : to be used in conjunction with LLFA point and LLFA polygon datasets.</small>                                                                                                                                                                    |
| banes_inspire_mineral_consultation_areas.geojson | **INSPIRE Mineral Consultation Areas**<br><smalll>Minerals Consultation Areas are defined to ensure that the Mineral Planning Authority is informed of significant development proposals which may adversely affect minerals resources and has the opportunity to comment upon or oppose them. Local Plan adopted 2007 (Policy M.2)</small>                                                                                          |
| banes_inspire_prslp_2007.geojson                 | **INSPIRE Protected Recreational Sites Local Plan 2007 Policy SR1A**<br><small>Local Plan adopted 2007 Policy SR1A. Defines the boundaries of protected recreational open space throughout the District, including that not currently available for public use such as some school play.</small>                                                                                                                                     |
| banes_inspire_psfps5.geojson                     | **INSPIRE Primary Shopping Frontage Policy S5**<br><small>Local Plan Policy S5 adopted 2007. Primary frontages protect retail uses within the areas defined in Bath central shopping area and Keynsham, Midsomer Norton and Radstock town centres</small>                                                                                                                                                                            |
| banes_inspire_residents_parking_zones.geojson    | **INSPIRE Residents Parking Zones** (Retrieved 2017-10)<br><small>Areas where residents parking permits are in operation</small>                                                                                                                                                                                                                                                                                                                         |
| banes_inspire_smoke_control_areas.geojson        | **INSPIRE Smoke Control Areas** (Retrieved 2017-10)<br><small>Areas within Bath & North East Somerset where smoke control legislation applies. Within these areas you are required to either burn approved smokeless fuels or require an appliance which has been approved by DEFRA as being smoke free. Areas declared between 1980 and 1994.</small>                                                                                                   |
| banes_inspire_sscs_2014.geojson                  | **INSPIRE Strategic Site Allocations Core Strategy 2014 Policies B3A KE3A KE4A RA5**<br><small>Core Strategy adopted 2014 Policies B3A KE3A KE4A RA5. Defines the boundary of large strategic sites allocated principally for residential development on the edge of Bath, Keynsham and Whitchurch.</small>                                                                                                                          |
| banes_inspire_tpos.geojson                       | **INSPIRE Tree Preservation Orders** (Retrieved 2017-10)<br><small>A Tree Preservation Order is an order made by a local planning authority (LPA ) to protect specific trees, groups of trees or woodlands when it is deemed to be expedient in the interests of amenity. An Order prohibits the cutting down; topping; lopping; uprooting; wilful damage or wilful destruction of trees without the local planning authority's written consent.</small> |
| banes_inspire_wraalp_2007.geojson                | **INSPIRE Waterside Recreation Activity Areas Local Plan 2007 Policy SR10**<br><small>Local Plan adopted 2007 Policy SR10. Defines the boundaries of areas where recreational development associated with the waterways may be acceptable.</small>                                                                                                                                                                                   |
| banes_litter_bins.geojson                        | **INSPIRE Roadside Litter Bins** (Retrieved 2017-10)                   |

### Bath: Hacked

#### Accessible Bath Project

| Item        | Description                                                                                                                |
|:------------|:---------------------------------------------------------------------------------------------------------------------------|
| Files       | bh_accessible_bath.geojson                                                                                                                  |
| Source      | Snapshot from [Bath: Hacked Accessible Bath Website](https://accessiblebath.org/)                                               |
| Retrieved   | 2017-10-06                                                                                                                    |
| Licence     | [ODbL](https://opendatacommons.org/licenses/odbl/)                                           |
| Attribution | &copy; OpenStreetMap contributors |


### Department for Communities & Local Government

#### Green Belt boundaries for England 2013-2014

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | dclg_greenbelt_2013_14.geojson                                                                                                                                                                                              |
| Source      | [Open Data Communities - Greenbelt](http://opendatacommunities.org/data/geography/greenbelt)                                                                                                                                |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | Contains OS data &copy; Crown copyright and database right \[year\]<br>Data provided by Department for Communities & Local Government                                                                                       |
| See also    | [Green Belt boundaries for England have been released as open data](http://mapgubbins.tumblr.com/post/99635819470/green-belt-boundaries-for-england-have-been)                                                              |

### Department of Energy & Climate Change

#### Domestic Electricity Consumption

Domestic electricity consumption 2013 by postcode.

| Item        | Description                                                                                                                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | decc_dom_elec_pc_2013.geojson                                                                                                                                                                                   |
| Source      | [Postcode level electricity estimates:2013 (experimental)](https://www.gov.uk/government/statistics/postcode-level-electricity-estimates-2013-experimental)                                                     |
| Retrieved   | 2016-01-24                                                                                                                                                                                                      |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                                                                |
| Attribution | Data provided by Department of Energy & Climate Change                                                                                                                                                          |
| See also    | [Sub-national electricity and gas consumption statistics](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/388960/Subnational_electricity_and_gas_consumption_summary_report_2013.pdf) |

#### Domestic Gas Consumption

| Item        | Description                                                                                                                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | decc_dom_gas_pc_2013.geojson                                                                                                                                                                                    |
| Source      | [Postcode level gas estimates: 2013 (experimental)](https://www.gov.uk/government/statistics/postcode-level-gas-estimates-2013-experimental)                                                                    |
| Retrieved   | 2016-01-24                                                                                                                                                                                                      |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                                                                |
| Attribution | Data provided by Department of Energy & Climate Change                                                                                                                                                          |
| See also    | [Sub-national electricity and gas consumption statistics](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/388960/Subnational_electricity_and_gas_consumption_summary_report_2013.pdf) |

### Department for the Environment, Food & Rural Affairs

#### Strategic noise mapping 2012


| Item        | Description                                                                                                        |
|:------------|:-------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                          |
| Source      | [Open data: strategic noise mapping](https://www.gov.uk/government/publications/open-data-strategic-noise-mapping) |
| Retrieved   | 2016-01-20                                                                                                         |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                   |
| Attribution | Data provided by Department for the Environment, Food & Rural Affairs                                              |

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
| Attribution | Data provided by Environment Agency                                                                                               |

### Historic England

#### Listed Buildings

| Item        | Description                                                                                                                                                                                                                                                                                                         |
|:------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | he_listed_buildings.geojson                                                                                                                                                                                                                                                                                   |
| Source      | [Historic England](https://www.historicengland.org.uk/listing/the-list/data-downloads)                                                                                                                                                                                                                              |
| Retrieved   | 2017-10-05                                                                                                                                                                                                                                                                                                          |
| Licence     | See he_listed_buildings_licence.pdf                                                                                                                                                                                                                                                                                 |
| Attribution | &copy; Historic England [year].<br>Contains Ordnance Survey data &copy; Crown copyright and database right [year]<br>The Historic England GIS Data contained in this material was obtained on [date]. The most publicly available up to date Historic England GIS Data can be obtained from HistoricEngland.org.uk. |

#### Scheduled Monuments

| Item        | Description                                                                                                                                                                                                                                                                                                         |
|:------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | he_scheduled_monuments.geojson                                                                                                                                                                                                                                                                                   |
| Source      | [Historic England](https://www.historicengland.org.uk/listing/the-list/data-downloads)                                                                                                                                                                                                                              |
| Retrieved   | 2017-10-05                                                                                                                                                                                                                                                                                                          |
| Licence     | See he_scheduled_monuments.pdf                                                                                                                                                                                                                                                                                 |
| Attribution | &copy; Historic England [year].<br>Contains Ordnance Survey data &copy; Crown copyright and database right [year]<br>The Historic England GIS Data contained in this material was obtained on [date]. The most publicly available up to date Historic England GIS Data can be obtained from HistoricEngland.org.uk. |

### National Trust

#### Bath Skyline Walk Route

| Item        | Description                                                                      |
|:------------|:---------------------------------------------------------------------------------|
| Files       | nt_bath_skyline.geojson                                                          |
| Source      | Provided by BANESC                                                               |
| Retrieved   | 2016-01-25                                                                       |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) |
| Attribution | Data provided by National Trust                                                  |

### Natural England

| Item        | Description                                                                                                                                                 |
|:------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                   |
| Source      | [Environment Agency - Download Environmental Open Data](http://www.geostore.com/environment-agency/WebStore?xml=environment-agency/xml/ogcDataDownload.xml) |
| Retrieved   | 2016-01-25                                                                                                                                                  |
| Licence     | [OGL NE-OS](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/409507/NE-terms-of-use.pdf)                                           |
| Attribution | &copy; Natural England copyright.<br>Contains Ordnance Survey data &copy; Crown copyright and database right \[year\]                                       |

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

### Ofcom

#### Broadband Survey June 2013

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| File        | ofcom_broadband_2013.geojson                                                                                                                                                                                                |
| Source      | [Ofcom](http://data.gov.uk/dataset/broadband-coverage) via [Bath: Hacked Datastore](https://data.bathhacked.org/Economy/Banes-Broadband-Survey-June-2013/cnmf-qdpb)                                                         |
| Retrieved   | 2015-08-21                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | Data provided by Ofcom<br>Contains OS data (c) Crown copyright \[year\]<br>Contains Royal Mail data (c) copyright and database right \[year\]                                                                               |

#### Connected Nations 2016

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                                                                    |
| Source      | [Ofcom](https://www.ofcom.org.uk/research-and-data/multi-sector-research/infrastructure-research/connected-nations-2016/downloads)                                                                                          |
| Retrieved   | 2017-03-10                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | Data provided by Ofcom<br>Contains OS data (c) Crown copyright \[year\]<br>Contains Royal Mail data (c) copyright and database right \[year\]                                                                               |

| File                  | Description                            |
|:----------------------|:---------------------------------------|
| ofcom_bb_pc_2016.csv  | Full name of fields  |
| ofcom_bb_pc_2016.geojson | Broadband Survey June 2016 |


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
| Attribution | Data provided by Office for Low Emission Vehicles                                            |

### Office for National Statistics

#### Administrative Boundaries

| Item        | Description                                                                                                                                                                                                                 |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                                                                                   |
| Source      | [ONS Geoportal](https://geoportal.statistics.gov.uk/geoportal/catalog/content/filelist.page?&pos=3&cat=#BD)<br>(If you are thrown to the home page click on Downloads > Boundaries)                                         |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                  |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) ([OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)) |
| Attribution | Contains National Statistics data &copy; Crown copyright and database right \[year\]<br>Contains OS data &copy; Crown copyright and database right \[year\]                                                                 |

| File                  | Description                            |
|:----------------------|:---------------------------------------|
| ons_lsoa_2011.geojson | 2011 Lower Super Output Areas (LSOAs)  |
| ons_msoa_2011.geojson | 2011 Middle Super Output Areas (MSOAs) |
| ons_oa_2011.geojson   | 2011 Output Areas (OAs)                |
| ons_ward_2011.geojson | 2011 Wards                             |
| ons_wmc_2014.geojson  | 2014 Westminster Constituencies        |
| ons_wz_2011.geojson   | 2011 Workplace Zones                   |

#### Census 2011

| Item        | Description                                                                                                                                                                                   |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                                                                                                     |
| Source      | [ONS](http://www.ons.gov.uk/ons/guide-method/census/2011/index.html) via [Bath:Hacked Datastore](https://data.bathhacked.org/Population/Census-2011-B-NES-Selected-Small-Area-Data/qxks-a8tv) |
| Retrieved   | 2016-02-07                                                                                                                                                                                    |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                                              |
| Attribution | Adapted from data from the Office for National Statistics licensed under the Open Government Licence v.3.0.                                                                                   |

| File                       | Description                            |
|:---------------------------|:---------------------------------------|
| ons_census_2011_fields.csv | Full names of common fields            |
| ons_census_2011_oa.csv     | 2011 census by Output Area             |
| ons_census_2011_lsoa.csv   | 2011 census by Lower Super Output Area |
| ons_census_2011_ward.csv   | 2011 census by Ward                    |


#### Output Area Classifications 2011

Area classifications group together geographic areas according to key characteristics common to the population in that grouping. These groupings are called clusters and are derived using census data. The area classifications are hierarchical classifications, consisting of three tiers: Supergroups, Groups and Subgroups.

| Item        | Description                                                                                                                                                                                                                                                                                                                                                                                             |
|:------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | ons_oac_2011.geojson                                                                                                                                                                                                                                                                                                                                                                                    |
| Source      | [2011 Area Classifications](http://www.ons.gov.uk/ons/guide-method/geography/products/area-classifications/ns-area-classifications/ns-2011-area-classifications/index.html)                                                                                                                                                                                                                             |
| Retrieved   | 2016-01-25                                                                                                                                                                                                                                                                                                                                                                                              |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)<br>[OS Open Data](https://www.ordnancesurvey.co.uk/business-and-government/licensing/using-creating-data-with-os-products/os-opendata.html)<br>[ODbL](http://opendatacommons.org/licenses/odbl/)                                                                                                                       |
| Attribution | Contains National Statistics data &copy; Crown copyright and database right \[year\].<br>Contains ONS data &copy; Crown copyright and database right \[year\].<br>Contains NRS data &copy; Crown copyright and database right \[year\].<br>Contains NISRA data &copy; Crown copyright and database right \[year\].<br>Contains Ordnance Survey data &copy; Crown copyright and database right \[year\]. |
| Granularity | Output Area                                                                                                                                                                                                                                                                                                                                                                                             |

#### Indices of Mass Deprivation 2015

Statistics on relative deprivation in small areas in BANES. See `ons_imd_2015_fields.csv` for full descriptions of fields.

| Item        | Description                                                                                                         |
|:------------|:--------------------------------------------------------------------------------------------------------------------|
| File        | ons_imd_2015.geojson, ons_imd_2015_fields.csv                                                                       |
| Source      | [English Indices of deprivation 2015](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2015) |
| Retrieved   | 2016-01-17                                                                                                          |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                    |
| Attribution | Data provided by DCLG & ONS.                                                                                        |
| Granularity | Lower Super Output Area                                                                                             |

### Ordnance Survey

#### Open Map Local

| Item        | Description                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                       |
| Source      | [OS Open Map - Local](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-map-local.html) |
| Retrieved   | 2017-10-05                                                                                                      |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                                    |
| Attribution | Contains OS data &copy; Crown copyright \[and database right\] \[year\]                                         |

| File                           | Description                         |
|:-------------------------------|:------------------------------------|
| os_boundary.geojson            | Bath & North East Somerset boundary |
| os_buildings.geojson           | Buildings                           |
| os_car_charging_point.geojson | Car charging points |
| os_electricity_lines.geojson   | Electricity lines                   |
| os_functional_sites.geojson    | Functional sites                    |
| os_important_buildings.geojson | Important buildings                 |
| os_parishes.geojson            | Parishes (retrieved 2016-01-21) |
| os_place_names.geojson         | Place names                         |
| os_rail_station.geojson | Rail station |
| os_rail_track.geojson          | Rail track                          |
| os_rail_tunnel.geojson | Rail tunnel |
| os_roads.geojson               | Roads                               |
| os_road_roundabout.geojson | Road roundabout |
| os_settlements.geojson         | Settlements  (retrieved 2016-01-21) |
| os_surface_water_area.geojson  | Surface water polygons              |
| os_surface_water_line.geojson  | Surface water lines                 |
| os_woodland.geojson            | Woodland                            |

#### Open Greenspace

| Item        | Description                                                                                                     |
|:------------|:----------------------------------------------------------------------------------------------------------------|
| Files       | See below                                                                                                       |
| Source      | [OS Open Greenspace](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-greenspace.html) |
| Retrieved   | 2017-10-05                                                                                                      |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                                    |
| Attribution | Contains OS data &copy; Crown copyright \[and database right\] \[year\]                                         |

| File                           | Description                         |
|:-------------------------------|:------------------------------------|
| os_greenspace_access_point.geojson | Greenspace access points |
| os_greenspace_site.geojson | Greenspace sites |

#### Code-Point Open

Postcode centroids within BANES, with administrative area lookup.

| Item        | Description                                                                                                                                                                                                                                         |
|:------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| File        | os_postcodes.geojson                                                                                                                                                                                                                                |
| Source      | [Code-Point Open](https://www.ordnancesurvey.co.uk/business-and-government/products/code-point-open.html)                                                                                                                                           |
| Retrieved   | 2017-10-05                                                                                                                                                                                                                                          |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                                                                                                                                                                        |
| Attribution | Contains OS data &copy; Crown copyright \[and database right\] \[year\]<br>Contains Royal Mail data &copy; Royal Mail copyright and Database right \[year\]<br>Contains National Statistics data &copy; Crown copyright and database right \[year\] |

#### Terrain 50

Terrain contours with post spacing of 50m	& vertical interval of 10m.

| Item        | Description                                                                                        |
|:------------|:---------------------------------------------------------------------------------------------------|
| File        | os_terrain50.geojson                                                                               |
| Source      | [OS Terrain 50](https://www.ordnancesurvey.co.uk/business-and-government/products/terrain-50.html) |
| Retrieved   | 2017-10-05                                                                                         |
| Licence     | [OS OpenData](http://os.uk/opendata/licence)                                                       |
| Attribution | Contains OS data &copy; Crown copyright \[and database right\] \[year\]                            |

### Police

#### Street Level Crimes

| Item        | Description                                                                                                                                                                |
|:------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Files       | police_crimes.geojson                                                                                                                                                      |
| Source      | [Police API](https://data.police.uk/docs/) via [BANES Street Level Crimes Dataset](https://data.bathhacked.org/Government-and-Society/BANES-Street-Level-Crimes/cujy-zqnk) |
| Retrieved   | 2017-10-05                                                                                                                                                                 |
| Licence     | [OGL](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)                                                                                           |
| Attribution | Data provided by data.police.uk                                                                                                                                            |
