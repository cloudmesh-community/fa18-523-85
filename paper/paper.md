# Big Data Analytics in E-commerce :hand: fa18-523-85

|Bo Li
| bl15@iu.edu
| Indiana University Bloomington
| hid: fa18-523-85 
| github: [:cloud:](https://github.com/cloudmesh-community/fa18-523-85/blob/master/paper/paper.md)

---

Keywords: E-commerce, Consumer Behaviors, Python, TensorFlow, big data, deep
learning

---

## Abstract

In recent years, online shopping has become a more popular way of consuming.
Traditional retailers are eager to find a way to maintain revenue, online
retailers are also finding ways to extend the market. The rise of 'big data' had
impacted on marketing research and practice a lot. As technology developed, we
have huge data on consumer behaviors which could be very detailed and accurate,
but how to mine the data is a problem. In this article, we talk about the
application of big data in the consumer behaviors data, subsequently discuss how
the TensorFlow can translate the data into valuable conclusions in consumers
behaviors research.

## Introduction

The Big Data has a common definition, Big Data always comes with 3V: volume,
velocity, and veracity. The Internet allows us to do almost all work online and
keep records of our actions. If you listen to a song in the playlist, maybe
iTunes will record it as part of your individual activity log, which could be
the dataset that explores your interest. If you often use Uber to commute
between your home and your company, maybe they could picture your daily life
including the places that you have spent time in. If you use your device to
safari on the internet, your action of clicking on several links could also be
recorded and researched since the action contains you using habits and
preferences [@Matz2017Using,]. The online shopping data includes the consumer's
all kinds of information: age, job, education, catalog preferences, price
sensitivity, etc. But some of them are not presented to us directly, mining the
consumer behaviors is an appropriate way to get access to the hidden
information. How could we mine something meaningful to explore consumer
behaviors and provide valuable insight? The answer lies in several using cases
and the understanding of market research and also human psychology research.

## Technology Background

TensorFlow is an open source software library for numerical computation using
data flow graphs [@abadi2016tensorflow]. TensorFlow could help developers to
transform from code to graph, which could benefit developer in understanding
their work, and the term tensor, is generated in the process, as the tensor will
go from the beginning to the end of the graph, so the technology is called
TensorFlow. The process of computation could be done in CPU or GPU, as we know,
in blockchain, GPU works better than CPU since the fundamental design of GPU
fits better in the computation of mining coins. TensorFlow also has a data
visualization module called TensorBoard, which contains the common drawing tools
as well as some useful templates for the developers to visualize their data.
There is no doubt that the graph will be more clear than codes especially when
the structure of data is very complex. And the graph could give the readers a
direct presentation of the data, which is worthwhile since it could reduce the
communication cost between different developers.

There is a team in Google called Brain team, which is the initial developer of
TensorFlow, there original purpose of the development of this module is to
improve the efficiency of machine learning. For example, if the deep learning
task is to predict a result based on a training dataset, the more layers you
have, the more accuracy you will have. But more layers will cost much more time,
so TensorFlow is created to solve the problem. One more important thing is that
in the previous version of TensorFlow, it began to support distributed computing
which means more resources could be deployed in the process so the efficiency
will be boosted.

To support more developers, Python API and C APIs are also available in
TensorFlow. One thing that must be pointed out is that, although TensorFlow
supports many kinds of languages, the Python API is the most efficient one since
Python does better in the feedback process which focuses on improving the model.
And there are also more examples in Python since most of the machine learning
work is done by Python.

##  Big Data Applications in E-commerce

Since the design of the website is getting more complex than before, the users
may conduct different operations in different pages of the website, but most of
them are very import to provide an essential information for us to find the
customer's preferences.
>"There is a way to achieve that which is called four rights. Talk to the right audience, through the right channel, with the right message, at the right time" [@datameer2018article].

> "Customer acquisition: Marketing will target high-value customer segments identified by behavior analytics and study behavior patterns to determine the best potential offers. Customer engagement: Behavior patterns will be used to generate personalized next-best, cross-sell and up-sell offers, while behavioral customer segmentation will be used for more general customer marketing offers. Customer retention: Behavior patterns will be used to detect possible customer churn and generate next-best retention offers" [@datameer2018article].

The strategic meaning of big data is that deploying professional analysis on
those meaningful datasets generated from the E-commerce trading. The improvement
in the value of data is the most important part of the benefit of using big
data, especially compared with the previous situation, that the data useless
since the huge amount. Some meaningful things are hidden behind the big data,
mining them is the main task of the application. In the E-commerce domain, users
have generated huge amount data about their every action: browsing products,
clicking on the details of products, adding the products into the wishing list,
adding the products into the cart, delete the products from the wishing list,
clicking dislike product button and querying more information to the seller of
the products. Such information has been stored in the log document, but it is
too massive and fragmented to analysis it with limited technologies and
techniques.

Big data could help the enterprise to have a more profound understanding by
analyzing users behavior data, which allows the enterprise to establish
strategies with more specific aims. This could make the enterprise to be
competitive in the market and win more consumers' hearts. For example, the user
may want to buy a guitar for himself, and he has browsed several kinds of
guitars and could hardly to make his decision. The big data technologies could
base on his operation history to find his acceptable price level and the
specific version of guitar (such as with or without pick up system), then we can
put such requirements into our database to find the appropriate guitars and push
those potential choices to the user's interface, which could realize an
improvement in sales transformation rate.

TensorFlow could be a kind tool to analyze consumers behaviors since the model
of recommendation is doable in TensorFlow. Due to the feature of distributed
computation, the efficiency of the model is good enough for a small scale
recommendation system. To have a more profound understanding of user behavior, a
whole lifecycle of the user is needed to be established for the analysis of user
behavior.

## Features of User Behavior in the E-commerce Platform

The online platform is the main platform for e-commerce which lists the product
in different ways and provides the whole chain of finishing the trade. Different
from traditional commerce, online e-commerce has some special features which
could be used in the big data.

There are fewer limitations for consumers in the B2C pattern since the online
platform can run for 24 hours if it is well maintained. Consumers are able to
conduct any operation (browsing, selecting, finishing the trade) at any time in
anywhere.

The trading cost is much less than the traditional commerce pattern. For the
consumer, time cost, transportation cost and delivery cost are lower than the
traditional commerce pattern. Their trading action is much simplified by the
online shopping system, the trade can be done by several clicks on the mobile
device.

The online product can offer a more attractive price due to the advantages of
the internet. Comparing with the traditional commerce, online sellers have less
item to pay for maintaining the shop. There is a lot of extra costs for the real
store.

Customized service. The recommendation system is able to recommend the most
wanted goods for each customer based on their user behavior and the big data
technology, which is the traditional commerce cannot achieve due to the cost.
The customized service can benefit a lot in the transformation between browsing
and buying.

More kinds of product and no space limitations. Since the information of the
product is much smaller than the product itself, and the online store can
exhibit them all at the same time, so there are more choices presented for the
consumers.

The information is easy to get. Every item in the online platform has been
labeled by the system, so the search of the item is very convenient for
consumers, the cost is significantly lower than the traditional commerce.

## Applications

Due to the hotness of machine learning and deep learning, there are a lot of
applications in every domain. Search ranking and recommendation are the most
common two applications.
>"Recommendation systems in particular benefit from specialized features describing past user behavior with items" [@covington2016deep].

Just like search ranking, recommendation systems also have a problem of the
balance between memorization and generalization. Memorization can be seen as the
representing of the relationship between the products and users, which can be
extracted as vectors. Generalization is to generate rare feature combinations in
order to serve for the recommendation systems [@cheng2016wide].

TensorFlow, with so many advantages in machine learning, is very appropriate for
the recommendation system. Since the features of products could be learned by
multi-labels classification, and the user's features could be learned in his
historical actions in the online platform, which has the record of every
consumer's trading history. When we have both features of products and users, we
can establish a recommendation system by matching the two objects. Besides, the
model can be judged by the dot product between the two vectors.

To establish such a recommendation system, we need to fit the TensorFlow since
it is tensor that flows in the whole model. The transformation from dataset to
tensor is a necessary step to conduct the model. And the users', as well as the
products' character tensors, need to be transformed into the presentations of
users and products by the embedding function. The next step is to generate the
recommendation by the pair the presentations of users and products. Such pair of
presentations contains the most match user and product calculated by the model,
the vectors in the model contain all the information of the user and the
product. The last step is to compare the generated score and the actual comment
from users to define the result's quality, which is called loss function
[@csdn2018tensorflow].

TensorRec scores recommendations by consuming user and item features (ids, tags,
or other metadata) and building two low-dimensional vectors, a "user
representation" and an "item representation". The dot product of these two
vectors is the score for the relationship between that user and that item — the
highest scores are predicted to be the best recommendations.

The representation function in TensorRec can be set up by developer's
preferences, it could extract the features of users as well as products. It can
be very convenient for developers to set the parameters independently since the
scenario varies in different cases [@csdn2018tensorflow].

## Conclusion

Information is booming in recent years, data and internet techniques are
spreading in everywhere, with the significant effect on consumers' deciding
pattern and purchasing pattern. The digital economic on the internet has become
the focus of all the domain. For the biggest group in the digital economics in
the internet, online consumers are the focus in the specific domain. How to draw
the picture of the users and get the key feature of their behaviors have become
a hot topic.

Benefitted by the internet, we have all the records of most of the online
activities of users, but the relationship between those actions and the user's
features is ambiguous. Basing on the TensorFlow, we are able to use a
low-dimensional vector to represent the user's features as well as the products'
features. The algorithm allows us to extract the key point of users as well as
products, which provide a base for the recommendation of the product.

The big data technology can help us to mine the black box of the relationship
between the actions and the features. Several factors which measure the user's
preferences can represent the user, and those factors are also the key
parameters in the model. Once we get a clear picture of the user, we are able to
customize the recommendation, which can not only improve the user's experience
and also improve the revenue of the online retailer.   
