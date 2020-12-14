# ENVRI-FAIR-WP11---Soil-Water-Content-UC
We have now to put the Soil Water content use case on track.
Soil water Content use case 

Context 

Scientific needs : 

Soil water content (SWC) is a key variable in many ecosystem processes as the vegetation dynamic, the biogeochemical cycles, water balance, soil physical properties. However, SWC presents very strong spatial variations linked to the heterogeneity of the soil, the vegetation and climatic conditions as well as the relief which can contribute to water redistribution by runoff. This variability is also temporal, linked in particular to the temporal dynamics of plant cover and climate. In situ measurement methods are very local, requiring large, expensive and intrusive sampling. Remote sensing offers the possibility of spatialization, but the methods remain limited to a layer of a few centimetres. Modelling therefore remains an essential tool for providing a representation of soil moisture at scales of interest for many applications (hydrology, ecology, agronomy). Models are nevertheless relatively complex and require a large number of contextual variables, such as the local climate, plant cover and its rooting, soil properties and topography. It is therefore important to be able to surround the soil moisture measurements by the acquisition of contextual variables that allow the interpretation of the measurements and feed the models. For this purpose, research infrastructures offer a particularly favourable framework that is complementary to existing networks by producing both quality soil moisture measurements and by describing the context variables. 

Potential users : 

The provision of soil moisture data and context variables in a standardised framework is undeniably a very important service for a wide range of users :  

Meteorologist  for data assimilation in meteorological models 

Water resource management (aquifer recharge/discharge, runoff, river flow). 

Science community (calibrate and implement models, soil moisture being interesting by itself or can be co-variable of other process – erosion, compaction biochemical cycle, soil biology …) 

Climate change study 

Drought assessment (Insurance) 

Satellite product calibration 

Public/media (during extreme events  but requires modelling) 

Existing initiative 

Il existe des initiatives rassemblant des données provenant de différents réseaux de mesure. C’est le cas notamment de l’International Soil Moisture Network (ISMN) qui rassemble des données venant d’une soixantaine de réseaux couvrant plus de 3000 sites à travers le monde. Ce réseau a été impulsé grâce aux efforts conjoints de GEWEX, the Committee on Earth Observation Satellites (CEOS), the Global Climate Observing System - Terrestrial Observation Panel for Climate (GCOS-TOPC), the Group of Earth Observation (GEO), the Global Terrestrial Network on Hydrology (GTN-H) and the European Space Agency (ESA). Dans la mouvance de l’observation de la terre, ce reseau a privilégié l’exhaustivité spatiale et offre un service de moissonnage de données essentiellement fondés sur des critères spatiaux. Par contre la fourniture de données de contexte reste sommaire. C’est là ou un portail donnant accès à des données d’humidité et des variables décrivant le contexte d’acquisition constitue une offre très complémentaire de l’ISMN. 

Envri-FAIR context 

In Envri Fair use case should ideally present requirements 

User oriented service : technically the architecture and functionalities will be driven by the applications and user needs. 

RI Interoperability demonstration  

The use case definition bridges to the activities in EOSC Future. 

Use cases should be designed along cross-subdomain science questions like, e.g. interaction of air pollution with climate change, spreading of diseases, or change in biodiversity (see use cases for EOSC Future). 

Use case Vision (to be consolidated 

Functionalities can be: 

Querying on site contextual element 

Location (available in ISMN) 

Period of acquisition (available in ISMN) 

Ecosystem type 

Plant species  

Climate quantitative indicator 

Soil type 

Soil moisture set up (depth, spatio temporal sampling) 

Availability of contextual data 

Gathering rich data and metadat sets including data and contextual data in standard format 

Site characteristics (soil, ecosystem, location, contact … 

SM table 

Site permanent characteristic (soil horizon, texture, density, retention curve, hydraulic conductivity ….) 

Contextual table (climate, soil temperature, canopy traits (aerial, underground), … 

Data analysis  

Vizualisation  

Should we (how can we) go further to address science questions (SWC forecast, plant stress, drought characterization, soil trafficability, runoff risk …) keeping in mind that RI provide rich data sets but are not organised to provide spatialized monitoring). 

Objective 

The primary objectives is to make SWC and related contextual data acces easier over a network unique by its size and by the richness of information. This is possible by combining resources from the different RIs across Europe. Behind this core objective the use can provide  a data service able to query extract SWC and contextual data in a harmonize format from the different data sets (likely requires some modelling to standardize measurements through the different sites for spatial and temporal scales). This requires to 

Develop a dynamic portal 

Develop API to access the data 

Develop data transformation tools to harmonize delivered data 

Consider intellectual properties issues (TF5) 

The participating RI will be AnaEE, eLTER, Danubius, ICOS, SIOS and Lifewatch 

Technical Issues (to be updated with RI communities) 

The following components are foreseen 

request API able to make facetted research that could query a data repository and identify source of data based on semantic resources (including updating process with running experiments) 

 

An API able to upload data base from distributed data base 

An integrator that provide harmonized data sets 

 

Work flow 

Identification of data set that will contribute (2020) 

Final Design of the service (2020) 

Technical specification of the different components (01-2021) 

Service architecture and technology selection (03-2021) 

Implementation  
