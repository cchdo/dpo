Example S6A: Before We Get Started
==================================
In the exercises related to DPO Chapters S6, we will explore the difference in depiction of ocean temperature, salinity, dissolved oxygen, and density when viewed via data from bottle casts, CTD casts, and statistically-compiled multi-year average data (WOA09). First we will examine the three data types at one location (one profile per data type), and then we will examine the depiction of a vertical section via each of the three data types.

.. admonition:: Learn More
  :class: seealso

  CTD profiling and CTD data files

  (See DPO text Chapter S6.4 for general information about CTD profiling.)

  Although it is tempting to think that CTD electronic profiling instruments produce a continuous data stream, in fact, the data stream from the sensors is broken up into data packets.

  The native resolution of the CTD instrument most commonly used in “blue water” oceanography in 2007 was 24 Hz, meaning, more or less, that a packet of data containing one measurement from each primary sensor (pressure, temperature, and conductivity) is sent to the computer 24 times each second.

  The typical deployment (and haul) speed for a CTD is about 60 meters of wire out (or in) per minute, and a typical ocean depth is 4000 meters, meaning that the data file for a typical down and up CTD profile contains more than 170,000 raw data packets.
  
  If equally distributed vertically throughout the 8000 meters down and up, this would be about one data packet every 5 cm; however, the practical vertical resolution of a CTD electronic profiling instrument mounted on a large rosette frame [e.g., see DPO Figure 6.18] is limited by several factors. One especially limiting factor is that the instrument package is deployed from a rolling ship and so does not traverse the water column at a steady rate; meanwhile, the hardware of the rosette package is throwing off wakes.
  
  There is also the matter that each CTD sensor has its own response time lag and is physically separated from the other sensors. Thus, for these and other reasons, typical raw deep ocean CTD profiles for reference-quality cruises are processed via the CTD computer to report one data record every 2 decibars. Only the down casts are reported into data archives - there are good reasons for this - but even so, a single 'down' profile through a 4000 meter water column would contain 2000 records.
  
  Hence, even with this near 99% reduction in data volume, a final, processed CTD profile potentially contains a large amount of data.
  
  Java OceanAtlas can deal with this typical level of CTD cast data detail, but considering the status of Java implementation in 2008, use of more than ca. 100 full-resolution processed CTD profiles at one time in JOA can seriously slow a user's computer and may require impressive amounts of computer RAM.
  
  The large size of CTD data files is one reason we do not supply more of them routinely in these DPO JOA Examples. Fortunately, the principal large-scale variations in water properties can be easily seen with far lower vertical resolution.
  
  In most ocean regions, vertical resolution akin to the following provides good resolution of the principal variations in water properties:

  +---------------------+
  | Pressure (decibars) |
  +=====================+
  | 0                   |
  +---------------------+
  | 10                  |
  +---------------------+
  | 20                  |
  +---------------------+
  | 30                  |
  +---------------------+
  | 50                  |
  +---------------------+
  | 75                  |
  +---------------------+
  | 100                 |
  +---------------------+
  | 125                 |
  +---------------------+
  | 150                 |
  +---------------------+
  | 175                 |
  +---------------------+
  | 200                 |
  +---------------------+
  | 225                 |
  +---------------------+
  | 250                 |
  +---------------------+
  | 300                 |
  +---------------------+
  | 350                 |
  +---------------------+
  | 400                 |
  +---------------------+
  | 450                 |
  +---------------------+
  | 500                 |
  +---------------------+
  | 600                 |
  +---------------------+
  | 700                 |
  +---------------------+
  | 800                 |
  +---------------------+
  | 1000                |
  +---------------------+
  | 1200                |
  +---------------------+
  | 1400                |
  +---------------------+
  | 1600                |
  +---------------------+
  | 1800                |
  +---------------------+
  | 2000                |
  +---------------------+
  | 2250                |
  +---------------------+
  | 2500                |
  +---------------------+
  | 3000                |
  +---------------------+
  | 3250                |
  +---------------------+

  Continuing at 250db intervals to the bottom (ca. 10 meters above bottom is the usual safe maximum lowering level), but adding values at ca. 50 and 100 meters above bottom.