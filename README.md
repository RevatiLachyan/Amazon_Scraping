# Amazon_Scraping

This is an application of Natural Language processsing

The question is 'Scrape about 5000 reviews on any product of your choice on Amazon along with their ratings (1-5). Considering reviews with 1-2 as 'negative' and 4-5 as 'positive', develop an NBC classifier.'

The scraping is done using Beautiful Soup.

The reviews of Amazon-Halo-Fitness-And-Health-Band is fetched from the web.
The body, title and ratings are differentiated using beautiful soup

A data frame is created for the data and all the unnecessary characters and emoticons are removed from the review line.
The data frame is finally exported to an excel file.

In FinalProject_AmazonScrapping, the excel file is imported
These sentences are lemmatized, the accents and the punctuations are removed. All the letters are converted to lower case.
All the stop words are removed and the sentences are tokenized
The frequencies of all the words are noted and the words are converted to vectors.

The rating are labelled as 0-2 as negative, 3 as neutral and, 4-5 as positive.
Applied multinomial Naive Bayes, categorial Naive Bayes, Bernoulli Naive Bayes, Complement Naive Bayes and found accuracy for all

Plotted the word cloud

