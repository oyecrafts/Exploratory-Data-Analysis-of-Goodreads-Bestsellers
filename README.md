# Exploratory-Data-Analysis-of-Goodreads-Bestsellers
## Introduction
The dataset provided here originates from the Goodreads API, a platform that offers a plethora of book-related information. This dataset encompasses various details about books, including their titles, authors, user ratings, reviews, prices, publication years, genres, and bestseller ratings. The data has been collected and curated meticulously, offering valuable insights into the literary landscape.

## Overview of the Dataset
The Goodreads books dataset is a comprehensive collection of book-related data obtained from the Goodreads API. It includes information on thousands of books, covering a wide range of genres, authors, and publication years. The dataset provides insights into the popularity, ratings, and reviews of these books, allowing for in-depth exploration and analysis.

## Description of Variables/Features
* Name: The title of the book.
* Author: The author(s) of the book.
* User Rating: The average rating given to the book by users on Goodreads.
* Reviews: The total number of reviews the book has received.
* Price: The price of the book.
* Year: The year in which the book was published.
* Genre: The genre/category of the book.
  
## Bestseller Rating: 
A newly created column categorizing books based on their user ratings and reviews, indicating whether they are moderately rated bestsellers, highly rated bestsellers, or very highly rated bestsellers.

## Bestseller Rating Criteria:
* Moderately Rated Bestsellers: Books with a user rating of 3.9 or below and at least 29,280 reviews.
* Highly Rated Bestsellers: Books with a user rating between 4.0 and 4.9, inclusive, and between 29,281 and 58,560 reviews.
* Very Highly Rated Bestsellers: Books with a user rating of 4.0 or above and at least 58,561 reviews.
This new column provides additional insight into the popularity and reception of each book within the dataset, categorizing them based on their user ratings and reviews.

## Data Visualization
Visualizations of the dataset have been created using Tableau. For interactive visualizations and further exploration of the dataset, please visit the [Tableau Dashboard](https://public.tableau.com/views/Book11_17115508245790/BestsellerBookDataRatingsReviewsPricesandMore?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link).

## License
The dataset is publicly available on Kaggle, and while it is shared for the benefit of the data science community, the ownership and maintenance of the dataset lie with its [creator](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks). Please refer to the dataset creator's terms of use and licensing agreements for any specific restrictions or permissions regarding its use.

Feel free to reach out to the dataset creator for any further inquiries or clarifications regarding the dataset.
