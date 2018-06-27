---
layout: post
title:  "DeepNilm: A deep learning approach to non-intrusive load monitoring"
date:   2018-02-22
excerpt_separator: <!--more-->

tags: presentations
---
Venue: [Heidelberg.AI](http://heidelberg.ai/), Heidelberg, Germany
[Talk Slides]({{ "/images/DeepNilm_22022018.pdf" | absolute_url }})

As deep learning methods mature, they increasingly find their way into real-world applications. One exciting area of application is the energy sector and this meetup will have Discovergy - a company that works on making private energy consumption and generation more transparent and controllable - elaborate on how they employ machine learning methods to this end.

Research in non-intrusive load monitoring aims to infer the appliance level energy consumption from the aggregate building consumption data reported by smart meters. Most of the work in the field has focused on identifying events in the time series using hand engineered features. This process can be time consuming and often proves insufficient in capturing the information necessary to identify all the different appliances.

Discovergy instead leverages recent advances in deep learning to automatically learn features for individual appliances. This talk will begin with an overview of Discovergy's approach including some tricks that helped train the neural network systems and improve their generalization performance. Insightful visualizations that illustrate the kind of features the neural networks have learnt to recognize, will be shared alongside. The talk will wrap up with a demonstration of Discovergy's live platform which provides a detailed breakdown of energy consumption per appliance to each individual customer.



