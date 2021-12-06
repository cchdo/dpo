Example 9-14A: Before we get started
====================================
DPO Chapters 9-13 discuss the water masses, circulation and other aspects of the descriptive physical oceanography of each of the principal oceans and their marginal seas, with a discussion of global subjects provided in Chapter 14 and climate and ocean topics in Chapter S15.

We use nearly the same approach to using Java OceanAtlas to illuminate the oceanographic features of each ocean. Thus we provide here an overview of the DPO Examples data files and tools which should prove useful for DPO Chapters 9-14.

For each of the regional chapters (9-13), we provide:

* **one or more gridded, full-resolution data sets from WOA09 which cover the region**

  These are at the full WOA09 lateral resolution of one degree of latitude and one degree of longitude, but with no grid points retained over land, below the ocean bottom, or any other region where there are no water column data.

  .. note::

    We are in the process of updating the WOA05 data files to WOA09. Some on-line data files for the JOA DPO Examples have an "05" instead of the "09" shown here. This is of no consequence to the use of the WOA data files in the JOA DPO Examples.

* **one or more gridded, decimated (reduced-resolution) data sets from WOA09 which cover the region**

  These are at the full WOA09 lateral resolution of one degree of latitude and one degree of longitude in the tropics and subtropics, but with values at half of the longitudes removed poleward of 60 degrees, another half removed poleward of 75 degrees, and yet another half removed poleward of 85 degrees, and with no data points retained over land. This reduces the file size from the original WOA09 by reducing WOA09's horizontally closely-spaced grid points at higher latitudes (where lines of longitude come closer together).

* **(optional) a gridded, heavily decimated data set from WOA98 which covers the region**

  These are at half WOA98 lateral resolution of one degree of latitude and one degree of longitude in the tropics and subtropics, with values at half of those longitudes removed poleward of 60 degrees, another half removed poleward of 75 degrees, and yet another half removed poleward of 85 degrees, and with no data points retained over land. Also, these are saved in an older binary format (".poa") which has a smaller file size. This greatly reduces the file size from the WOA09 version. JOA will load and run these files quickly, which is useful on slower computers and/or those with less RAM, and is also useful for displaying the entire World Ocean in one data set efficiently on any computer.

* **data from basin-scale transects from recent oceanographic expeditions**

  These were selected on the basis of their high data quality, their inclusion of oxygen, nutrient, CFC, and ocean carbon data, and their basin-spanning paths. We prepared both bottle and CTD data from each transect (usually the CTD data are decimated to reduce file size), cleaning bad and questionable data from the files, and eliminating stations and casts not part of the principal transect path of interest.

* **data from useful basin-scale transects from older oceanographic expeditions**
  
  These were selected on the basis of their location, high data quality, inclusion of oxygen and nutrient data, and their basin-spanning paths. Most of the older cruises have bottle data only, and for many we have cleaned bad and questionable data from the files, and eliminated stations and casts not part of the principal transect path of interest. Some of the older cruise tracks are nearly co-located with those from more recent cruises, and thus can be used to examine seawater property changes over the intervals between expeditions.

  .. note::

    To examine the difference between two co-located transect data sets, please see "Section Difference" under "Section Calculations" in the JOA User Guide for techniques to subtract one section from another.

* **WOA09 profiles following the same track as the basin-scale transects, above**
  
  These present a multi-year averaged depiction of temperature, salinity, oxygen, and nutrients along each transect, at the WOA09 native one-degree resolution.

For the World Ocean chapter (Chapter 14) we provide:

* **A gridded, full-resolution data set from WOA09 which covers the entire World Ocean**

  This is at the full WOA09 lateral resolution of one degree of latitude and one degree of longitude, but with no grid points retained over land, below the ocean bottom, or any other region where there are no water column data. In order to get this very large file to load within the limitations of JOA, we have saved it in an older, more compact format (".poa") which JOA can open. Use of this very large data set may greatly slow down the response of your computer.

* **A gridded, decimated (reduced-resolution) data set from WOA09 which covers the entire World Ocean**

  This is at the full WOA09 lateral resolution of one degree of latitude and one degree of longitude in the tropics and subtropics, but with values at half of the longitudes removed poleward of 60 degrees, another half removed poleward of 75 degrees, and yet another half removed poleward of 85 degrees, and with no data points retained over land. This reduces the file size from the original WOA09 by not reducing very closely-spaced grid points at higher latitudes (where lines of longitude come closer together). This is a large data set and may slow down the response of your computer.

* **A gridded, heavily decimated data set from WOA98 which covers the entire World Ocean**

  This is at half WOA98 lateral resolution of one degree of latitude and one degree of longitude in the tropics and subtropics, with values at half of those longitudes removed poleward of 60 degrees, another half removed poleward of 75 degrees, and yet another half removed poleward of 85 degrees, and with no data points retained over land. Also, these are saved in an older binary format (".poa") which has a smaller file size. This greatly reduces the file size from the WOA09 versions, so will load and run quickly on slower computers with less RAM.

* **Meridional sections from WOA09 every 10 degrees of longitude and zonal sections every 5 degrees of latitude**

  These are provided to fill out global data coverage. The zonal sections (the ones along constant lines of latitude) permit easy comparison of each of the oceans from a single data file. Note, however, that due to the one-degree horizontal resolution of WOA09, most boundary currents - which are narrow - are not resolved in WOA09 data.

* **"Grand Tour of the Oceans" bottle and CTD data files (and a section made from WOA09 grid points following the same path)**

  The "Grand Tour of the Oceans" is an edited collection of oceanographic bottle and CTD data files which, when assembled, create a transect of the ocean from the northwestern Ross Sea near the Antarctic continent north through the Pacific Ocean and Bering Strait, across the Arctic Ocean over the North Pole and through the Nordic Seas, south through the Atlantic Ocean, and ending at the Antarctic continent in the Weddell Sea. The Grand Tour provide a unique "real data" (as opposed to averaged data such as WOA09) examination of two principal oceans (the Pacific and Atlantic) along with the interesting Arctic region. The section's pathways are determined more by the availability of appropriate data than by an ideal for illustration of water masses and circulation, yet the Grand Tour yields useful multi-ocean comparisons. The Grand Tour bottle data file includes these measured parameters: temperature, salinity, dissolved oxygen, nutrients (NO3, PO4, and SiO3), CFC-11, CFC-12, dissolved inorganic carbon, and total alkalinity. [The Grand Tour ocean data files include a "2" designation (e.g., "Ocean_Grand_Tour_2_bottle.joa") to distinguish them from an earlier Grand Tour assembled by Swift, which follows a different path.] We also provide a section following the same path as the Grand Tour, but assembled from the closest WOA09 averaged data grid points to the station track. This provides an opportunity both to view long-term averaged data along the track and to examine over a large region the many differences in depiction of gradients and boundaries between data from oceanographic expeditions and mathematically-constructed gridded data.