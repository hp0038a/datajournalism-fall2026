# DC Crime Data
1. Question: What types of recorded crime are most common within one mile of American University's campus, and how do the pattens differ depending on the time of day?
This question is newsworthy for the AU community because students, faculty, and staff live, work, and travel around the AU campus consistently. Understanding the offenses that are reported most frequently as well as when they occur could help students make informed decisions about their routines and could also provide them with useful context for discussions regarding campus safety. Additionally, the findings may also help to identify patterns that could call for more investigation or could be a bigger deal.

2. Steps taken
We used the DC crime dataset and opened it as a CSV file in Excel. Once we had the dataset in the spreadsheet, we inserted a PivotTable, and placed offense-text in the Rows section and SHIFT in the Columns section. We then placed offense-text in the Values section and set it to Count to count the number of records for each offense type and shift. We used the row and column totals to compare the frequency of different offenses and identify patterns across the day, evening and midnight shifts.
The dataset contained 2,156 reported crime records. Theft/other was the most frequently reported offense with 1,271 records, followed by theft from auto, with 615 records. These two categories together accounted for most of the reports in the dataset. These findings indicate that theft-related offenses made up the largest portion of reported crime in the dataset and that reported offenses varied depending on shift. The numbers, however, represent recorded reports rather than the actual risk of experiencing a crime. The data by itself can't explain why these patterns occurred or establish that one shift it more dangerous than another. 

# Final Project Data
1. Original dataset: _________. 
2. We reviewed the columns first and determined which variables were relevant to the question: Do Capital Bikeshare members and casual riders differ in their use of electric bikes versus classic bikes?
 The variables used were: ride_id, rideable_type, member_casual. We did not need to remove the rows with missing station information because that information wasn't relevant to the research question. We also didn't need to change the bike-type or rider-type categories because they were already organized into usable categories.
3. Question: Do Capital Bikeshare members and casual riders differ in their use of electric bikes versus classic bikes?
   This question is newsworthy because Capital Bikeshare is a major form of transportation in the Washington D.C. region, and the system offers both classic and electric bikes. The comparison is relevant because Capital Bikeshare's pricing differs between classic bikes and e-bikes, and members receive discounted e-bike rates and other benefits. Looking at whether members and casual riders use e-bikes at different rates and provide information about how different types of riders are utilizing the bikeshare system.
4. We used Excel to create a PivotTable
   1. Opened the Capital Bikeshare September 2026 dataset in Excel
   2. Selected the full dataset
   3. Inserted a PivotTable in a new worksheet
   4. Put member_casual into the Rows section
   5. Put rideable_type into the Columns section
   6. Put ride_id into the Values section
   7. Changed the Values field to Count of ride_id so that the PivotTable counted the number of rides
   8. Compared the number of electric bike and classic bike rides for members and casual riders
5. Both members and casual riders used electric bikes far more often than classic bikes. Casual riders took 139,538 e-bike trips compared with 53,523 classic bike trips. Electric bikes therefore made up about 72.3% of casual riders' trips. Members took 343,412 e-bike trips compared with 140,335 classic bike trips. Electric bikes made up about 71% of members' trips. The results show that e-bike use was common among both groups; casual riders had a higher percentage of e-bike trips than members at 72.3% compared with 71%. Overall, the data shows that e-bike use is not limited to casual riders.

# What has already been reported?
Capital Bikeshare's growing use of e-bikes has been covered by local transportation reporters. Recent Greater Greater Washington reports have found that e-bikes are now the most popular type of Capital Bikeshare bike. In July 2025, e-bikes accounted for 62.2% of rides, while members accounted for 69.2%. The report also found that members used e-bikes for 65.4% of their rides, compared with 55% for casual riders.
More recent reporting found that e-bikes made up 67.5% of Capital Bikeshare trips in April 2026, while annual members accounted for 70.5% of trips.
The Washington Post has also reported on Capital Bikeshare's e-bike popularity and pricing. In 2025, e-bikes made up about 30% of the fleet but 60% of usage, contributing to higher operating costs and a major price increase.
An older 2018 analysis found that members took 99% of e-bike trips during Capital Bikeshare's original e-bike pilot.

Most of the recent coverage focuses on overall ridership, monthly trends, pricing and broad differences between members and casual riders.
Our project will use 676,808 individual Capital Bikeshare trips from September 2026 to conduct my own analysis of e-bike and classic-bike use.
The initial PivotTable found that 72.3% of casual riders' trips and 71.0% of members' trips were on e-bikes. This is different from some earlier reporting and gives me a current data point to investigate further.
We want to explore what these patterns look like in the September 2026 data and potentially examine differences by location, time or other variables available in the dataset.
Potential datasets:
1. Capital Bikeshare Trip History Data
Source: Capital Bikeshare (https://capitalbikeshare.com/system-data)
This is the official trip-level data from Capital Bikeshare and includes information such as trip times, stations, bike type and member type. It is trustworthy because it comes directly from the organization operating the system.
Limitation: The current dataset only covers September 2026, so it can't show long-term trends on its own.
2. Capital Bikeshare Station Data (https://capitalbikeshare.com/system-data)
Source: Capital Bikeshare
Station information could be used with the trip data to examine where e-bike and classic-bike trips are concentrated.
Limitation: Station data shows locations but does not explain why people use particular stations or provide individual rider demographics.
3. American Community Survey (https://www.census.gov/data/developers/data-sets/acs-5year/2024.html)
Source: U.S. Census Bureau
ACS data could provide neighborhood information such as income, race, commuting patterns and other demographics that could be compared with Capital Bikeshare station and trip data.
Limitation: Census data describes neighborhoods, not individual bikeshare riders, so we could not assume that a particular rider has the characteristics of the neighborhood where they began a trip.
