# Tweet-based-Trends-plotting-using-Hashtags
**Tweet Based Trends plotted on maps using hashtags** uses Twitter data, more importantly the tweet text and sentimentally analyses it to output a feeling index and the tweet location, on the other hand, is simultaneously projected on a world map. This can be used for getting a bird's eye view of the current trends going on in the world, regarding any issues such as social, economic, cultural or political overview of a specific area. 

## Getting Started
**Input:** A twitter hashtag and the limiting value of how many tweets are to be extracted. 

**Output:** An HTML file, to be opened in any browser for displaying the map. 

*A sample HTML output file is uploaded to this repo where the hashtag input was 'bjp' and the limiting value was 1000.*

#### Instructions to run the code
Step 1
_git clone https://github.com/Debanik/Tweet-based-Trends-plotting-using-Hashtags.git_

Step 2
_python3 -m virtualenv myenv_

Step 3
_source myenv/bin/activate_

Step 4
_pip install -r requirements.txt_

Step 5
_Edit twitter.py and insert your own Twitter API credentials_

Step 6
_python twitter.py_

#####Viola! If everything worked correctly, you'll find a _twittermap.html_ file with the geocoded data.


## Built With
- [TextBlob](https://textblob.readthedocs.io/en/dev/) - For sentimentally analysing the tweets. 
- [Folium](https://github.com/python-visualization/folium) - For creating a Leaflet map from location parameters. 
- [Tweepy](http://www.tweepy.org/) - An open source API for fetching twitter data. 
- [Geopy](https://pypi.org/project/geopy/) - For geocoding the location name to latitude and longitude pairs. 
- [Tweet-Preprocessor](https://pypi.org/project/tweet-preprocessor/) - For cleaning the tweets

## Contributors 
- [Debanik Banerjee](https://github.com/Debanik)
- [Bidyudipta Chanda](https://github.com/bidyutchanda)
