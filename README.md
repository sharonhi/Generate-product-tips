# Products-generate-tips

This is a sample from the full dataset that will be released with the paper "Generating Tips from Product Reviews" after the acceptance.

The dataset contains the following fields:
review_id - identifier of the review in the dataset. integer

asin - product identifier. string

reviewer_id - user identifier. string

category - the category that the product belongs to, one of five possible categories. string

sentence - the split sentence from the full review. string

tip - whether the sentence is a tip or not. binary (1/0)

type - if the sentence is a tip the column contain the tip type. string

standalone - if the sentence is a tip the column contain whether the tip is a standalone sentence (yes) or not (no). string

before/after - tip timing, useful before/after the purchase (or both). string (before/after/both)

extend_position - in case the tip can be extended to one of the adjacent sentences for context, the adjacent sentence is mark 

as before/after the tip.
