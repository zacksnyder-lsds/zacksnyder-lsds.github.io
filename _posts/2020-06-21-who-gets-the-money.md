---
layout: post
title: Who Gets the Money?
subtitle: An Analysis of the Demographics in the Kiva Lending Dataset
cover-img: assets/img/kiva feature photo 3.jpg
---

<b> Prefer to view this article on Medium? [click here](https://medium.com/@zacksnyder1998/https-plotly-com-zacksnyder1998-1-9cff3c79dfce)</b>

<b> All data was sourced from the Kaggle competiton [Data Science for Good](https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding)</b>


<b><u>What is Kiva?</u>

- Online Non-profit Service founded in 2005 in San-Francisco
- Facilitate borrowing and lending between users
- loans for small amounts to fund entrepreneurial ventures
- Payments are made back to the initial lender with interest
- Lenders can choose who they would like to fund and for wha

<b><u>Who gets the money?</u>

The fundamental question that this brings up is who is served by this lending service? Since the service helps individuals by providing them with funds, we can specify this question further to ask who are lenders choosing to give their money too? This question is fundamental to the mission of Kiva to extend financial access to under-served communities. Correct matching of this question to the mission of Kiva can radically change the lives of individuals without access to the resources needed to escape from poverty otherwise.

<b><u>Breaking the question down</u>

This question can be solved using three smaller fundamental questions that make up the whole

- What country gets the most loans
- What sector within those countries get the most loans
- What demographic within those sectors get the most loans

<b><u>What Country gets the most loans?</u>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~zacksnyder1998/19/.embed" height="525" width="100%"></iframe>

The graph above shows clearly that from the countries Kiva serves, The Philippines by far receives the largest amount of loans. This makes sense given that the Philippines is focusing on improving technology infrastructure (and Kiva being reliant on its users' ability to access technology to apply for loans), while still being a developing country in the process of building new businesses to grow into the future and improve the lives of its citizens.
We can also tell from this graph that all countries receive on average the same loan amount on each loan, except for the United States which is significantly higher.

<b><u>What sectors get the most loans?</u>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~zacksnyder1998/17/.embed" height="525" width="100%"></iframe>

The most common loan sectors for individuals to lend into on the Kiva platform are Agriculture, Food, and Retail. These three sector categories represent a large number of activities that individuals can borrow to further their entrepreneurial ventures, such as purchasing livestock, buying fruit to sell in a market, or getting products to sell in a small shop just to name a few.

Interestingly, we can also see from this graph that though the Entertainment and Wholesale sectors receive the least amount of loans, they also receive the highest average funding per loan.

<b><u>What Demographic in these sectors borrows the most</u>

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~zacksnyder1998/9/.embed" height="525" width="100%"></iframe>

From this, we can see that females overtake males in the amount borrowed in every country that Kiva serves. One explanation for this comes from the origin of small loans (known as microloans) to individuals in general. The idea of microloans originated from Grameen bank in Bangladesh as a way to allow the most under-served individuals (women in poverty-stricken areas of Bangladesh) to start entrepreneurial ventures without having to go through individuals who would exploit their lack of financial knowledge. It makes sense that this tradition would carry on to the online micro-lending service of Kiva, due to women in higher poverty nations still being extremely under-served by the financial services industry. Overall Kiva allows women to create income for themselves and their families to build towards escaping poverty.

<b><u>Bringing it all together</u>

Who does Kiva Serve the most?

- Women across all nations they operate in
- Individuals in the Philippines
- People seeking funding in the sectors of Agriculture, Food, and Retail.

<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~zacksnyder1998/1/.embed" height="525" width="100%"></iframe>

<b> Want to see how I got to these conclusions? [click here](https://github.com/zacksnyder-lsds/Unit_1_build_week/blob/master/Unit_1_build_week.ipynb) to veiw my Github repository!</b>
