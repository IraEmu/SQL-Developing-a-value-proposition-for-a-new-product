# SQL-Developing-a-value-proposition-for-a-new-product
SQL Project

The coronavirus took the entire world by surprise, changing everyone's daily routine. City dwellers no longer spent their free time outside, going to cafes and malls; more people were home, reading books. That attracted the attention of startups that rushed to develop new apps for book lovers.

You've been given a database of one of the services competing in this market. It contains data on books, publishers, authors, and customer ratings and reviews of books. This information will be used to generate a value proposition for a new product.
Description of the data

<b>books:</b>

Contains data on books:

`book_id`

`author_id`

`title`

`num_pages` — number of pages

`publication_date`

`publisher_id`

<b>authors:</b>

Contains data on authors:

`author_id`

`author`

<b>publishers:</b>

Contains data on publishers:

`publisher_id`

`publisher`

<b>ratings:</b>

Contains data on user ratings:

`rating_id`

`book_id`

`username` — the name of the user who rated the book

`rating`
    
<b>reviews:</b>

Contains data on customer reviews:

`review_id`

`book_id`

`username` — the name of the user who reviewed the book

`text` — the text of the review
