
# Analyzing Investor Outcomes in Initial Coin Offerings (ICOs)

In this repo, we analyze the Investor protection  from the point of view of a regulator trying to understand the risks involved in public offer of crypto assets. 

This involves asking several questions:

Question 1: Open-ended—what features of an ICO serve as signals that investors may or may not benefit from their investment in the long-term?
    
    Part I (classification): Which variables serve as the best predictors of whether a crypto asset will survive after an ICO—using today’s status of the coin as our benchmark.

    Part II (OLS regression): From the perspective of a crypto asset issuer, what are the most significant factors for predicting the total amount raised (USDm) in an ICO?

    Part III (two-sample OLS regression): Asks the same question as part II but using two sub-samples (active or inactive status) to refine the prediction 


Question 2: More specific and involves a hypothesis test of these two sub-samples to determine if their means are statistically significant: 

    Does the average total amount raised in the ICO determine whether the crypto asset will succeed long-term (i.e., still be actively traded at an exchange)?

Dataset includes observations on ~300 crypto assets offered in ICOs between 2016-2018
Features (17 total) in the dataset include: 
    
    KYC/AML procedures
    Whitepaper page count
    Team size
    No. of venture capital (VC) investors
    Registration country
    Celebrity endorsements
    etc…
Target variables (2) used in the analysis:

Regression: Total amount raised in ICO (USDm)

Classification: Active/inactive (CoinMarketCap API volumes)

## Author

- [@wmarshalljr](https://github.com/wmarshalljr)


## Documentation

* [Original dataset](https://zenodo.org/record/4034258)
* [CoinMarketCap API](https://coinmarketcap.com/api/documentation/v1/#operation/getV1CryptocurrencyMap)
* [API wrapper used](https://github.com/bizzyvinci/cmc-api)
* [Tableau charts from presentation](https://public.tableau.com/app/profile/william.marshall/viz/ICO_InvestorOutcomes_Ironhack/Dashboard1)
* [Presentation of results](https://docs.google.com/presentation/d/1u3yL9SK0_yTCQMiOY06ANT4mGqtXJ2QMvNoPS61vzGw/edit?usp=sharing)
