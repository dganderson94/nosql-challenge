# nosql-challenge
This repository contains two Jupyter Notebooks:
* The first:
    - imports an included JSON into MongoDB
    - adds a document to it
    - updates that document's BusinessTypeID
    - removes documents for establishments within the Dover Local Authority
    - updates all latitude and longitude values to the double data type
* The second:
    - identifies establishments with a hygiene score of 20
    - identifies establishments under the London Local Authority with a RatingValue greater than or equal to 4
    - identifies the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, near the restaurant "Penang Flavours"
    - counts how many establishments in each Local Authority have a hygiene score of 0
    - displays the previous four pieces of information in DataFrames