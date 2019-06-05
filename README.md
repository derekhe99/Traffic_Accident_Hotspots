# Traffic_Accident_Hotspots
Using Kernel Density Estimation to identify traffic accident hotspots for various cities in Texas (can be expanded to other states)

We seek to combat the generally held belief that there is little that can be done to curb driving accident rates, estimated to be at least 7 million per year in the United States. The number of fatalities has hovered well over 35,000 per year throughout the 21st century. 

We believe that a mobile app that informs drivers of the most dangerous locations on the road (determined through historical crash locations) and the factors that most contributed to the crashes (such as the time of day, the location of the impact, or the road condition), can decrease these traffic incidents. 

We optimized our hotspot identification method (kernel density estimation) and applied it to general-area analysis and route-specific analysis. General-area analysis lets drivers receive real-time reminders as they drive without stating their route; route-specific analysis allows users to silence audible notifications and see the hotspots on their route before they start driving. 

Images:
https://lh3.googleusercontent.com/-or-NDOm35AM/XBIRCOklnLI/AAAAAAAADBA/tdl92HQ6GRQbVNHis7OWFceJCe1xjm8AgCE0YBhgL/w2000/Screenshot_2018-12-13-01-21-08.png
https://lh3.googleusercontent.com/-pXwOdER9KlQ/XBIQ2WGSLRI/AAAAAAAADA4/EDDnGiC3qWQoA-slENySmP_qCiG41oDLwCE0YBhgL/w2000/Screenshot_2018-12-13-00-59-16.png

Summary of Results:

The algorithm has been tested with data from various urban and suburban locations in Texas successfully- can be applied to other states and locations too

Successfully and reliably outputs the top 35 hotspots in urban areas and top 20 hotspots in suburban areas

Developed and utilized bandwidth-optimization regression equation for maximum kernel density estimation accuracy

Route-specific method produces the top 10 hotspots per route
