Chapter Seven
=============

Dynamical processes for descriptive ocean circulation
-----------------------------------------------------

.. toctree::
  :maxdepth: 2
  :caption: Contents:

  7a
  7b


.. admonition:: Data files supplied for Chapter 7 exercises

  * WOA09_decimated_Pacific.joa
  * WOA98_heavydeci_Pacific.poa
  * WOA05_decimated_Arctic.joa
  * WOA05_decimated_Atlantic.joa
  * WOA05_decimated_Indian.joa
  * WOA05_decimated_Southern.joa
  * WOA98_heavydeci_Atlantic.poa
  * WOA98_heavydeci_Indian.poa

  Download: :download:`Chapter 7 Data Files <./DPO_data_chapter_7.zip>`

Goals
`````
* Map the dynamic topography of ocean regions

To accomplish this, one will
````````````````````````````
* Open a WOA09 data file
* Configure map plots to display topography
* Customize plots

Tools
`````
* JOA built in parameter calculator

DPO Chapter 7 Sections
``````````````````````
DPO JOA examples are available for the following **emphasized** sections:

.. list-table::
  :widths: 10, 90

  * - 7.1
    - Introduction: mechanisms
  * - 7.2
    - Momentum balance
  * - 7.2.1
    - Acceleration and advection
  * - 7.2.2
    - Pressure gradient force and gravitational force
  * - 7.2.3
    - Rotation: centrifugal and Coriolis forces
  * - 7.2.4
    - Viscous force or dissipation
  * - 7.2.4.1
    - Molecular viscosity
  * - 7.2.4.2
    - Eddy viscosity
  * - 7.2.5
    - Mathematical expression of momentum balance
  * - 7.3
    - Temperature, salinity and density evolution
  * - 7.3.1
    - Temperature, salinity and density equations
  * - 7.3.2
    - Molecular and eddy diffusivity
  * - 7.4
    - Mixing layers
  * - 7.4.1
    - Surface mixed layer
  * - 7.4.2
    - Bottom mixed layers
  * - 7.4.3
    - Internal mixing layers
  * - 7.5
    - Response to wind forcing
  * - 7.5.1
    - Inertial currents
  * - 7.5.2
    - Langmuir circulation
  * - 7.5.3
    - Ekman layers
  * - 7.5.4
    - Ekman transport convergence and wind stress curl
  * - 7.5.5
    - Observations of Ekman response and wind forcing
  * - 7.6
    - Geostrophic balance
  * - 7.6.1
    - Pressure gradient force and Coriolis force balance
  * - 7.6.2
    - Geopotential and dynamic height anomalies and reference level velocities
  * - 7.6.3
    - Dynamic topography and sea surface height maps
  * - 7.6.4
    - A two-layer ocean
  * - 7.7
    - Vorticity, potential vorticity, Rossby and Kelvin waves, and instabilities
  * - 7.7.1
    - Vorticity
  * - 7.7.2
    - Potential vorticity
  * - 7.7.3
    - Rossby waves
  * - 7.7.4
    - Rossby deformation radius and Rossby wave dispersion relation
  * - 7.7.5
    - Instability of geostrophic ocean currents
  * - 7.7.6
    - Kelvin waves
  * - 7.8
    - Wind-driven circulation: Sverdrup balance and western boundary currents
  * - 7.8.1
    - Sverdrup balance
  * - 7.8.2
    - Stommel’s solution: westward intensification and western boundary currents
  * - 7.8.3
    - Munk’s solution: western boundary currents
  * - 7.8.4
    - Fofonoff's solution: large-scale inertial currents
  * - 7.8.5
    - Wind-driven circulation in a stratified ocean
  * - 7.9
    - Wind-driven circulation: eastern boundary currents and equatorial circulation
  * - 7.9.1
    - Coastal upwelling and eastern boundary currents
  * - 7.9.2
    - Near-surface equatorial currents and Bjerknes feedback
  * - 7.10
    - Buoyancy (thermohaline) forcing and abyssal circulation
  * - 7.10.1
    - Buoyancy loss processes (diapycnal downwelling)
  * - 7.10.2
    - Diapycnal upwelling (buoyancy gain)
  * - 7.10.3
    - Stommel and Arons' solution: abyssal circulation and Deep Western Boundary Currents
  * - 7.10.4
    - Thermohaline oscillators: Stommel's solution
  * - 7.1
    - Introduction: mechanisms
  * - 7.2
    - Momentum balance
  * - 7.2.1
    - Acceleration and advection
  * - 7.2.2
    - Pressure gradient force and gravitational force
  * - 7.2.3
    - Rotation: centrifugal and Coriolis forces
  * - 7.2.4
    - Viscous force or dissipation
  * - 7.2.4.1
    - Molecular viscosity
  * - 7.2.4.2
    - Eddy viscosity
  * - 7.2.5
    - Mathematical expression of momentum balance
  * - 7.3
    - Temperature, salinity and density evolution
  * - 7.3.1
    - Temperature, salinity and density equations
  * - 7.3.2
    - Molecular and eddy diffusivity
  * - 7.4
    - Mixing layers
  * - 7.4.1
    - Surface mixed layer
  * - 7.4.2
    - Bottom mixed layers
  * - 7.4.3
    - Internal mixing layers
  * - 7.5
    - Response to wind forcing
  * - 7.5.1
    - Inertial currents
  * - 7.5.2
    - Langmuir circulation
  * - 7.5.3
    - Ekman layers
  * - 7.5.4
    - Ekman transport convergence and wind stress curl
  * - 7.5.5
    - Observations of Ekman response and wind forcing
  * - 7.6
    - Geostrophic balance
  * - 7.6.1
    - Pressure gradient force and Coriolis force balance
  * - 7.6.2
    - Geopotential and dynamic height anomalies and reference level velocities
  * - 7.6.3
    - Dynamic topography and sea surface height maps
  * - 7.6.4
    - A two-layer ocean
  * - 7.7
    - Vorticity, potential vorticity, Rossby and Kelvin waves, and instabilities
  * - 7.7.1
    - Vorticity
  * - 7.7.2
    - Potential vorticity
  * - 7.7.3
    - Rossby waves
  * - 7.7.4
    - Rossby deformation radius and Rossby wave dispersion relation
  * - 7.7.5
    - Instability of geostrophic ocean currents
  * - 7.7.6
    - Kelvin waves
  * - 7.8
    - Wind-driven circulation: Sverdrup balance and western boundary currents
  * - 7.8.1
    - Sverdrup balance
  * - 7.8.2
    - Stommel’s solution: westward intensification and western boundary currents
  * - 7.8.3
    - Munk’s solution: western boundary currents
  * - 7.8.4
    - Fofonoff's solution: large-scale inertial currents
  * - 7.8.5
    - Wind-driven circulation in a stratified ocean
  * - 7.9
    - Wind-driven circulation: eastern boundary currents and equatorial circulation
  * - 7.9.1
    - Coastal upwelling and eastern boundary currents
  * - 7.9.2
    - Near-surface equatorial currents and Bjerknes feedback
  * - 7.10
    - Buoyancy (thermohaline) forcing and abyssal circulation
  * - 7.10.1
    - Buoyancy loss processes (diapycnal downwelling)
  * - 7.10.2
    - Diapycnal upwelling (buoyancy gain)
  * - 7.10.3
    - Stommel and Arons' solution: abyssal circulation and Deep Western Boundary Currents
  * - 7.10.4
    - Thermohaline oscillators: Stommel's solution