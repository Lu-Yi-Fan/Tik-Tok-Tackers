# Tik-Tok-Tackers
We were inspired by the challenge of improving the efficiency and effectiveness of social media advertisement moderation. We wanted to create a solution that can help TikTok balance its revenue goals and its social responsibility, while also respecting the diversity and preferences of its users and advertisers.


## Inspiration
We were inspired by the challenge of improving the efficiency and effectiveness of social media advertisement moderation. We wanted to create a solution that can help TikTok balance its revenue goals and its social responsibility, while also respecting the diversity and preferences of its users and advertisers.

## What it does
Our solution is a stochastic optimization model that can dynamically score and prioritize social media advertisements for review, and match them with the best fitting moderator. The model takes into account various factors, such as the absolute revenue, the riskiness, the urgency, the language, and the topic of the ads, as well as the availability, the expertise, and the performance of the moderators. 

## How we built it
We built our model using Python alongside with the models from Sklearn : -Gradient Boost Regression Model and Linear Regression Model. We used data provided by TikTok's platform to train our model and derive the weights of our equation to generate a Y value (priority scores) for our ads and moderator so as to rank them

## Challenges we ran into
- Dealing with noisy and incomplete data, we had to use K-nearest neighbours to fill in missing data and leverage feature engineering before using it for generating the Y value (priority scores) for our dataset.
- Finding a solution to predict a score for our ads and moderator. We ended up using regression models to aggregate the coefficients of each independent variable to predict the priority scores.
- Handling the unequal distribution of moderators across countries. We had to assign ads to moderators according to country to moderators with the least number of assigned ads, so as to increase utilisation rates across the board.


## Accomplishments that we're proud of
Some of the accomplishments we're proud of are:
- Developing a model to score ads and moderators by aggregating the coefficients of each independent variable.
- Achieving high utilisation of over 95% of the available moderators by assigning ads to moderators by country.

## What's next for optimization of ads moderation
- Incorporating more features like ad arrival time to improve the utilisation rate of the moderators using our matching model.
- Testing our model on updated datasets to validate our models.
- Scaling up our model to handle larger volumes of ads and moderators.

## Our Team
- Liang Bing: Third year Business Analytics Student interested in Machine Learning and AI
- Jesper: Student interested in Big Data and Financial Analytics
- Summer: Business Analytics student and Data Enthusiast
- Yifan: Third year Business Analytics student interested in algorithms and data science
- Marc: Student majoring in Data Science & Analytics
