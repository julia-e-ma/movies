# movies
Code related to movie watching habits

This project was created to help you decide which movie to watch.

RandomMovieGenerator.ipynb reads in a movie spreadsheet (an example named Mega Movie List) that I manually maintain of every movie I would like to watch eventually. The notebook generates a normalized (0-1) IMDb score within the genre cluster (Action, Animated, Comedy, Drama, Horror, Mystery) and appends it as the final column of the dataset. The notebook generates a UI with buttons and sliders where users can input their movie watching preferences for that day and the code will filter the movies based on your preferences as well as by what is available to stream. Then it will randomly choose 1 movie based on the set parameters.

The end of the notebook calculates the total time spent watching movies together and creates histograms of our ratings of watched movies. The final cell calculates which of our favorite actors appear most frequently in our movie watching history. 

