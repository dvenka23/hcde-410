# HCDE410
Files for HCDE410 - Assignment A1
# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St
**Source:** https://data.seattle.gov/resource/2z5v-ecg8 (pulled 2026-20-06)
**License / terms of use:** Public Domain

## Questions I asked
1) In terms of busiest--what is considered busiest? We said it's when there wa sth most number of users on average between bikes AND pedestrians so we weren't allowing the data to skew in favor of one group much more than the other.
2) Do cyclists and pedestrians use the trail at different times? We compared the habits of the two and found the peaks for both groups and determined that the peaks show "business" for each group so when that differed, individual use differed.
3) We decided that the best way to determind teh reason for trail use was to look at timings. Most commuters would work a 9-5 so we checked trail use at 8am and 6pm on weekdays and weekends to check for patterns there.
4) In terms of the direction of travel: honestly we were kind of stumped as to why people were going in the direction that they were but it made us check a map to see where the trail actually laid and how that could impact flow based on the landmarks we saw on the map. Also what is considered north vs. south on the trail when the trail entered horizontal paths?

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
Adapted from # cdsw-2020 https://wiki.communitydata.science/Seattle_open_data

## Additional Information
I also worked with peers on this project: Ella Gebers and Ariel Lin.