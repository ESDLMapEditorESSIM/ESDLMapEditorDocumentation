Exploring rooftop PV panels potential
=====================================

One of the applications provided by the PICO model developed by Geodan, is to gain insight in the potential for rooftop
PV panels. Based on internal calculations the model can be queried for the potential on roofs of 5 different orientations:

* Roofs facing north

* Roofs facing east

* Roofs facing Ssouth

* Roofs facing west

* Flat roofs


There are two possible ways to use this service:

* Via the 'External services' menu

* Via the context menu of an area on the map


External services menu
**********************

This workflow can be divided in the following steps:

1. Go to 'Services' menu and select 'External ESDL Services'. Select 'Get PICO rooftop solar potential' from the list

  .. image:: images/esdl_services_pico_rooftop_solar_potential.png
    :alt: Select 'external ESDL services', and 'get PICO rooftop solar potential'

2. The service can be queried for 3 different geographical scopes:

  .. image:: images/pico_rooftop_solar_potential_scope.png
    :alt: 3 different geographical scopes

3. As an example, select 'Municipality' and choose 'Hengelo'. Press the 'Run Service' button. The following result will load.

  .. image:: images/pico_rooftop_solar_potential_municipality.png
    :alt: Results for the municipality of Hengelo

5. Continue :ref:`here <Exploring potential values>`


Via the area context menu
*************************

1. If you have an already loaded energy system (and the area attributes have been formatted in the right way), you can right click on an area and select 'Query Rooftop PV Potential'.

  .. image:: images/context_menu_area_query_potential.png
    :alt: Context menu for an area

2. A dialog opens where you can select to only query the potential for the selected area or for all areas in the energy system.

  .. image:: images/query_rooftop_pv_potential.png
    :alt: Query rooftop pv potential for area

3. If you choose to query for all areas, the result looks like

  .. image:: images/rooftop_potential_neighbourhood.png
    :alt: Rooftop PV potential for all areas

4. Continue :ref:`here <Exploring potential values>`

Exploring potential values
**************************

1. When you right click on a building on the map, a context menu appears

  .. image:: images/building_context_menu.png
    :alt: Building context menu

2. Click 'Building ESDL contents' to open the building editor

  .. image:: images/five_types_of_rooftop_panels_potential.png
    :alt: building editor with 5 different types of rooftop PV potential

3. Right click on one of the icons for the solar potential (SP)

  .. image:: images/right_click_solar_potential.png
    :alt:

4. Click on 'Edit' to open the ESDL browser and inspect the information.

  .. image:: images/value_of_solar_potential.png
    :alt: Inspect values of solar potential

Converting potential to actual installations
********************************************

The last functionality is to convert (part of) the potential to installed capacity of PV installations.

1. Right click on an area, and select 'Use Rooftop PV Potential'

  .. image:: images/context_menu_area_use_potential.png
    :alt: Context menu are use potential

2. At the moment you can fill in one percentage for all orientations and apply this to this area or all areas

  .. image:: images/use_rooftop_pv_potential.png
    :alt: Use Rooftop PV Potential

3. If you open the building editor again, the result looks like this. By right clicking on an icon for a PV installation and selecting 'Edit' from the menu, values can be inspected.

  .. image:: images/building_editor_installed_pv_installations.png
    :alt: Installed PV installations

.. note::
    ESDL: The produced energy in kWh is connected as a SingleValue profile to the OutPort of the PVInstallation asset.
    Other models, like for example the Energy Transition Model, know how to handle this information and are able to
    take these values into account.