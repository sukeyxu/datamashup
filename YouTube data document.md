##**YouTube Data Documentation**
***
####**File Name:** TouTube Data
***
####**Data Cleaning Assessment**
Some reviews are irrelavant with the brand and commercial. I will use Python to filter irrelavant reviews. The data format should be changed via Python (change to rectangular shape in the class) and OpenRefine (transform data type, handle missing data).  
Estimated time: 2-3 hours
***  
####**Provenance, Authorship, and Attribution**
- Provenance: youtube.com
- Authorship: youtube viewers
- Attribution: sukey used google api explorer got the data.
***
####**Content Description**
- Description: This data set contains most recent 100 comments from the reviews under the TV commercials launched by the Brand's official channel about the two TV commercials respectively.
- **A short statement about what is being used from this dataset.**
- Data Collection Date: 11/5/2018
***
####**Collection Process**
Used google API explorer to get most recent 100 reviews from brand channels since 11/5/2018. Selection information is needed such as the maximum number of the reviews and channel ID.
***
####**Data Structure**
- Records/Entities: Each row of the data set is a single tweet.
- Dimensions: 104 rows × 4 columns
- Codebook:
    - review_id: The review ID.
    - channel_id: channel ID.
    - videoid: The video ID from the channel.
    - review_content: The content of the review.
    - publish_time: The time that the review was posted.




















