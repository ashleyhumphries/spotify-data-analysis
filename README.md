# spotify-data-analysis
A quick notebook for analyzing my Spotify data from 2023 and 2022. 


One day, I became curious about my Spotify data and wanted to play around with it. In this script, I look at certain song features (e.g., valence, danceability, liveness) of the songs I listened to in 2023 and 2022. I also tried using a machine learning model to see if I could predict my songs from 2023 using data from 2022 and to see if one song feature could predict another within a year. 


### File Structure

- `data/` contains the excel files used in this project. These files are a list of song names, artist names with the features and the date/ time I listened to them. The file with "unique" in it has no song repeats. 

### Usage 

- This notebook uses numpy, pandas, ski-kit learn, seaborn, matplotlib, and some other packages related to pulling Spotify features and song ids. 
