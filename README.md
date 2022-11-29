# Around-the-world-in-80-days

# Requirements 
* Numpy 
* Matplotlib
* Pandas
* Cartopy
* NLTK
* Requests
* BeautifulSoup


An analysis of the book, Around the World in 80 Days by Jules Verne. I started off by exploring the contents of the book.
This included counting the characters, words, unique words and commonly used words in the book.
Then I split the book into its chapters and used the VADER tool in the NLTK library to analyse the sentiment of each chapter 
and to plot the positive sentiment level over time on a chart. Finally, I plotted the locations mentioned in the book on a map and did analysis to provide
travel information to people who are inspired by the travels of Phileas Fogg and who would want to simulate their own journeys by visiting the same cities.

I’v focused the analysis primarily on the cities mentioned in the book that are in the UK. 
Estimates of the average hotel rates and the score of how likely people are to recommend the related cities as holiday destinations 
to a friend were collected using "Beautiful Soup" and "requests" libraries to scrape the website.
