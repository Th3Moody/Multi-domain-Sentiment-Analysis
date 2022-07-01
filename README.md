# Multi-domain Sentiment Analysis
*Multi-domain Sentiment Analysis using Natural Language Processing techniques.*

## Abstract
This is a sentiment analysis model aimed at determining whether a product review is positive or negative using natural language processing techniques. The model was built with a Long-Short Term Memory neural network and scored 77% accuracy on test data.
## Dataset
The dataset used is the [Multi-Domain Sentiment Dataset](https://www.cs.jhu.edu/~mdredze/datasets/sentiment/index2.html) provided by Mark Dredze and John Blitzer.
The Multi-Domain Sentiment Dataset contains product reviews taken from Amazon.com from 4 product types (domains): Kitchen, Books, DVDs, and Electronics. Each domain has several thousand reviews, but the exact number varies by domain.

The dataset split the reviews in 4 different folders (folder for each domain) and each folder contained positive reviews file, negative reviews file, and an optional unlabeled reviews file. Each file contains a pseudo-XML scheme for encoding the reviews.

A negative review example:
```XML
<review>
  <unique_id>
    0312355645:horrible_book,_horrible.:mark_gospri
  </unique_id>
  <asin>
    0312355645
  </asin>
  <product_name>
    Running with Scissors: A Memoir: Books: Augusten Burroughs
  </product_name>
  <product_type>
    books
  </product_type>
  <helpful>
    4 of 9
  </helpful>
  <rating>
    1.0
  </rating>
  <title>
    Horrible book, horrible.
   </title>
  <date>
    November 14, 2006
  </date>
  <reviewer>
    Mark Gospri
  </reviewer>
  <reviewer_location>

  </reviewer_location>
  <review_text>
    THis book was horrible.  If it was possible to rate it lower than one star i would have.  I am an avid reader and picked this book up after my mom had gotten it from a     friend.  I read half of it, suffering from a headache the entire time, and then got to the part about the relationship the 13 year old boy had with a 33 year old man       and i lit this book on fire.  One less copy in the world...don't waste your money.

    I wish i had the time spent reading this book back so i could use it for better purposes.  THis book wasted my life
  </review_text>
</review>
```
