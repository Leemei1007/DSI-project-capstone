# Capstone - Using NLP to extract quick and valuable insights from consumers’ reviews


### Problem statement and objectives

**Problem statement**

- I came across this company (Meatless Farm) on Crowd Cube, a crowdfunding website and I was particularly interested in this company because this is a young company which has high growth potential. In recent years, people’s interest in plant based diet has grown tremendously. So, not surprisingly, Meatless Farm's fund raising campaign was an astounding success – they’ve raised 80% more than what they’ve targeted.
- As an adviser, my job is to explore ways on how I can work with potential clients. It’s my job to go reach out to them… and in order to convince them of the feasibility of my idea, a Proof of Concept is required. 
- I came across reviews of the company's products online. This gave me an idea whereby I can approach this company with a pitch to them… I can use my expertise to process these reviews.. Get customers’ insights… and use these insights to advise the company accordingly 
    

**Objectives**

Understanding customers’ feedback and knowing what are the Company's (and competitor's) strengths and weaknesses by accessing information that could provide with those insights, i.e. website reviews


### Overall workflow
- The process of developing the model entails the following:
1. Scrape the dataset from e-commerce websites, utilising Beautiful Soup
2. Prepping the data, i.e. data processing, inpute the missing values, tokenize, lemmatise and stem the words where required
3. Some preliminary EDA conducted to gauge insights 
4. Train a sentiment analysis classifier on the data, and then use libraries like SHAP to understand which features (i.e. words) have the most impact on a review being classified as positive or negative.


### Conclusion

#### Observations

- Some interesting insights can be derived, for eg. for Meatless Farm's plant based products, we can observe that "smell" and "blandness" have negative impact on ratings. To put it in another way… when customer talk about smell / blandness, they’re likely to give poor ratings. We also noted that Beyond Meat, i.e. a competitor, "texture" has biggest positive impact on ratings… From what we understand, Beyond Meat is widely known for being able to replicate meat so well that meat eaters are convinced

#### Limitations

- Imbalance datasets and subpar quality of reviews, i.e. reviews not detailed enough. Reviews are assumed to be genuine.  

#### Future steps

- Approach Meatless Farm with the proof of concept with hopes for further collaboration, i.e. gather more (quality) data for deeper insights
