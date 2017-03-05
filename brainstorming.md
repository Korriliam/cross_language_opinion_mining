Firstly, our project will download comments and review from various sources, along with their notation (if there's)
Then, all this data will be used to train a classifier aimed to associate various scores to a given input (a text as
well).

These scores might be dealing with:
reliability
sentiment
...


Another purpose might be to detect category of a given comment/notation. 
Was it a political text ?
One dealing with sport ?
Science ?
Tech ?
Computer sciences ?


We will mine websites such as:
- amazon
- babelio
- goodreads
- cdiscount
- le figaro
- facebook
- google+
...

We'll use scrapy bots. Storage in mysql database. 

Database structure ?


Tables:

Source (name, website)



