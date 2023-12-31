# Social Network Analysis : study case of a Facebook group of diabetes in Morocco

## Project Overview

This project utilizes Social Network Analysis (SNA) to delve into the structure and dynamics of a Facebook group dedicated to diabetes in Morocco. The primary objective is to gain valuable insights into the experiences and needs of individuals grappling with diabetes in the region. Additionally, the project aims to pinpoint areas for potential improvement in terms of support and resources.

## Findings

The study unveiled an active and engaged community within the Facebook group, demonstrating members' willingness to share information, offer emotional support, and foster a sense of community. This underscores the potential of social media platforms like Facebook in promoting health and supporting those with chronic conditions.

## Data Collection

- The Facebook group was established on January 30, 2021, boasting over 4,500 users at the time of the study—making it one of the largest diabetes-focused groups in Morocco on Facebook.
- Data collection was accomplished through web scraping, employing the `facebook-scraper` tool. Refer to the [`Scraping_Code.ipynb`](Scraping_Code.ipynb) file for the code.

## Data Cleaning

Post data collection, several cleaning operations were executed:

- Removal of duplicated data.
- Deletion of columns with excessive missing values or non-informative content (e.g., image and video links).
- Text data cleaning involving the elimination of special characters, numbers, and punctuation to prepare the data for subsequent content analysis.

## Data Visualization

Following data collection and cleaning, the project transitioned into the data visualization and structure analysis phase. This pivotal step aids in extracting insights from the data by unveiling patterns, trends, and relationships. The [`Data_Visualization_And_Structure_Analysis.ipynb`](Data_Visualization_And_Structure_Analysis.ipynb) notebook contains detailed information on this phase.

The included figure below illustrates the network of reactions, portraying each node as a group member and edges symbolizing interactions between them.

![Network Graph of User Reactions](fig/NetworkGraphOfUserReactions.png)
## Data Analysis

The project goes beyond visualization to extract deeper insights from the data by analyzing both the structure of the interactions between group members and the content of their posts.

### Structure Analysis

- Analyze the structure of the Facebook group network using centrality measures.

### Content Analysis

- Analyzing textual data to derive insights, patterns, and themes.
- Analyze Moroccan Darija comments content. Moroccan Darija is a dialect of Arabic widely spoken in Morocco. The aim of this analysis is to gain insights into the language, sentiments, and topics discussed in these comments. The [`Content_Analysis.ipynb`](Content_Analysis.ipynb) notebook contains detailed information on this phase.

## Further Steps

In continuation of this project, the following steps are envisioned:

1. **Community Engagement:** Develop strategies to foster more active participation and engagement within the Facebook group.

2. **Enhanced Sentiment Analysis:** Deepen the understanding of member sentiments through advanced sentiment analysis techniques.

3. **Collaboration Opportunities:** Identify potential collaboration opportunities with healthcare professionals, organizations, or influencers to enhance the group's impact.

Feel free to contribute, share your insights, or open issues for discussion.
