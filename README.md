# Data_Mining---COVID-19-Hate-Speech-Analysis

**Overview**:
The project focuses on the influence of the recent pandemic COVID19 on people’s behavior using the data from Twitter. The tweets from before the pandemic and during the pandemic are used to identify the change in the topics around which people have expressed hatred. The policy of twitter to remove such tweets makes this a challenge since getting the data of the actual tweet is very difficult. Our study uses NLP to refine the tweets and draw visualizations depicting the most common words used during both times. The dataset considered is a labelled dataset (1200 rows) with pre covid tweets and during covid tweets with an almost equal distribution of hate (60%) and non-hate (40%) speech. The data mining approach that we use here is topic modelling to understand the most common topics of such hatred during the pre and post covid times.

**Results**:
The results for the during covid data show that the coherence considering the hatred and non-hatred tweets together is highest when number of topics is 6 (0.2868). However, we did not see distinct topics themes from all the topics created. They contained very similar words. We also considered adjusting the lambda to see if the rare words helped better in the analysis. Lambda closer to zero gives the rare and exclusive terms that is the words that can differentiate the topics more from one another and define topic exclusivity. Therefore, on running the model with lesser number of topics, we saw that the optimal number of topics was 2 (with coherence 0.2331) to make understandable themes out of the topics. 

<img width="193" alt="image" src="https://github.com/guptar02/Data_Mining---COVID-19-Hate-Speech-Analysis/assets/134241281/e5d681de-a085-4be2-9ab0-c362bae06447">
<img width="201" alt="image" src="https://github.com/guptar02/Data_Mining---COVID-19-Hate-Speech-Analysis/assets/134241281/87e89af6-bcb0-4781-b0d4-2281df5d98be">
<img width="360" alt="image" src="https://github.com/guptar02/Data_Mining---COVID-19-Hate-Speech-Analysis/assets/134241281/7004a3d3-65d9-4fc9-a295-fa9fb3d28d61">

**Note - This was done in a team of two and my part was to analyze the post covid sentiments. Therefore, the scripts are only available for post-covid analysis.** 
