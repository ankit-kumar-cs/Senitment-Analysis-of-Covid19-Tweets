# SBSPS-Challenge-254-Twitter-Sentiment-Visualization-for-Lockdown-Extension
**1**. First we need to collect the data of tweets. We have used the [Download Data Link](https://ieee-dataport.org/open-access/coronavirus-covid-19-tweets-dataset) to collect the tweets.</br>
**2**. The downloaded data is in csv file so have to combine all csv files of a particular **phase**.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;Use [This File MergeData.ipynb](MergeData.ipynb) to merge all the csv files of a particular phase in one text file.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;File generated after this step will look like this [Text File](final-phase4.txt)</br>
**3**. After step 2 now we have one text file in each phase folder that contains all the tweet ids. Now our task is to</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp; Hydrate the text file to get actual tweets and other information about the tweets.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(2)&nbsp; Apply pre-processing on the data to clean the data.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(3)&nbsp; Changing the data in required format.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;To accomplish the above mentioned tasks use the [HydrateTweets.ipynb File](HydrateTweets.ipynb).</br>
        &nbsp;&nbsp;&nbsp;&nbsp;A [final_cleaned_data.csv](final_cleaned_data.csv) file will be created that contains data to be visualized.</br>
**4**. Now we will apply some Python Data Science techniques for **Sentiment Analysis**. To accomplish following tasks</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp; Calculate sentiment value of each tweet.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp; Calculate weight of each tweet.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp; Subdivide the sentiment into Positive,Negative,Weakly Positive,etc.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;(1)&nbsp; Calculate Average Sentiment Value.</br>
        &nbsp;&nbsp;&nbsp;&nbsp;Use [ApplySentimentAnalyis.ipynb](ApplySentimentAnalyis.ipynb)
