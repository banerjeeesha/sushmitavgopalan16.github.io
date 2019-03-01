---
layout: page
title: ''
---

##### Predicting Infant Mortality : Minimizing False Negatives 
&nbsp;
&nbsp;
<div style="text-align:justify" font size = '2'>Early experiments suggest that targeting public health resources on high-risk pregnant mothers can help reduce the risk of infant death in cost-effective ways. For my M.A. thesis at the University of Chicago, I applied machine learning to train a classifier to identify pregnant mothers who are at high risk for infant death, without requiring the input of a medical professional. The sparseness of observations about children who have died makes it difficult for a classifier to learn to identify them. Since it could be dangerous to misclassify at-risk children as being healthy, I focused on minimizing false negatives. I tested different resampling methods to address the class imbalance problem and found that removing Tomek links before using a random forest classifier helps reduce the false negative rate from 74% to 7%, while keeping the false positive rate at 6%. </div>
&nbsp;
&nbsp;
##### Class Imbalance in Machine Learning &nbsp;
&nbsp;
&nbsp;
<div style="text-align:justify" font size = '2'>I wrote a Shiny application to visually illustrate some ways to resample data to address class imbalance problems in machine learning. I love the storyboard format because it allows the reader to progress at their own pace and go back and forth if they need to. Each panel in the storyboard offers one method of resampling, graphs that compare the original and resampled data and a short explanation. You can look at it here. (link - https://sushmitavgopalan.shinyapps.io/storyboard/)</div>
&nbsp;
&nbsp;
##### Very Fun Tweets &nbsp;
&nbsp;
&nbsp;
<div style="text-align:justify" font size = '2'>Very Fun Tweets is a Django application that I wrote with my friends Haylee and Chelsea. Our app takes a hashtag, plots the frequency of its usage over a period of two months, identifies spikes, and uses keywords in related tweets to scrape Google News and find out what newsworthy event could have caused the spike. For instance, #womensmarch spiked on International Women’s Day in 2016 (http://time.com/4695030/international-womens-day-womens-march-strike/). Try it out at veryfuntweets.com. </div>
&nbsp;
&nbsp;
##### Judge a Magazine by its Cover (Story) &nbsp;
&nbsp;
&nbsp;
<div style="text-align:justify" font size = '2'>I scraped five years of cover stories and images from profiles in Vanity Fair magazine to explore the differences in the ways that men and women are interviewed in popular media using natural language processing. Male journalists write longer articles on average, than female journalists, but both write longer articles while interviewing someone of the opposite gender. Topics of discussion centered around family and the home are more likely to come up with same-gender pairs. Male journalists interviewing women are twice as likely to reference a part of the interviewee’s body as are female journalists interviewing men. Further, I used a residual neural net to score associated images on a scale of 0 to 1 on sexual content. Images of women consistently scored higher on this scale than men. </div>

