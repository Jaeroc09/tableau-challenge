# tableau-challenge
Tableau Public visualization/analysis of NYC CityBike trip data (June 2023)

by Jason Estrada

## Analysis
Data was sourced from [City Bike Data](https://www.citibikenyc.com/system-data) and the trip data from June 2023 was analyzed and displayed in [Tableau Public](https://public.tableau.com/views/June2023CityBikeUsage/June2023-CityBikeUsage?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

Geographical coordinates of each ride's start and stop were overlayed onto a map of the New Jersey/New York area.
- Many users started their trip in suburban New Jersey (zip codes 07304, 07306, 07307).
- Many trips end in urban New Jersey (zip codes 07302, 07310, 07030).
- There are a few rides that end in Manhattan (noticeable on map, but only occur once per location in the month).
- Top station names where rides start/stop are "Grove St PATH", "Marin Light Rail", and "Hoboken Terminal", suggesting bikes are frequently used as part of a work commute using public transportation (rail or ferry).

The dashboard for top starting stations utilized a bar graph as well as a treemap to visualize the ride count frequency for the month.  For clearer visualization, the data was filtered to only show ride counts at stations greater than 100.  Similar to the map dashboard, starting stations "Grove St PATH", "Hoboken Terminal", and "South Waterfront Walkway" were very frequent in bike usage.  Hovering over the treemap's tooltip, the average trip duration for these stations are mostly under 10 minutes.  There may be a strong correlation that regular subscribers (members) of City Bike use the bikes as part of a work commute, however further analysis is needed.