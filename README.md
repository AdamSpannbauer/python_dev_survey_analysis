# Python Dev Survey Analysis

Analysis of [Python Developers Survey 2019 Results](https://www.jetbrains.com/lp/python-developers-survey-2019/?utm_source=marketo&utm_medium=email&utm_campaign=pycharm&utm_content=newsletter&mkt_tok=eyJpIjoiTkRjM1lqUm1ZalUxTmpVNSIsInQiOiJOQVQrOHlTV1dtekREaHljMlhXcWZQeGc5Y2RHVk55QTRCam9LRVJWdkJkRVwvYk5hdm0yZTdxbEgzaVdaVk0rNzlHbnVORDVSR2xCRW5pQ1F0Z0lJRE9XTnFJcDFjVFA1TzJ4ZlJzQzJIVlJPNnpRYVRBTGpnNHdXWFZuYXJJcnoifQ%3D%3D) collected by JetBrains.

Raw data can be found here: [https://drive.google.com/drive/folders/1GW86M_QLFOA2KyeWeb8hzBj_RqQIXmAU?usp=sharing](https://drive.google.com/drive/folders/1GW86M_QLFOA2KyeWeb8hzBj_RqQIXmAU?usp=sharing)

Project was performed as a demo and this restricted the work to a < 1 week timeline.  The demo was to show how you might perform and present a cluster analysis.  This was the sole reason that a cluster analysis was performed over other techniques.

## Results of Cluster Analysis

Questions were analyzed in 3 groups: (1) how involved are you with, (2) general, & (3) how often do you.

#### How could analysis be used?

If these clusters were to be used to segment PyCharm customers.  The main groups might be:

* Less experienced programmers, interested in more Data Science focused features (Cluster 3)
* More experienced programmers, interested in more traditional Software Engineering features (Clusters 1 & 4)
* Python web developers that are likely more interested in tools for building web applications (Cluster 0)

Analyzing / polling these groups might lead to valuable market analysis of these segments.

#### Cluster differences on 'how involved are you with' questions

<p align='center'>
 <img src='readme/involved.png' width=90%>
</p>
- Our most experienced cluster is the most involved with varying techniques
- Our least experienced cluster is the most involved with more "Data Science" techniques
- Cluster 0 doesn't stand out in many ways other than their preference for web dev

#### Cluster differences on general questions

<p align='center'>
 <img src='readme/code_exp.png' width=70%>
</p>

Order of average coding experience: 4, 1, 0, 2, 3

<p align='center'>
 <img src='readme/py_exp.png' width=70%>
</p>

Order of average Python experience: 4, 0, 3, 2, 1

- Cluster 1 had the biggest change in experience compared to general programming experience. (they dropped from 2nd to last)
- Cluster 3 had the 2nd biggest change in experience compared to general programming experience. (they jumped from last to 2nd)

<p align='center'>
 <img src='readme/python_main_lang.png' width=70%>
</p>
- Cluster 1 are least likely to be primarily Python users
- Cluster 2 has ~20% secondary Python users
- Remaining clusters are primarily primary Python users

#### Cluster differences on 'how often do you' questions

<p align='center'>
 <img src='readme/often.png' width=90%>
</p>
- This explains why Cluster 2 exists. Cluster 2 was by far the least likely to mark that they did any of these activities 🤦.
- Cluster 4 (most experienced programmers) does most all of these activities the most. Cluster 0 is right behind.
- Cluster 3 (less experienced programmers) does most of these things the least.
- Cluster 0 doesn't stand out in many ways other than their preference for web dev.

#### Final Cluster Summary Statements

##### Cluster 0

Might be a group of Python web developers.  Could be of interest to see this cluster's affinity for flask / django / etc.

##### Cluster 1

Python is not their first choice for programming.  They are experienced programmers, and they use varying technologies and techniques

##### Cluster 3

Less experienced programmers with a focus on data science style tasks.  Is their lack of programming experience due to a lack of experience in industry or due to a heavier focus on the math/stats of data science tasks?

##### Cluster 4

Most experienced Programmers and most experienced Pythonistas.  They are more classical programmers than they are data scientists.

##### Cluster 2

Might not be a cluster of interest.  Membership seems mostly based on not answering the "How often do you... ?" series of questions.


### Limitations

* This analysis ignored many of the survey participants and many of the questions.
    * These decisions were made due to a short project timeline.
* Treating a lack of response as an indication of not using a technology / technique should be revisited.
* There is survey data available for 2017, 2018, & 2019.  Only 2019 was considered.  Could previous results be leveraged in analysis?

### How could analysis be used?

If these clusters were to be used to segment PyCharm customers.  The main groups might be:

* Less experienced programmers, interested in more Data Science focused features (Cluster 3)
* More experienced programmers, interested in more traditional Software Engineering features (Clusters 1 & 4)
* Python web developers that are likely more interested in tools for building web applications (Cluster 0)

Analyzing / polling these groups might lead to valuable market analysis of these segments.