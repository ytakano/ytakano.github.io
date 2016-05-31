---
layout: post
title: "Web Tracking"
description: ""
category: ["research", "visualization", "web"]
tags: ["visualization", "web tracking"]
---
{% include JB/setup %}

## [MindYourPrivacy: Design and implementation of a visualization system for third-party Web tracking](https://github.com/ytakano/ytakanospapers/tree/master/pst_2014)

Third-party web tracking is a serious privacy issue.
Advertisement sites and social networking sites stealthily collect users' web browsing history for purposes such as targeted advertising or predicting trends.
Unfortunately, very few Internet users realize this, and their privacy has been infringed upon since they have no means of recognizing the situation.
This paper presents the design and implementation of a system called MindYourPrivacy that visualizes third-party web tracking and clarifies the entities threatening users' privacy.
The implementation adopts deep packet inspection, DNS-SOA-record-based categorization, and HTTP-referred graph analysis to visualize collectors of web browsing histories without device dependency.
In order to demonstrate the effectiveness of our proof-of-concept implementation, we conducted an experiment in an IT technology camp, where 129 attendees discussed IT technologies for four days,
The experiment's results revealed that visualizing web tracking effectively influences users' perception of privacy.
The result of analysis of user data we collected at the camp also revealed that MCODE clustering and some features derived by graph theory are useful for detecting advertising sites that potentially collect user information by web tracking for their own purposes.

## Slide

<script async class="speakerdeck-embed" data-id="b6d7f1ae65c24da1b14437476c3cf9c8" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

## Pictures

[![webtracking](/assets/wide1309.png "Visualization of Web Tracking")](/assets/wide1309.png)

[![webtracking](/assets/wide1309_top5.png "Visualization of Web Tracking")](/assets/wide1309_top5.png)

[![webtracking](/assets/wide1309_mcode.png "Visualization of Web Tracking")](/assets/wide1309_mcode.png)

[![webtracking](/assets/wide1309_all.png "Visualization of Web Tracking")](/assets/wide1309_all.png)

