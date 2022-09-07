# Fake_News_Detection


## Overview  
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.  Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles. 
<br>
It is built using python and Flask . Flask is a small and lightweight Python web framework that provides useful tools and features that make creating web applications in Python easier. It gives developers flexibility and is a more accessible framework for new developers since you can build a web application quickly using only a single Python file.
## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source.  Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news.  Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.  

The intended application of the project is for use in applying visibility weights in social media.  Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.

<br>
## Dataset Description

* train.csv: A full training dataset with the following attributes:
  * id: unique id for a news article
  * title: the title of a news article
  * author: author of the news article
  * text: the text of the article; could be incomplete
  * label: a label that marks the article as potentially unreliable
    * 1: fake    * 0: real

* test.csv: A testing training dataset with all the same attributes at train.csv without the label.
# Work Flow

![flow](https://user-images.githubusercontent.com/87085956/188944636-e9122aeb-21aa-4ebf-b946-e0d4eb13ee59.png)

#ScreenShots
![first](https://user-images.githubusercontent.com/87085956/188944751-0aed4c24-13a7-42c5-bc86-a6b7d82a692d.png)

![second](https://user-images.githubusercontent.com/87085956/188944770-65f77703-55b5-490e-8296-397540c1e68b.png)

![third](https://user-images.githubusercontent.com/87085956/188944788-0379fdba-f92b-4bfe-b4f9-711f8cdb9898.png)

![fourth](https://user-images.githubusercontent.com/87085956/188944804-7b6c776f-4948-4642-8f62-1451b25487de.png)



![fifth](https://user-images.githubusercontent.com/87085956/188944812-bee313c1-c870-4ed8-b807-63fa9eea6d78.png)

