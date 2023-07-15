# Data

## Books table: contains data on books
- *book_id* - unique identifier of the book.
- *author_id* - unique identifier of the author.
- *title* - title of the book.
- *num_pages* — number of pages in the book.
- *publication_date* - date the book was published.
- *publisher_id* - unique identifier of the publisher.

## Authors table: contains data on authors
- *author_id* - unique identifier of the author.
- *author* - the name of the author.

## Publishers table: contains data on publishers
- *publisher_id* - unique identifier of the publisher.
- *publisher* - the name of the publisher.

## Ratings table: contains data on user ratings
- *rating_id* - unique identifier of user rating.
- *book_id* - unique identifier of the book.
- *username* — the name of the user who rated the book.
- *rating* - book rating.

## Reviews table: contains data on user reviews
- *review_id* - unique identifier of the user review.
- *book_id* -unique identifier of the book.
- *username* — the name of the user who reviewed the book.
- *text* — the text of the review.
