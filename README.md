# Fake News Detection - Resources

This is a complementary list of resources for the book [Detecting Fake News on Social Media](https://www.morganclaypool.com/doi/abs/10.2200/S00926ED1V01Y201906DMK018). 

### Datasets

[BuzzFeedNews](https://github.com/BuzzFeedNews/2016-10-facebook-fact-check/tree/master/data):
This dataset comprises a complete sample of news published in Facebook from 9 news agencies over a week close to the 2016 U.S. election from September 19 to 23 and September 26 and 27. Every post and the linked article were fact-checked claim-by-claim by 5 BuzzFeed journalists. It contains 1,627 articles 826 mainstream, 356 left-wing, and 545 right-wing articles.

[LIAR](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip):
This dataset  is collected from factchecking website PolitiFact. It has 12.8 K human labeled short statements collected from PolitiFact and the statements are labeled into six categories ranging from completely false to completely true as pants on fire, false, barely-true, halftrue, mostly true, and true.


[BS Detector](https://github.com/bs-detector/bs-detector):
This dataset is collected from a browser extension called BS detector developed for checking news veracity. It searches all links on a given web page for references to unreliable sources by checking against a manually compiled list of domains. The labels are the outputs of the BS detector, rather than human annotators.

[CREDBANK](http://compsocial.github.io/CREDBANK-data/):
This is a large-scale crowd-sourced dataset of around 60 million tweets that cover 96 days starting from Oct. 2015. The tweets are related to over 1,000 news events. Each event is assessed for credibilities by 30 annotators from Amazon Mechanical Turk.

[BuzzFace](https://github.com/gsantia/BuzzFace):
This dataset is collected by extending the BuzzFeed dataset with comments related to news articles on Facebook. The dataset contains 2263 news articles and 1.6 million comments discussing news content.

[FacebookHoax](https://github.com/gabll/some-like-it-hoax):
This dataset comprises information related to posts from the facebook pages related to scientific news (non- hoax) and conspiracy pages (hoax) collected using Facebook Graph API. The dataset contains 15,500 posts from 32 pages (14 conspiracy and 18 scientific) with more than 2,300,000 likes.

[FakeNewsNet](https://github.com/KaiDMML/FakeNewsNet/):
This dataset comprises fake and real news pieces collected from fact-checking websites PolitiFact and GossipCop. It contains news articles content, tweets related to news articles and their social engagements including replies, retweets, and favorites. In total dataset contains nearly 2 million tweets related to fake and real news pieces along with their engagements and user profiles of users interacted with these tweets.


|Datasets | Linguistic | Visual | User|  Post| Response|  Network | Spatial | Temporal |
|--|--|--|--|--|--|--|--|--|
|BuzzFeedNews|Y||||||||
|LIAR| Y||||||||
|BS Detector| Y||||||||
|CREDBANK| Y||Y|Y|||Y|Y|
|BuzzFace| Y|||Y|Y||||
|FacebookHoax| Y||Y|Y|Y||||
|FakeNewsNet|Y|Y|Y|Y|Y|Y|Y|Y|



### Software

 - **Hoaxy**: ([https://hoaxy.iuni.iu.edu/](https://hoaxy.iuni.iu.edu/))

 - **FakeNewsTracker** : ([http://blogtrackers.fulton.asu.edu:3000/](http://blogtrackers.fulton.asu.edu:3000/)
 
 - **Grover**:  (https://grover.allenai.org/)
  
 - **dEFEND**: ([http://fooweb-env.qnmbmwmxj3.us-east-2.elasticbeanstalk.com/](http://fooweb-env.qnmbmwmxj3.us-east-2.elasticbeanstalk.com/))
 
 - **NewsVerify**: ([http://www.newsverify.com/NewsVerifyPro/](http://www.newsverify.com/NewsVerifyPro/))
 
  - **Claim buster**:  ([https://idir-server2.uta.edu/claimbuster/](https://idir-server2.uta.edu/claimbuster/))
