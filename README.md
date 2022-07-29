# Portfolio of my data analytics/data science projects
Repo of any data focused work I've done

### Highlights

[Email notifications MVP](https://github.com/terry-zeng1134/Portfolio/blob/main/BQ%20notification%20MVP/first_review.ipynb)
  - Sends email notification to partners based on day to day changes in data (BigQuery table partitioned by execution date)
  - Used to identify new brands that have secured partnerships with Sephora/Ulta by identifying new "first reviews" that appear on their website
    - The idea is that appearing on Sephora/Ulta requires a distribution/marketing partnership between brand & retailer
    - The partnerships gives access to Sephora/Ulta's distribution network, gets an allocation of Sephora/Ulta's marketing budget, and put in front of millions of customers
    - Faster customer growth -> higher revenue expectations -> higher exit valuation
  - Multiple instances of this Jupyter notebook is ran daily on other modeled value indicators (growth index, product velocity, estimated revenue, new to Target/Walgreens, etc)
  - Developed to source early-stage equity investment opportunities
  
[Topic model](https://github.com/terry-zeng1134/Portfolio/blob/main/Topic%20modelling/topic%20model%20v2.ipynb)
- Computes the [key purchase critiera](https://redfworkshop.org/learn/key-purchasing-criteria/) of a particular parent category (food, beverages), primary category (soft drinks, non-dairy milks), and product categories (kombucha, energy drinks) based on customer reviews
- Returns the seed words used to classify reviews by topic
  - If a topic of a review was classified as the "Price" of the product, the review would contain seed words such as "expensive", "paid", "money", "value", etc...
- When deciding on whether to invest in a brand, they are compared against their competitors on the key purchase criteria derived from the topic outputted from this model

