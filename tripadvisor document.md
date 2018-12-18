##**TripAdvisor Data Documentation**
***
####**File Name:** TripAdvisor TV Commercial Data
***
####**Data Cleaning Assessment**
This file is pretty established when I get it. But the format is still problematic. There are some narrative documentation and description about the file above the table. I need to move them to another text file for future reference. And I also deleted some irrelavant columns. Some works are expected to be done, when I get other data and try to combine data sets together.  
data cleaning time: less than 15 mins.
***  
####**Provenance, Authorship, and Attribution**
- Provenance: This data set is downloaded from a TV commercial analyzing company named [alphonso](https://insights.alphonso.tv/).
- Authorship: The primary authorship belongs to alphonso. I reform the table a little bit.
- Attribution: Myself
***
####**Content Description**
- Description: This data set contain 5957 records of Airing data of a single TV commercial named TripAdvisor "A Price That Fits" during Apr. 1st, 2018 - Sep. 15th, 2018.  
- **A short statement about what is being used from this dataset.**
- Data Collection Date: 9/15/2018
***
####**Collection Process**
I directly downloaded the data set from the alphone website.
***
####**Data Structure**

- Records/Entities: Each row of the data set is a single airing of the commercial on TV.
- Dimensions: 5957 rows (obervations), 13 columns (properties)
- Codebook:
    - Network Type: Network Type of the network. (cable or broadcast) String Type, categorical.
    - Show: The show that the TV commercial is played in the middle or ahead. String Type.
    - Date: The date that the airing is on. Date Type.
    - Dayparts: The time slot of the day of the airing. String Type, categorical.
    - Duration: The total seconds of the airing. integer type.
    - Broadcast Year: The year of the airing. date type.
    - Broadcast Month: The month of the airing. date type.
    - Broadcast Week: The week number of the airing. The calculation of the week starts from the begining of the year. integer type.
    - Day Of Week: The day of week of airing. The day of the airing in a week. 1 stands for Monday and so on. integer type. categorical.
    - Hour Of Day: The hour of day of airing. (range:0-23) integer type. categorical.



















