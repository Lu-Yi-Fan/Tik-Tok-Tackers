# Tik-Tok-Tackers
We were inspired by the challenge of improving the efficiency and effectiveness of social media advertisement moderation. We wanted to create a solution that can help TikTok balance its revenue goals and its social responsibility, while also respecting the diversity and preferences of its users and advertisers.


## Inspiration
We were inspired by the challenge of improving the efficiency and effectiveness of social media advertisement moderation. We wanted to create a solution that can help TikTok balance its revenue goals and its social responsibility, while also respecting the diversity and preferences of its users and advertisers.

## What it does
Our solution is a stochastic optimization model that can dynamically score and prioritize social media advertisements for review, and match them with the best fitting moderator. The model takes into account various factors, such as the absolute revenue, the riskiness, the urgency, the language, and the topic of the ads, as well as the availability, the expertise, and the performance of the moderators. 

## How we built it
We built our model using Python alongside with the models from Sklearn : -Gradient Boost Regression Model and Linear Regression Model. We used data provided by TikTok's platform to train our model and derive the weights of our equation to generate a Y score for our ads and moderator so as to rank them

## Challenges we ran into
- Dealing with noisy and incomplete data , we had to clean and preprocess the data before using it for generating the Y value for our dataset.
- Handling the uncertainty and variability of user behavior and response to ads. We had to use stochastic methods and probabilistic models to account for these factors.
- Ensuring fairness and diversity in our model. We had to avoid bias and discrimination in our model's decisions and outcomes.

## Accomplishments that we're proud of
Some of the accomplishments we're proud of are:
- Developing a novel and comprehensive solution for social media advertisement moderation optimization.
- Achieving high accuracy and efficiency in our model's predictions and assignments.
- Demonstrating significant improvement in TikTok's revenue generation and risk reduction compared to its current moderation process.

## What we learned
- How to apply stochastic optimization techniques to real-world problems.
- How to use web search results to enhance our data and information.
- How to work as a team and collaborate effectively.

## What's next for optimization of ads moderation
- Scaling up our model to handle larger volumes of ads and moderators.
- Incorporating more features and data sources into our model to improve its performance.
- Testing our model on other social media platforms and domains.
