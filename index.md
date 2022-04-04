# CAMELS-CH reproducibility guide

The purpose of this guide is to describe the creation of the CAMELS-CH dataset in order to facilitate its future updating.


## CAMELS_CH_topographic_attributes

### Gauge data

**Attributes**: gauge_id, gauge_name, gauge_lat, gauge_lon, gauge_easting, gauge_northing, gauge_elev

**Source data**:
* Main data source: BAFU gauge properties
* Complemented with the EU-Hydro river network database (https://land.copernicus.eu/imagery-in-situ/eu-hydro)

**Instructions**:
1. ...
2. ...

### Catchment properties

**Attributes**: area, dpsbar, elev_mean, elev_min, elev_10, elev_50, elev_90, elev_max

**Source data**:
* Main data source: Catchement shapefiles provided by BAFU
* Complemented with the EU-Hydro river network database (https://land.copernicus.eu/imagery-in-situ/eu-hydro)

**Code used**: ...

**Instructions**:
1. ...
2. ...


## CAMELS_CH_climatic_attributes


## CAMELS_CH_hydrologic_attributes

### Hydrologic Signatures

**Attributes**: q_mean, runoff_ratio, stream_elas, slope_fdc, baseflow_index, baseflow_index_ceh, hfd_mean, Q5, Q95, high_q_freq, high_q_dur, low_q_freq, low_q_dur, zero_q_freq

**Source data**:
* Streamflow time series provided by BAFU

**Code used**: hydro/hydro_signatures.R

**Instructions**:
1. ...
2. ...


## CAMELS_CH_landcover_attributes


## CAMELS_CH_soil_attributes


## CAMELS_CH_hydrogeology_attributes


## CAMELS_CH_hydrometry_attributes


## CAMELS_CH_humaninfluence_attributes
