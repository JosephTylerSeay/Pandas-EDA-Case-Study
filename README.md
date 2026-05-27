# Pandas-EDA-Case-Study

Given datasets about top trending YouTube videos in different countries for our date range, we built a program that can compare trending categories among selected countries. For our exploration, we chose the USA and Russia to compare. The functions are built to take in any dataset of the same structure. Available on Kaggle are also: 
- Canada 
- Germany
- France
- Great Britain
- India
- Japan
- South Korea
- Mexico

Our work is contained in the `project.ipynb` file. To begin, we import `pandas`, `matplotlib`, and `numpy`. Next, we define the functions we need to clean each dataset and plot data.

Next, we introduced the US and Russia datasets and ran the cleaning functions on each. The cleaning functions convert the date columns to datetime type, and drop unnecessary columns: 
- thumbnail_link
- video_id
- comments_disabled
- description
- ratings_disabled
- video_error_or_removed

Lastly, our exploration section. Here, we experimented with a few different visualizations to understand our data and see the relationship between US viewership and Russian viewership.

### Findings:
- Music is significantly less popular in Russia than in the US
- Entertainment is essentially equal between the two.
- News and Politics, People and Blogs are far more popular in Russia

### Inferences:
- Russians need a lot more help fixing their cars than people in the US.
- An Amero-Russian YouTuber would probably be most successful focusing on the Entertainment category, which has over 20% of all views in each country.
- Americans love to stream music on YouTube.
