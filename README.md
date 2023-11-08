# Deep-Learning-in-Recommender-Systems


This repository contains the code base for my bachelor's thesis


## Summary
Recommender systems are employed by most companies, as they help their users overcome the information overload problem by providing relevant recommendations. 
At the same time, deep learning has revolutionized several areas of research with the ability to process natural data and learn complex representations. Hence, 
this paper investigates how deep learning can be applied, to improve the movie recommender system currently employed by a company. Deep learning has been implemented in 
recommender systems to perform a wide range of tasks, however, few studies have exploited the rich visual information contained in the movie poster. Hence, this paper
implemented the pretrained VGG16 model to extract a set of features describing each poster. To
include poster aesthetics in the recommendation process, poster similarity was measured on two
levels; on a group level by implementing a clustering algorithm and on a poster to poster level by
calculating a cosine similarity matrix. This paper did not identify groups of similar posters, but it
was found that poster similarity could be successfully measured, based on the features extracted by
the VGG16 model. Further, based on feedback from the company, it was found that information
about poster aesthetics is best utilized in combination with other information sources. Finally, this
paper provides an example of how the algorithm proposed in this paper is best implemented in a recommender system.



## RESULTS

![Figure 1](https://github.com/MadsBirch/Deep-Learning-in-Recommender-Systems/blob/master/similar_posters.png?raw=true) <br />
*Figure 1*
