# PotterVerse Insights: Character Relationships and Network Visualization 

## Network analysis between the harry potter characters using NLP


* First a harry potter website is scrapped using BeautifulSoup to obtain the list of all characters in the series (scrape.ipynb)
* The data is cleaned to get the final list of characters
* Using named entity recognition from Spacy we obtain the entities in each sentence in the first book "The Philosophers Stone"
* non characters are filtered out and we findout the entities present in the character list
* entities that occur within a window size of 5 form a relationship
* the number of times a relationship occurs in the book is added after sorting
* Then networkx library is used to visualize the network of relations betweeen the characters

The netwrok visualizations: 

https://github.com/foyie/harry_potter_character_network/assets/89987028/1a274cea-54be-456a-b720-f4b51daaee11


