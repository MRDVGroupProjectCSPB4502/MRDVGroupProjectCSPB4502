# Youtube Trending Videos Analysis
Team Members: Daniel Shackelford, Vidya Giri, Rouzbeh Salehi Pour, Michael Taylor

***WARNING, data set size is too large to be hosted on github. Original data set can be found at: https://www.kaggle.com/rsrishav/youtube-trending-video-dataset***

### Description

Youtube is an American video streaming platform that serves as a key source of news, entertainment, and reference in the digital age: allowing all ranges of global users to broadcast their videos to the world and view videos that are relevant to their interests. Variety magazine states that in order, “to compile its trending-video rankings, YouTube uses a proprietary algorithm that factors in total views, likes, comments and searches.” This project intends to identify what determines the performance of a trending YouTube video through the analysis of string, numeric, and visual data.

### Summary of Questions and Answers

- Do various tags have an effect on viewership and lead to higher view counts?
  -  Tags have a weak correlation or are not correlated at all to video view count totals.
- Do popular trending videos in a particular category lead to an overall increase in viewership in the same category?
  - there was not a direct correlation between an increase in views in a category after a popular video was released, however different categories do experience more of a change in views than others
- What features cause an increase in viewership count for a trending video? (number of likes and dislikes, comment count, video title length, video description length, etc)
  - The feature importance scores from the random forest model (88% f1-score) showed that likes, comment count, and dislikes were the most important features when predicting video view count and therefore could be the most contributing factors for an increase in viewership.
- What are common visual features in trending video thumbnails? What is the prevalence of faces in the thumbnail images? What clusters of thumbnails exist? 
  - We were able to detect significant visual features in Youtube thumbnails with facial and object detection models and subsequently created 20 defined clusters. From our analysis we have determined that 63.8% of the trending videos in the US contained a detectable face in the thumbnail. 

### Application of this knowledge

Overall this analysis is directly invaluable to two main groups, creators wanting to grow their viewer base, and YouTube’s engineers wishing to increase user engagement. Creators can use this information to understand what factors into video success and what they can do to improve their viewers' engagement in their content. YouTube can use this information not only to better their creators, but can also use it to determine server loads and site use, as well as determine which categories of videos are most important to their user base and which categories possibly need more support from the platform. Looking further out, this data can be used in the design of other social media systems and in analyzing population response to things like news and its effect on society. 

### Video demonstration
- https://drive.google.com/file/d/1ClNJgKI1wNAv1glFeDXchZmPjMTpV6Gh/view?usp=sharing

### Link to your final project paper
- https://github.com/MRDVGroupProjectCSPB4502/MRDVGroupProjectCSPB4502/blob/main/Final%20Report_%20Group03_YouTubeAnalysis_Part4.pdf

### Extra credit visualization
- https://mrdvgroupprojectcspb4502.github.io/

