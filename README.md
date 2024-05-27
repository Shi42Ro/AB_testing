# A/B TEST AND HYPOTHESES TO BOOST MARKETING REVENUE
# Data
/datasets/hypotheses_us.csv
> - Hypotheses — brief descriptions of the hypotheses
> - Reach — user reach, on a scale of one to ten
> - Impact — impact on users, on a scale of one to ten
> - Confidence — confidence in the hypothesis, on a scale of one to ten
> - Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

/datasets/orders_us.csv
> - transactionId — order identifier
> - visitorId — identifier of the user who placed the order
> - date — of the order
> - revenue — from the order
> - group — the A/B test group that the user belongs to

/datasets/visits_us.csv
> - date — date
> - group — A/B test group
> - visits — the number of visits on the date specified in the A/B test group specified

# Goal
> - To apply the ICE framework to prioritize hypotheses and sort them in descending order of priority.
> - To apply the RICE framework to prioritize hypotheses and sort them in descending order of priority.
> - To carried out A/B test for the marketing revenue

# Libraries
*pandas ,matplotlib ,numpy, seaborn, nltk, scipy, statsmodels*
