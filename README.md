# Analysis-the-online-news-popularity
Due to the Web expansion, the prediction of online news popularity is becoming a trendy research topic. In this project, we propose a novel and proactive Intelligent Decision Support System (IDSS) that analyzes articles prior to their publication. Using a broad set of extracted features (e.g., keywords, digital media content, earlier popularity of news referenced in the article) the IDSS _rst predicts if an article will become popular.
# Data description
This is a large and recently collected dataset with 39000 articles from the Mashable website. And there are 61 attributes in this dataset. 58 predictive attributes (e.g., Number of words in the title, Number of images, Rate of non-stop words in the content, Rate of negative words in the content).2 non-predictive attributes (URL of the article, Days between the article publication and the dataset acquisition).1 goal field (Number of shares). 
Class Distribution: the class value (shares) is continuously valued. We transformed the task into a binary task using a decision threshold of 1400. (>=1400 is popular, <1400 is not popular)
# Algorithm and metrics
During this project, because the response is a binary outcome, so I choose Logistic Regression as benchmark algorithm. And I also choose Support Vector Machine as another model to do prediction and make comparison.  And in this project, I choose misclassification error between predicted value and actual value as evaluation metrics. And I also split the dataset into train data and test data, 0.75/0.25 split randomly. 
