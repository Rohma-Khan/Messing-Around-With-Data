# Messing-Around-With-Data
I watched the previous U.S. election and wanted to see how they came up with the maps they did so I decided to make a map myself! 

Using data from: https://electionlab.mit.edu/data
and geographic boundary data from the US Census : https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html.

I created a 2016 US presidential election map. I wanted to create a map that showed a truer view of variation in voting. I find with the US elections each state is often treated like a monolith being either a blue state or a red state. Being from NYC I know that some counties vote differently than the overall state does and that even within some counties there is about a 40-ish percent vote for the other party as well. The 2016 map I made shows the difference in percentages of voting. Heavily democratic counties are still blue and heavily republican counties are still red but counties where there is a closer split in votes are white/light blue/ light red.


I elected to put in all the mistakes I've made in this as well as a cleaned up version of my code! I used geoviews/geopandas and pandas to work with the data and create the map. I received a 'Warning' many, many times working with geoviews (as you can see since I've left them in and theres a LOT). The error was specifically with 'bokeh' but since it still created a finished product I was okay with, I didn't bother with figuring out where or why the 'Warning's where coming from. The issue was most likely an issue with incompatible versions of 'params', 'bokeh', 'geopandas', or 'geoviews'. I updated all the packages and their needed dependencies but when the "Warning" still appeared I left it as is and kept on going.

The maps I've saved in an interactive html format (thanks bokeh!). The final version is titled "2016_pres_election_map_of_counties_final.html" and there is a png image just called "maps.png" that also looks nice in my opinion. (To see click on this link: https://rohma-khan.github.io/Messing-Around-With-Data/ ).

Personally this was supposed to be a fun project for myself to do. I might create a website to broadcast the data in a better way. I also might make a map of the 2020 election ... or the previous elections. Should I actually do that I'd have to figure out where/why the 'Warning's are coming from so I'll keep you all updated!
