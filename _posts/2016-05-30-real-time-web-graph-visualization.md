---
layout: post
title: "[Real-time Web Graph Visualization by Using SF-TAP]"
description: ""
category: ["visualization", "traffic analysis"]
tags: ["visualization", "web graph", "SF-TAP"]
---

## SF-TAP: Scalable and Flexible Traffic Analysis Platform Running on Commodity Hardware

Application-level network traffic analysis and sophisticated analysis techniques
 such as machine learning
and stream data processing for network traffic require considerable computational
resources.
In addition, developing an application protocol analyzer is a tedious
and time-consuming task.
Therefore, we propose a scalable and flexible traffic analysis platform (SF-TAP) that provides an efficient
and flexible application-level stream
analysis of high-bandwidth network traffic.
Our platform's flexibility and modularity allow developers to easily
implement multicore scalable application-level stream analyzers.
Furthermore, SF-TAP is horizontally scalable and can therefore manage
high-bandwidth network traffic.
We achieve this scalability by separating network traffic
based on traffic flows, forwarding the separated flows to multiple
SF-TAP cells, each of which consists of a traffic capturer and
application-level analyzers.
In this study, we discuss the design and implementation of SF-TAP
and provide details of its evaluation.

## Links

- [SF-TAP: Scalable and Flexible Traffic Analysis Platform Running on Commodity Hardware (USENIX LISA 2015)](https://www.usenix.org/conference/lisa15/conference-program/presentation/takano)
- [SF-TAP - http://sf-tap.github.io/](http://sf-tap.github.io/)
- [SF-TAP - https://github.com/SF-TAP](https://github.com/SF-TAP)

## Visualize Web Graph by Using SF-TAP

<iframe width="560" height="315" src="https://www.youtube.com/embed/G9xbGHxVxXc" frameborder="0" allowfullscreen></iframe>

[![chakra](/assets/chakra.png "CHAKRA: Big Data Visualization System"){:width="100%"}](/assets/chakra.png)

[![lisaposter](/assets/usenix_lisa2015_poster.png "SF-TAP Poster - USENIX LISA 2015"){:width="100%"}](/assets/usenix_lisa2015_poster.pdf)

## Slides

<script async class="speakerdeck-embed" data-id="1cadedf3f63944c2b7da9101296cf029" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

<script async class="speakerdeck-embed" data-id="ddb3a8f1c88e44dc9894a598f2c411b3" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

---
