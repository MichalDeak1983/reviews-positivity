# reviews-positivity

The scraping jupyter notebook scrape_reviews.ipynb was created by modifying/improving scraping code from
https://www.scrapehero.com/tutorial-how-to-scrape-amazon-product-details-using-python-and-selectorlib/

To use the scraper the url should be obtained in the following way:
1. Go to the page of the product on amazon.
2. Place cursor on product rating (stars), select 1-star.
3. Go to the next page.

The url should look like this: https://www.amazon.com/product-reviews/B07NVTGRVZ/ref=cm_cr_getr_d_paging_btm_next_2?filterByStar=one_star&pageNumber=2

To use the reviews_analysis.ipynb just run in jupyterlab. Code uses data_review.csv
