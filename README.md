# Portfolio of my data analytics/data science projects
Repo of any data focused work I've done

### Highlights

[1. Email notifications MVP](https://github.com/terry-zeng1134/Portfolio/blob/main/BQ%20notification%20MVP/first_review.ipynb) <- Click here to go to jupyter notebook
  - Sends email notification to partners based on day to day changes in data (BigQuery table partitioned by execution date)
  - Used to identify new brands that have secured partnerships with Sephora/Ulta by identifying new "first reviews" that appear on their website
    - The idea is that appearing on Sephora/Ulta requires a distribution/marketing partnership between brand & retailer
    - The partnerships gives access to Sephora/Ulta's distribution network, gets an allocation of Sephora/Ulta's marketing budget, and put in front of millions of customers
    - Faster customer growth -> higher revenue expectations -> higher exit valuation
  - Multiple instances of this Jupyter notebook is ran daily on other modeled value indicators (growth index, product velocity, estimated revenue, new to Target/Walgreens, etc)
  - Developed to source early-stage equity investment opportunities
  
[2. Topic model](https://github.com/terry-zeng1134/Portfolio/blob/main/Topic%20modelling/topic%20model%20v2.ipynb) <- Click here to go to jupyter notebook
- Computes the [key purchase critiera](https://redfworkshop.org/learn/key-purchasing-criteria/) of a particular parent category (food, beverages), primary category (soft drinks, non-dairy milks), and product categories (kombucha, energy drinks) based on customer reviews
- Returns the seed words used to classify reviews by topic
  - If a topic of a review was classified as the "Price" of the product, the review would contain seed words such as "expensive", "paid", "money", "value", etc...
- When deciding on whether to invest in a brand, the brand is compared against their competitors on the key purchase criteria derived from the topic outputted from this model
- The outputs of this model are used to assess product/market fit. [A few samples done on Amazon S3](https://github.com/terry-zeng1134/Portfolio/tree/main/S3%20Spark%20projects/Key%20Purchase%20Criteria)

[3. Customer attribute analysis](https://github.com/terry-zeng1134/Portfolio/blob/main/BQ%20projects/Ad%20hoc/Partake%20Basket_Analysis%20Review_Distribution%20Term_Frequency.ipynb) <- Click here to go to jupyter notebook
- Portfolio company Partake is deciding between repositioning its messaging towards the better-for-you cookies vs allergen-free cookies market segments
- Identified the top 20 products most frequently reviewed by customers of Partake, then manually labeled whether they are "better-for-you", "allergy-free", or irrelevant
- Resulted in reposition of brand to target the better-for-you cookies market
