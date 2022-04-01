# Tasks

## Density

	- [x] General coding for LBCS / NAICS based density calculation
	- [x] Coding for residents / jobs density calculation
	- [x] Coding for intersection density calculation
	- [ ] Realization and testing for specific density indicators: 3rd places, culture, etc.
	- [ ] Density normalization

## Diversity

	- [x] General coding for LBCS / NAICS based diversity calculation
	- [x] Coding for residential / job diversity calculation
	- [ ] Realization and testing for specific diversity indicators: 3rd places, culture, etc.
	- [x] Diversity normalization

## Proximity

	- [x] General coding for LBCS / NAICS based proximity (heatmap  + indicator) calculation
	- [x] Proximity normalization
	- [ ] Realization and testing for specific proximity indicators and heatmaps.

## Composite Indicators

	- [ ] Coding for health, wellbeing, safety calculation: it just takes some specific indicators of density/diversity/proximity and do some aggregation. 

## Building Energy

	- [x] Commercial building energy model training
	- [x] Commercial building energy prediction
	- [x] Residential household energy model training 
	- [x] Residential household energy prediction

## Mobility and Innovation Potential

	- [x] Network generation and shortest path testing
	- [ ] Network refinement: from driving to activity and public transit
	- [ ] Home location choice model training
	- [ ] Home location choice model prediction
	- [x] Activity schedule (motif) clustering
	- [ ] Activity scheduler model training
	- [ ] Huff model for destination choices 
	- [x] Mode choice model training
	- [ ] The whole framework of ABM for mobility simulation
	- [ ] Innovation potential module embedded in ABM 

## Data Processing

 - [x] Geodata processing and assigned to H3 cells
 - [x] H3 cells: aggregating data from different sources
 - [x] Type definition: land use type, housing type, profile (x)
 - [x] Data formatting

## Backend Architecture

 - [x] Handler: using UDP + MQTT for message communication
 - [x] Receive table state and update land use 
 - [ ] Receive density (height) from tablet and update it 
	- [x] Send results back to frontend



