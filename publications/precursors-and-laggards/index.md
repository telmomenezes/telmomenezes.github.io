---
layout: default
title: Precursors and Laggards
---

# Precursors and Laggards
## An Analysis of Semantic Temporal Relationships on a Blog Network

**Authors:** Telmo Menezes, Camille Roth and Jean-Philippe Cointet
_IEEE International Conference on Social Computing, SocialCom10, Minneapolis, USA, August 2010_

[Download Preprint (PDF)]({{ site.baseurl }}resources/SocialCom10_preprint_Menezes.pdf)
[Download Presentation (PDF)]({{ site.baseurl }}resources/SocialCom10_presentation_Menezes.pdf)
[arXiv](http://arxiv.org/abs/1009.0119)

## Media Mentions

[L'Atelier.fr (in French)](http://www.atelier.fr/reseaux/10/02092010/blog--reseaux-sociaux--moteur-de-recherche--ranking-40185-.html)

## Abstract

Most current methods of quantifying the contribution of nodes in blog networks do not account for temporal relationships. We provide a method for measuring how early or late bloggers typically are, in the topic flow of a network of related blogs. Furthermore, we show that this type of analysis adds to the knowledge that can be extracted by studying the network only at the structural level of URL links. We present an algorithm to automatically detect fine-grained discussion topics, characterized by n-grams and time intervals. We then propose a probabilistic model to estimate the temporal relationships that blogs have with one another. We define the precursor score of blog A in relation to blog B as the probability that A enters a new topic before B, discounting the effect created by asymmetric posting rates. Network-level metrics of precursor and laggard behavior are derived from these dyadic precursor score estimations. This model is used to analyze a network of French political blogs. The scores are compared to traditional link degree metrics. We obtain insights into the dynamics of topic participation on this network, as well as the relationship between precursor/laggard and linking behaviors. We validate and analyze results with the help of an expert on the French blogosphere. Finally, we propose possible applications to the improvement of search engine ranking algorithms.

## BibTEX

    @INPROCEEDINGS{menezes2010,
        title={Precursors and Laggards: An Analysis of Semantic
        Temporal Relationships on a Blog Network},
        author={T. Menezes and C. Roth and J-P. Cointet},
        booktitle={Proc. of the 2010 IEEE International
        Conference on Social Computing},
        pages = {120--127},
        year={2010},
        month={Aug},
        location = {Minneapolis, MN, USA},
        doi={10.1109/SocialCom.2010.26}
    }