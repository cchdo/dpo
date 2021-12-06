JOA Glossary
============

.. glossary::

   ARGO
     Argo is a global array of approximately 3,000 free-drifting profiling floats that each measure the temperature and salinity of the upper 2000 m of the ocean.
     This allows, for the first time, continuous monitoring of the temperature, salinity, and velocity of the upper ocean, with all data being relayed and made publicly available within hours after collection.

   Bottle data
      Originate from water sample bottles attached to a lowered wire or group mounted on a frame (called a rosette water sampler) attached to a lowered wire, which are closed at chosen levels, isolating water samples then subsampled shipboard for various parameters such as dissolved gasses (salinity, oxygen, etc), dissolved inorganic nutrients and other substances.

   CLIVAR (Climate Variability and Predictability)
     A component of the World Climate Research Programme (WCRP) project that addresses Climate Variability and Predictability, with a particular focus on the role of ocean-atmosphere interactions in climate.
     It works closely with its companion WCRP projects on issues such as the role of the land surface, snow and ice and the role of stratospheric processes in climate.

   CTD data (Conductivity, Pressure, Depth)
      Originate from semi-continuous sampling electronic profilers which are lowered into the ocean, recording output typically from pressure, conductivity and temperature sensors, other sensors may also be included. 
      Deep ocean CTD data are typically collected with a sampling rate of 24 Hz, at a profiling speed of about 60-70 meters/minute and post-casts are processed into records every two decibars (approximately every two meters) throughout the profile, meaning up to ca. 40-50 records may contribute to each reported two-decibar level. 
      Most modern bottle data includes data parameters from the CTD sensors recorded at the time the bottle was closed.

   Data window (JOA)
      Contains data display keyed to current x-z location in the data, current color bar (with arrow indicating color for current x-z location), and section display illustrating all data points in current section(s).

   Far-field (horizontal) interpolation (JOA)
      If a bounding observation in the current cast is missing, this option directs JOA to use up to n surrounding casts (before and after) to interpolate a value for the missing value. 
      It does this by first calculating the horizontal gradient of the contour parameter near the depth of the missing observation and secondly using the gradient to create virtual observations of the contour parameter at the current profile. 
      The closest virtual observation to the missing value is then used to interpolate the contour parameter to the surface level. 
      A 'Maximum distance' option is provided so that in cases of uneven station distribution along a track, Java OceanAtlas can be restricted from looking unrealistically far away for datato complete an interpolation.

   GODAE (Global Ocean Data Assimilation Experiment)
      Investigates and implements the capabilities to make ocean monitoring and prediction a routine activity similar to weather forecasting. GODAE will contribute to an information system for the global ocean that will serve interests from climate change and coastal preservation through to fisheries and the off-shore industry.

   Isopycnals
      A surface of constant potential density of water. 
      In the ocean, as the depth increases, so too does the density. 
      Salinity and temperature act to modify the density of water, and the denser water always lies below the less dense water. 
      Because of the action of winds and currents, isopycnals are not always level. 
      In ocean mixing, it is easier to mix water along an isopycnal rather than across it because it takes no work. 
      Information on ocean circulation can be inferred from studying isopycnal surfaces. 
      Isopycnals can also be drawn on temperature-salinity plots.

   Latitude
      Lines of latitude circle the globe parallel to the equator (0°) as degrees north to the north pole (90°N) or degrees south to the south pole (90°S). 
      Use positive values for north latitude and negative for south latitude.

   Left hand coordinate system
      The z-axis increases down, with positive y to the left of positive x.

   Longitude
      Lines of longitude circle the globe perpendicular to the equator and are expressed relative to the Greenwich meridian (0°) as degrees east or west and opposite from 0° longitude to 180°. 
      Use positive values for east longitude and negative for west longitude, i.e. 0 to 180 east and 0 to -180 west.

   Menu Bar (JOA)
      * **File → Open** : Open a new data file.
      * **File → Add** : Add or append a new data file to the presently-open data file(s).
      * **'Plots'** : contains the selections for the basic plot types supported by Java OceanAtlas.
      * **'Calculations'** : contains the interfaces for basic parameter calculations (i.e. potential temperature and density) and custom parameters.
      * **'Filters'** : contains the interfaces for filtering the data by station/region or by value limits of parameters.
      * **'Resources'** : Contains the interfaces for creating and modifying the color/contour bar, color palettes, levels used for vertical interpolations and preferences.

   Meridian
      Used in oceanography for longitude

   Meridional currents
      Ocean currents in a generally north-south direction

   Meridional section
      A line or section of oceanographic stations near a single longitude that is used to illustrate the variations in seawater characteristic between zones (e.g., the equator, tropics, sub-tropics, subpolar, polar zones).

   Nitrate
      Is heavily involved in ocean biochemical cycles. For example, phytoplankton require nitrogen and obtain it from nitrate when it is available. 
      This depletes nitrate in areas where photosynthetic production is or was active. 
      And when organic matter in the oceans decays (in a process called respiration), oxygen is used up and the nutrients are released. 
      In some very low-oxygen waters, the bacteria which are decaying the organic matter must obtain oxygen from nitrate to continue respiration. 
      This locally denitrifies the seawater.

   Oceanographic section
      A series of profiles/stations across an oceangraphic region or feature.

   Phosphate
      Phosphate is a nutrient heavily involved in ocean biochemical cycles. 
      Its uptake in photosynthesis and release in respiration are usually so closely tied to those of nitrate that their ratio of variability is quite close to constant, especially in a single ocean region. 
      But, to first order, in low-oxygen waters, the bacteria which are decaying the organic matter, when obtaining oxygen from nitrate, do not obtain oxygen from phosphate to continue respiration. 
      Thus the ratio of phosphate to nitrate is altered in those circumstances.

   Plots (JOA)
      * **'Property-property'** : Produce basic X-Y plots. Data points are colored by the current color/contour as in the Data Window.
      * **'Profile'** : Produce X-Y plots with each station offset from the previous by a constant or proportional amount/distance. 
        The plot is colored by the current color/contour bar in the Data Window.
      * **'Map'** : Produce maps of station positions. Features include manipulation of projections, isobath, gridded bathymetry, selection of symbol size, etc.
      * **'Contour'** : Produce traditional vertical section plots made from interpolations of any parameter onto standard levels of a chosen parameter.
        Plots are responsive to choices made under observation filters. EX: A contour plot of salinity on pressure, under an observation filter within the range 26.4 < sigma-0 < 27.6 will only color the section portion within the specified density range.

   Pressure
      Before electronic profiling devices came into common use, the vertical reference used for most oceanographic profiles was depth, measured from the sea surface downward, typically in meters. 
      Electronic profiling devices often contain a pressure sensor, the output of which is most commonly translated into decibars (tenths of a bar). 
      Pressure expressed in decibars is numerically close to depth expressed in meters. 
      Pressure is not the same as depth and it is important to remember the distinction between the two.

   Profile
      Are collected from a ship which stopped at a specific location. The principle types of profile data are bottle and CTD data.

   Quasi-synoptic sections
      A single ship transect, or any other assembled from data taken close together in time.

   Referenced Interpolations (JOA)
      Referencing an interpolation to the value of the interpolated parameter of a standard level or to a mean cast.

   Section
      A line of stations across a region. 
      An abbreviation of cross-section.

   Stations
      Location where data profiles are collected from a ship. 
      Profiles and stations can in some cases be used interchangeably.

   Vertical sections
      Vertically-oriented slices through the ocean.

   Vertical interpolations (JOA)
      JOA looks for observations that bound a standard level to interpolate to that level. 
      If one of the bounding observations in missing, this option directs JOA to look n number of observations below or above (depending upon the interpolation direction) in the profile for a non-missing value. 
      A Maximum number of observations option is provided to limit the number of observations away the interpolator will look for a non-missing value. 
      This is most useful for bottle profiles where the vertical spacing of bottles increases with depth.

   World Ocean Circulation Experiment (WOCE)
      A component of the World Climate Research Program (WCRP), which aimed to establish the role of the oceans in the earths climate and to obtain a baseline dataset against which future change could be assessed. 
      Sophisticated ocean models were also developed to provide a framework for the interpretation of the observations and for the prediction of the future ocean state.

      About 30 nations participated in the observational program, using ships to make physical and chemical observations, and employing moored and drifting instrumentation. 
      Global observations were also madre from satellites. 
      The field phase of the projec lasted from 1990-1998 and was followed by Analysis, Interpretation, Modeling, and Synthesis activities. 
      The AIMS phase of WOCE, officially continued until the end of 2002.

      On the completion of WOCE other large-scale projects which involve the ocean and climate were pursued. 
      Among them are: CLIVAR, a global study of the earths climate variability and predictability, GODAE, the Global Ocean Data Assimilation Experiment, and ARGO, a global array of temperature/salinity profiling floats.

      Although there is meaning to some parts of the WOCE transect names (e.g., A, P, I, and S stand for Atlantic, Pacific, Indian, and Southern, respectively), the WOCE line numbering scheme is not heavy with additional meaning.

   Zonal section
      A line or serction of oceanographic stations near or on a single latitude. 
      Such sections help illustrate where the oceans exchange between climate zones; zonal sections can be used to calculate fluxes and transports between climate zones.

   Zonal currents
      Ocean currents in a generally east-west direction.