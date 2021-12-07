**Streaming Services and the Quality of the Content Provided – How to Get the Most Out of Your Money**

**About Us:**

Megan Brandreth - illxso

Ginthushan Kandasamy - Ginthushan

Zhi Quan Peng - Dennis2680

Gerhard Matthew Yu - GerhardYu

**Introduction:**

Using statistical evidence collected from a number of popular online streaming platforms (Netflix, Disney+, Hulu, and Prime Video), we seek to determine which platforms provide the best deal for customers in regards to overall selection, genre variety, runtime, and film release dates.

The dataset being analyzed is _Movies on Netflix, Prime Video, Hulu, and Disney+,_ created by Ruchi Bhatia and published for use under a public domain on Kaggle. The dataset covers all movies available on the aforementioned platforms up until August 2021 and takes note of movies available on more than one platform, and contains movies released between 1914 and 2021. The dataset also takes note of target audiences of the films accessed and their ratings on third-party platforms

Seeking to find which streaming platform offers the largest selection of films allows users to make informed decisions about where their money is going and if subscription services to specific platforms are worth it for the individual based on their needs and wants.

**Discussion:**

To begin with, to determine the best streaming platform we asked ourselves five different questions based on different aspects relating to the movie industry.

The first question we asked ourselves was: Are there any review differences between IMDB reviews and Rotten Tomato ratings? If this difference exists, does it create a platform-wide disparity between review averages or are the IMDB ratings and Rotten Tomatoes ratings similar? Using our method we were able to conclude that Rotten Tomatoes has an average rating for their movies of 6,16 and IMDB has an average rating of 5,35. This is a difference of 14% which is not significant enough to say that Rotten Tomatoes and IMDB create a platform average. To summarize we are able to conclude that IMDB and Rotten Tomatoes are two platforms with similar reviews for movies so you shouldn&#39;t worry about a website being unreliable.

The second question was how long was the runtime of the movie with the longest runtime and the runtime of the shortest movie? The longest movie was titled The Irishman which had a runtime of 209 minutes and the shortest runtime was Into The Grand Canyon with 84 minutes. To expand on question 2, we also asked ourselves which platform has the longest and shortest average runtime for the movies they offer. To answer this question we came up with this graph which gives us a lot of information.



Looking at the graph produced in question 2, we are able to determine that these are the platforms that have the longest to shortest platform in order: Netflix, Hulu, Disney+, Prime Video.

Following that question, another question was asked which was which movies had the most languages available and the top 3 movies were chosen. The movie with the most languages available would be The Irishman with the languages that are available being English, Italian, Latin, Spanish and German. The top 2 and 3 movies were Dangal and David Attenborough: A Life on Our Planet respectively with Dangal having both Hindi and English available as its languages and David Attenborough: A Life on Our Planet having only English as its language available.

The fourth question was if there was any correlation between the highest rated movie and its genre. Based on the top 10 movies on IMDb, the most common genre in the top 10 was Documentary while based on the top 10 movies on Rotten Tomatoes the most common genre was Drama. This gives us information that the users of IMDb and Rotten Tomatoes have different genres in which they like seeing as both review sites have different top 10 movies. Since both Rotten Tomatoes and IMDb have different top 10 movies, there is no definite proof that genre has a correlation with how high the movie is going to be rated.

The final question is based on which subscription is the best bang for your buck in the sense of a value proposition. We did this by figuring out which of the subscriptions had the greatest selection of available movies but also which of them had the greatest selection of vintage movies (movies before the 1990s). The answer to this question turned out to be Prime on both occasions. With a total selection of 4113 total movies and 806 of them being vintage.

**Conclusion:**

In the analysis conducted by our group on the dataset containing movie data from four of the biggest streaming platforms readily available and well known to the public sphere, we were able to reach a number of interesting conclusions about the services we use often in our daily lives.

We delved into details pertaining to the reviews and scores given to films on third party websites and compared them to each other to determine disparity between the given values. We further analyzed the range of runtimes for the movies across all platforms, available languages, and which movie genres tended to perform better on different reviewing platforms. Finally, we delved deeper into which streaming platforms cater better to certain needs over others, using two examples of comparisons between platforms for different film qualifiers to determine which provider offers the best selection of movies for that specific qualifier.

**Reflection**

As we continued our work on this project, we refined our knowledge of python, including but not limited to our ability to use numpy, pandas, and seaborn to clean, dissect, and understand the data provided to us. We learnt the importance of communication when working as a team, as well as improved what we knew about finding bugs and errors in large projects such as this. Furthermore, we learnt valuable lessons in terms of industry-standard documentation of our code to make it more legible, helping us to better understand how our code was functioning regardless of who had worked on which part.

**Refinement**

Though, it goes without saying that there are numerous places we could improve should we approach this project once again. First and foremost, improved communication between the team would have benefitted us greatly. In terms of the technical aspects of our project, more pointed questions that would give us a chance to dig deeper into the data and provide us with less shallow conclusions would improve the quality of our work and findings.

**Acknowledgments:**

This project was submitted as the final course project for CSCI 2000U &quot;Scientific Data Analysis&quot; during Fall 2021. The authors certify that the work in this repository is original and that all appropriate resources are rightfully cited.

**References**

Bhatia, R. (2021, 08 02). _Movies on Netflix, Prime Video, Hulu and Disney+_ (3) [A collection of movies found on these streaming platforms]. https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney/version/3

**Read Me**

In order to run our code you would need to install our dataset at [https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney/version/3](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney/version/3) and import/install numpy, pandas and seaborn if your python does not already contain the existing libraries. Other functions that need to be imported are reduce from functools and basic code to read the csv file.

To run the following files above, the code below should be run.
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
df_data = pd.DataFrame(data)
```
