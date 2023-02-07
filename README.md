# Solar Farm Planner

A project I recently completed was a solar farm location planner for Alberta. Alberta is currently experiencing a rapid increase of solar panel farms so I made tool to identify where the best locations to install a solar panel farm are.

I used the geospatial software ArcGIS in combination with data from the Government of Alberta and AESO. My final product is a series of maps identifying 4 locations that I would consider to be the best spots for a solar panel farm. I presented this information in the form of publicly available maps and a locally hosted website.

When making this project I had three priorities:

Maximize Daily Energy Production:
In order to maximize the return on investment, a solar panel farm must collect as much sunlight as possible to maximize energy production. To do this, I prioritized areas in Alberta that have high annular solar radiation reaching the land. Additionally, using a digital elevation model any slope that was North facing was rejected as a possible location.
Minimize Start-Up Costs:
Solar panel farms can be an expensive investment so I looked for areas that could help keep those costs low. Firstly, I only looked at areas near high voltage power lines. This would be to ensure that a farm could connect to the energy grid without the need for additional infrastructure. Additionally, I prioritized areas around power substations that can handle an increased energy generation load. Finally, I narrowed my search to areas already used for agricultural use as that would minimize costs such as deforesting.
Minimize Impact on Environment:
Solar farms take up a lot of area, with that much area things like animal wildlife corridors or critical habitat could be disrupted. In my location selection I prioritized areas that have been indicated to be low priority wildlife as well as protected or forested areas.

With these goals set I then performed many geoprocessing operations to combine the data to create a final map. This final map displays approximately 5km x 5km grid squares that highlight excellent areas to install a solar panel farm.

If you would like to see the final map:
https://arcg.is/1DGKKX
If you would like to see a more detailed outline of the steps I took:
https://lnkd.in/gUhp6p9S


I am always happy to chat if you have any questions about this geospatial project!
