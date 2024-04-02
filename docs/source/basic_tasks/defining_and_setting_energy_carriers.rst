Defining and setting energy carriers
====================================

ESDL energy assets produce, consume, store, or convert different energy commodities and carries such as, for example, gas (natural gas, hydrogen etc.), electricity, or heat. These commodities and carriers are assigned to connections between energy assets.

In this basic scenario, two Commodities exist: gas (imported from an external system) and heat (as a result of GasHeater conversion). To add an energy Commodity, mouseover the Edit menu item and click on *Energy carriers...* (see figure below). A pop-up menu opens with a list of energy Carriers and Commodities that can be added and configured.

.. image:: images/adding_commodities1.png
   :width: 300
   :alt:

Click on the *Carrier type* dropdown menu (nr.1), and select *Gas Commodity* (nr.2).

.. image:: images/adding_commodities2.png
   :width: 300
   :alt:

Give it a descriptive name (e.g. Natural Gas) (nr.1) and leave the other fields blank. To save the changes, click on *Add* (nr.2).

.. image:: images/adding_commodities3.png
   :width: 300
   :alt:

The created Gas Commodity (Natural Gas) is shown on the pop-up window, along with the color that will be used to visualize the connections that have this commodity. The color of the commodity can be changed.

.. image:: images/adding_commodities4.png
   :width: 300
   :alt:

Repeat the same process to create Heat commodity.

Assigning energy commodities to asset connections
-------------------------------------------------

Energy carriers and commodities created in the previous steps are assigned to connections between ESDL energy assets, i.e. to their InPorts and OutPorts. To assign the natural gas commodity to Import's OutPort asset, right-click on Import and select *Set carrier*.

.. image:: images/adding_commodities5.png
   :width: 300
   :alt:

A pop-up window opens with a list of created energy commodities (Natural Gas and Heat, in this example). To assign Natural Gas to Import asset, click on Natural Gas in the list of carriers. The window automatically closes, and Natural Gas is assigned to the OutPort of Import, and the InPort of GasHeater, as there already exists a connection between these two ports.

.. image:: images/adding_commodities6.png
   :width: 300
   :alt:

The connection between the Import and GasHeater is colored in red (the color assigned to Natural Gas commodity), indicating the assigned commodity.

.. image:: images/adding_commodities7.png
   :width: 300
   :alt:

Repeat the same process to assign Heat commodity to HeatingDemand. This will assign Heat commodity to HeatingDemand's InPort, and to GasHeater's OutPort.
Assigned commodities can be seen by clicking on an asset and navigating to the *Ports* group, as shown below for GasHeater.

.. image:: images/adding_commodities8.png
   :width: 300
   :alt: