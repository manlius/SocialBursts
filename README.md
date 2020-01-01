# SocialBursts Multiplex Networks

This repository provides free access (under the GNU GPL v3) to the multiplex networks used in the paper:

*Unraveling the Origin of Social Bursts in Collective Attention*

M. De Domenico and E.G. Altmann

Scientific Reports X, Y-Z (2020)

# Introduction

In the era of social media, every day billions of individuals produce content in socio-technical systems resulting in a deluge of information. However, human attention is a limited resource and it is increasingly challenging to consume the most suitable content for one's interests. In fact, the complex interplay between individual and social activities in social systems overwhelmed by information results in bursty activity of collective attention which are still poorly understood. 
In the aforementioned paper, we tackle this challenge by analyzing the online activity of millions of users in a popular microblogging platform during exceptional events, from NBA Finals to the elections of Pope Francis and the discovery of gravitational waves. We observe extreme fluctuations in collective attention that we are able to characterize and explain by considering the co-occurrence of two fundamental factors: the heterogeneity of social interactions and the preferential attention towards influential users. Our findings demonstrate how combining simple mechanisms provides a route towards complex social phenomena.

# Description

Four files are provided. Each file contains one network, corresponding to the exceptional events dataset analyzed in this paper, namely

* [Religion] Pope Francis election (3 layers, X nodes)
* [Sport] NBA finals (3 layers, X nodes)
* [Science] gravitational waves discovery (3 layers, X nodes)
* [Culture] Cannes Film Festival (3 layers, X nodes)

and consists of 3 layers, corresponding to retweet, mentions and replies aggregated over time and observed between users.

The data is in extended edgelist format:

    nodeFrom layerFrom nodeTo layerTo weight

FOr each event, we provide a separate file for the temporal activity in the following format:

    nodeFrom nodeTo action timestamp

For further details about the calculation of weights, we refer to the aforementioned paper.

# Acknowledgments

The authors acknowledge the Max Planck Institute for the Physics of Complex Systems (Visitors program 2016).

# Credits

Please cite the accompanying paper, if you use this data set in your study.
