Exploring spatial possibilities for large scale wind and solar
==============================================================

One of the applications provided by the PICO model developed by Geodan, is to gain insight in the spatial possibilities
for large scale wind and solar energy production. The PICO model can be queried for this potential, with several
constraints as input that can be given by user. The results in ESDL can be visualized in the ESDL MapEditor.

.. note::
    This page describes the steps for exploring the spatial possibilities for large scale wind. You can follow exactly the
    same steps if you select the 'Get PICO solar field potential' service in step 2.

This workflow can be divided in the following steps:

1. Click 'External ESDL Services' in the Services menu

  .. image:: images/select_external_service.png
    :alt: Select external ESDL services

2. Select 'Get PICO wind potential'

  .. image:: images/select_pico_wind_potential.png
    :alt: Select get PICO wind potential

3. The following information is displayed

  .. image:: images/pico_wind_potential_input.png
    :alt: input required for the PICO wind potential service

4. Fill in the required input parameters

  - We select the province of Drenthe
  - We want to know what the potential is, if we require a minimal distance of 500 meters between the wind turbines and the built environment
  - We don't want to include areas that have been marked as 'nature' and do want to include any agricultural area

  .. image:: images/pico_wind_potential_input_province_Drenthe.png
    :alt: Input settings for retrieving information about the wind potential in the province of DDrenthe

5. The result will look like the following picture. Each hexagon is a possible location for a wind turbine.

  .. image:: images/pico_wind_potential_output_province_Drenthe.png
    :width: 800
    :alt: Wind potential areas in the province of Drenthe

