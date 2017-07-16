
 
# OSEspecificaiton
## 
**OSEnergy _(Open Systems Energy)_** is an architectural specification who's aim is to provide a framework for the design, deployment, and operation of charging sources associated with a DC battery.  Allowing them to work together in a *'systems'* approach.
 
Through the utilization of open standards an out-of-band communications protocol enables multiple charging sources to function cooperatively; meeting the full requirements of an associated battery as well as concurrently supplying house power needs in  a consistent and efficient way.  Further, it allows for the prioritization of charging sources allowing optimal use of available resources.
 
Additional aspects of the architectural specification cover usability in terms of initial installation and configuration as well as ongoing monitoring.  Levering a system wide view allows for early degradation and fault detection at both an individual components as well as system wide.
 
Licensing terms of OSEnergy is intended to support both commercial as well as open source designs, moving away from existing proprietary approaches.
 
(GRAPHIC HERE)
 
 
<br><br>
## Architectural Goals
The OSEnergy initiative has three primary goals in the installation and operation of a DC system:  **Protection, Optimization, Simplification.**     _Design Objectives_ are created to support each of these goals.  Goals, in priority order, are:
 
1. Protection
* Protecting battery from damage or reduced life expectancy as a result of incomplete and/or improper charging or usage.
* Protecting system components from excessive stress, overloading, and other abuses.
* Support of fall-back / degraded operation modes allowing continue operation during component failure.  Including in-band only communications mode.
2. Optimization
* Providing for proper battery charging to maximize battery life expectancy while supporting energy needs.
* Prioritization of available resources while meeting the energy and power needs of the battery and system loads.
* Allow for trade-offs of component life (particularly the battery) with user energy expectations. 
3. Simplification
*  Simplify  Installation  - hardware, wiring, configuration
* Operation                       - self balancing, user monitoring
<br><br>

<br><br>
## Architectural Objectives
Architectural Objectives allow for designs to meet the goals of the OSEnergy initiative.  Care should be taken to consider different end users for installation, configuration, and operation.  By enabling each objective, different components will be able to fully participate in a fully cooperative manner.  The following gives a overview of some of the key objectives.  Reference the OSEnergy Design Guide for details of objectives.
 
