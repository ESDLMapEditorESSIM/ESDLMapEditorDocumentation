Connecting assets
=================

ESDL knows the concept of ports and connections to connect assets. Ports exist in two types (by design, see LINK for
more detailed information):

* InPort: port that is mainly used for incoming flow, current or energy
* OutPort: port that is mainly used for outgoing flow, current or energy

An InPort is visualized as a blue square to the left on an asset, an OutPort is visualized as a red square to the
right of an assets. InPorts can only be connected to OutPorts and the other way around.

The amount and type of ports the MapEditor attaches to an asset when the user adds an asset to the map, depends on the
view mode. The standard behaviour is as follows (for drawing 'single-line systems'):

* Producer: 1 OutPort
* Consumer: 1 InPort
* Storage: 1 InPort
* Conversion: 1 InPort and 1 OutPort

  * There are two exceptions to this rule, for the CoGeneration types (CHP and FuelCell): They'll get 1 InPort and 2 OutPorts

* Transport: 1 InPort and 1 OutPort

If you switch the view mode to 'CHESS', this behaviour changes to (for drawing 'double-line systems'):

* Producer: 1 InPort and 1 OutPort
* Consumer: 1 InPort and 1 OutPort
* Storage: 1 InPort and 1 OutPort
* Conversion: *** To be discussed ***
* Transport: 1 InPort and 1 OutPort

  * There are two exceptions to this rule, for the Transformer and HeatExchange: They'll get 1 InPort and 1 OutPort
    for the primary side and 1 InPort and 1 OutPort for the secondary side
