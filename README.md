# Sentiment-Analysis-_-Green-Electric-_Product-reviews
Sentiment refers to the emotion behind customer engagement.

Monitoring sentiment involves measuring the tone, context, and feeling derived from customer actions.

Whether a customer completes a purchase, leaves a review, or mentions a company on social media, there is always an emotional state connected to their action.

Customer sentiment can range from pleased or loving to neutral or angry. No matter where customers fall on the sentiment spectrum, it is essential to understand not only what their emotional state is but also what is driving it.

<center><img src="https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Retail/Images/sentiment.jpg" width="600px"></center>


Problem Statement 
- **Analyzing customer sentiment** helps give **insight** into how **customers feel** about your brand. 
he more you listen to how your customers feel about recommending your company, giving you a rating, engaging with you on social channels, and providing direct feedback, the more appreciation everyone is sure to feel, and the deeper your relationships will grow.

<center><img src="https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Retail/Images/sentiment2.jpg" width="600px"></center>

<h4>Business Scenario:</h4>

A large electronics company, Green Electric, has been falling behind the competition in terms of providing quality customer service.

Their previous marketing campaigns have also been inconsistent, and they are uncertain about what their customers truly want.

The company aims to gain deeper audience insights, improve customer engagement, provide enhanced customer service, and increase the success rate of future marketing campaigns.

To achieve this, the management has proposed analyzing the sentiment of different customers regarding various products.

However, analyzing customer sentiment manually can be a time-consuming process due to the sheer volume of data. Therefore, the company wants to automate the Sentiment Analysis process.

They have tasked their Data Science team with automating the Sentiment Analysis of future reviews.

# **Conclusion**
The reviews were cleaned by:

Changing the case of each word to lowercase,

Fixing certain words,

Removing all punctuation marks from each review, and

Eliminating any additional white space from each review.

The polarity and subjectivity values for each review were then calculated.

This enabled an in-depth analysis of the data to find relationships between various features, such as star rating and polarity.

A threshold for the subjectivity value in the reviews was calculated.

The most common words associated with different sentiments were identified.

After analyzing the data:

Redundant columns were removed,

Samples with a subjectivity value less than 0.3 (subjectivity threshold) were discarded,

Reviews were divided into sentiments based on star rating and polarity,

Finally, the data was split into training and test sets.

During model building, a TFIDF matrix was created from the data, and a Multinomial Naive Bayes model was trained.

The model was used to make predictions on the test set.

The model achieved an accuracy of 92% on both the training and test sets.

This indicated that the model is not overfitting and is generalizing well on unseen data.















  
  
  
