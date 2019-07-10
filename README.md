


# Fake News Detection - Resources

This is a complementary list of resources for the book [Detecting Fake News on Social Media](https://www.morganclaypool.com/doi/abs/10.2200/S00926ED1V01Y201906DMK018), Morgan \& Claypool Publishers. 

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

 - [**Hoaxy**](https://hoaxy.iuni.iu.edu/): This tool aims to build a uniform and extensible platform to collect and track misinformation and fact-checking , with visualization techniques to understand the misinformation propagation on social media.

 - [**FakeNewsTracker**](http://blogtrackers.fulton.asu.edu:3000/):  FakeNewsTracker is a system for fake news data collection, detection, and visualization on social media. It makes use of news articles and social media data to detect fake news. This tool also visualizes misinformation propagation on social media.
 
 - [**Grover**](https://grover.allenai.org/):  Grover makes uses of adversarially generated fake news towards targeted content to train the models and detect fake news. This software generates fake news on the user provided topic and generates fake news and also detects fake news based on the contents of the news articles.
  
 - [**dEFEND**](http://fooweb-env.qnmbmwmxj3.us-east-2.elasticbeanstalk.com/): This is an explainable fake news detection tool which can exploit both news contents and user comments to jointly capture explainable top-k check-worthy sentences and user comments for fake news detection.

 - [**NewsVerify**](http://www.newsverify.com/NewsVerifyPro/):  NewsVerify is a real-time news verication system which can detect the credibility of an event by providing some keywords about it.
 
 - [**BS Detector**](https://gitlab.com/bs-detector/bs-detector): BS Detector is a chrome extension that easily identifies fake and satirical news sites, as well as other questionable news sources. It adds a warning label to the top of questionable sites as well as link warnings on Facebook and Twitter.
 
 -  [**Open Mind**](https://openmind.press/): Open Mind is a Google Chrome extension designed to combat the proliferation of fake news, and increase exposure to opposing viewpoints. It warns users of websites known to publish fake news by providing the user with a large warning screen and links to more reputable sources.
 
- [**Media Bias Fact Check**](https://chrome.google.com/webstore/detail/official-media-bias-fact/hdcpibgmmcnpjmmenengjgkkfohahegk?hl=en-US):
This extension shows an icon denoting the political bias for the current page.This extension will display a color-coded icon denoting the bias of the page you are currently viewing, according to Media Bias/Fact Check.

 - [**News Guard**](https://www.newsguardtech.com/): NewsGuard is a chrome extension that uses red/green ratings and labels to help users know which news and information websites to trust.
 
#### Educative Games:

 -  [**Fakey**](https://fakey.iuni.iu.edu/): This game aims to teach media literacy and study how people interact with misinformation.
 
 -   [**FACTITIOUS**](http://factitious2017.augamestudio.com/#/): This game presents news articles which have been fact-checked by independent fact-checking organizations and challenges players to differentiate news from entertainment from opinion.

 -   [**Fake It To Make It**](https://www.fakeittomakeitgame.com/): This game takes significantly longer than an hour, but it puts you right into the mindset of someone who is manipulating social media purely for profit.

-   [**Bad News**](https://getbadnews.com/#intro): This game  puts you in charge of a fake news publication. You will learn about what goes into successful bad news and how people manipulate it for their benefit.


###  Related Events
 - [Fake News Challenge]([http://www.fakenewschallenge.org/](http://www.fakenewschallenge.org/))
 - [WSDM Fake News Classification Competition]([https://www.kaggle.com/c/fake-news-pair-classification-challenge/](https://www.kaggle.com/c/fake-news-pair-classification-challenge/))
 - [SBP-BRiMS Disinformation Challenge]([http://sbp-brims.org/2019/challenge/challenge2_Disinformation.html](http://sbp-brims.org/2019/challenge/challenge2_Disinformation.html))
 - [KDD'19, WSDM'19 - Fundamental Theories, Detection Strategies & Open Problems]([https://www.fake-news-tutorial.com/](https://www.fake-news-tutorial.com/))
 - [AAAI'18 - Computational Solutions against Fake News: AI vs. DB Approaches]([https://john.cs.olemiss.edu/~nhassan/file/aaai2018tutorial.html](https://john.cs.olemiss.edu/~nhassan/file/aaai2018tutorial.html))
- [ICDM'17 -Mining Misinformation in Social Media:  
Understanding Its Rampant Spread, Harm, and Intervention]([http://www.public.asu.edu/~liangwu1/ICDM17MisinformationTutorial.html](http://www.public.asu.edu/~liangwu1/ICDM17MisinformationTutorial.html))


### Contributing


Please feel free to send me [pull requests](https://github.com/mdepak/fake-news-detection-resources/pulls) or email ([dmahudes@asu.edu](mailto:dmahudes@asu.edu)) / ([kai.shu@asu.edu](mailto:kai.shu@asu.edu)) to add resources.
