# Movie-recommendation-based-on-emotion-in-Python
One of the underlying targets of movies is to evoke emotions in their viewers. IMDb offers all the movies for all genre. Therefore the movie titles can be scraped from the IMDb list to recommend to the user.IMDb does not have an API, for accessing information on movies and TV Series. Therefore we have to perform scraping. Scraping is used for accessing information from a website which is usually done with APIs.
Installation

Install BeautifulSoup and lxml,
Open terminal and write

pip install beautifulsoup4
pip install lxml
The scraper is written in Python and uses lxml for parsing the webpages. BeautifulSoup is used for pulling data out of HTML and XML files.

Emotion associated with Genre of Movie

There are 8 classes of emotion that would be effective to classify a text. These are: ‘Anger’, ‘Anticipation’, ‘Disgust’, ‘Fear’, ‘Joy’, ‘Sad’, ‘Surprise’, ‘Trust’. Here these are taken as input and the corresponding movies would be displayed for the emotion.
The correspondence of every emotion with genre of movies is listed below:
Sad – Drama
Disgust – Musical
Anger – Family
Anticipation – Thriller
Fear – Sport
Enjoyment – Thriller
Trust – Western
Surprise – Film-Noir

Based on the input emotion, the corresponding genre would be selected and all the top 5 movies of that genre would be recommended to the user.
