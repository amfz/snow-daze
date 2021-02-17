# [Title]

## Original
[background]

## Redesign

Data to recreate Snow's map is freely available online. As Drucker (2011) writes, all data are capta, and what is captured in online, machine-readable datasets is strikingly sparse, reflecting what could be digitized from the map itself. Death data contains coordinates of where the victim lived, and occasionally, their actual street address (e.g. https://www.arcgis.com/home/item.html?id=f39a169103da4149ae577ccceec9d125); all of the sources I encountered fell short of the 596 deaths in Snow's study (Koch & Denike, 2010). In contrast, Snow's reports are rich with details of the neighborhood around Broad Street and its inhabitants; the dead there have names and habits (Snow, 1855). Meanwhile, Snow's table of cholera attacks and deaths by date has also been digitized, but there isn't enough information there to link individual death dates and residences. In other words, available data makes it straightforward to show _when_ people died or _where_ they lived, but not both together. Finally, pump locations and names from Snow's map are readily available.

**[PLACEHOLDER FOR SKETCHBOOK IMAGE]**

This sparsity ruled out several redesign ideas, some of which are shown above. Without dates for individual death points, I couldn't animate a map of rising death tolls. Lack of data on total building populations ruled out depicting death rates, which could have bolstered Snow's original argument by showing that the higher death count around the Broad Street pump was not solely due to higher population density. Likewise, detailed, structured information on where individuals mainly got their water could have been used in a visualization, but that data was not available either.  Finally, while it is possible to draw pump service areas based on modern London's road network, today's network differs from 1854's in both topology and travel speeds. Voronoi polygons, which divide up space into areas based on which point of interest is nearest, were another option. Snow himself employed a version of this technique for a later iteration of the cholera map (Koch & Denike, 2010).

I decided to focus on the deaths themselves, taking a fuzzier, more humanistic approach to try to represent the scale of loss: Snow's Soho study spans nearly 600 deaths over six weeks in less than a quarter square mile, while other accounts of the outbreak describe streets where nearly every house lost someone (http://kora.matrix.msu.edu/files/21/120/15-78-AB-22-johnsnow-a0a1f5-a_11479.pdf). To do this, I used the most complete death dataset I could find. I initially planned to overlay deaths on the original map to "decay" the streetscape, so that areas with higher death counts would look like they had been erased. However, the original map's stark black-and-white design left little to remove, so I found a contemporaneous map of London that was visually busier and georectified it for use as a basemap instead (Lowry, 1851). Deaths were grouped by address and symbolized as white circles that blur towards the edge, making it look like the underlying image was partially erased.

The resulting visualization, shown below, is still a map, but it works differently than the original. It is interpretive rather than persuasive. While the death symbols in the redesign are proportional -- larger circles indicate addresses with higher death counts -- they blur and overlap so that a viewer would not be able to quantify the deaths, even if a map legend were provided. That visual clutter of the new basemap makes the image loss more noticeable in the redesign, while the lightness of Snow's streets and blocks focus the viewer's attention to the deaths and pumps there.



## References
Esri, Inc. (2020). ArcGIS Pro (Version 2.7). https://www.esri.com/en-us/arcgis/products/arcgis-pro/overview.

Esri, Inc. (2020). Cholera cases [Data Set]. Retrieve dfrom https://www.arcgis.com/home/item.html?id=f39a169103da4149ae577ccceec9d125.

Koch, T., & Denike, K. (2010). Essential, Illustrative, or… Just Propaganda? Rethinking John Snow's Broad Street Map. Cartographica: The International Journal for Geographic Information and Geovisualization, 45(1), 19-31. Retrieved from http://www.ph.ucla.edu/epi/snow/catographica45(1)_19_31_2010.pdf.

Lowry, W. (1851). Map of London and its vicinity [map]. McMaster University Digital Archive. Retrieved from https://digitalarchive.mcmaster.ca/islandora/object/macrepo%3A81429

Snow, J. (1855). _On the mode of communication of cholera_. Churchill. Retrieved from https://play.google.com/books/reader?id=-N0_AAAAcAAJ&hl=en&pg=GBS.PA1.

Snow, J. (1855). _Report on the Cholera Outbreak in the Parish of St. James, Westminster during the Autumn of 1854. Churchill_. Retrieved from http://resource.nlm.nih.gov/34721190R 
