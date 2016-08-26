## City Similarity

A project that demonstrates a simple use of Natural Language Processing when one wishes to establish similarity between various texts. <br>
I used business categories from publicly shared Yelp dataset, cleaned them and city names before forming a corpus of words. <br>
Then using constructed vectors, I examined similarity of the most frequent business categories among cities. 

## Content

<p>Python notebook, CitySimilarity, shows how the data munging using stemming of the words. After stemming of the words, I calculated a frequency of the single words in business categories, followed by calculation of the frequency for two and three words phrases. I used nltk and pandas module. </p>

<p>
Python notebook, CitySimilarity2, shows next steps of analysis. Includes forming of the corpus of the words, and clustering with a k-mean algorithm. The notebook contains discussion about the efficiency of a k-mean algorithm for this particular data set. I used gensim, numpy, and pandas module. </p>

## Motivation

When I started my Insight data project, I was thinking broad, trying to make a recommendation engine that will be based on US census data, while Yelp data will serve just as a training set. <br>
This particular analysis is a step in that direction. Categorization of the cities in Yelp data I performed will allow me to train future machine learning algorithm that will be able to recommend a type of the business fitting for specified population structure. Thus ensuring the existence of the customer base necessary for the success of any business enterprise. <br>
More at <a href="https://villepique.wordpress.com/2016/08/25/city-similarity/"> my blog post.</a>

## Use

The code you see is not complete. At the moment, it calculates the only similarity based on the Yelp data, which you have to obtain for yourself by contacting Yelp directly. <br>
However, the principle is adaptable for other uses. 


## Contributors

If you're interested in developing project, please contact me, either through GitHub, or my <a href="https://villepique.wordpress.com"> Data Science blog.</a> 

## License

MIT License

Copyright (c) [2016] [Aleksandra Andic Villepique]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.