---
layout: post
title: "Measurement of DNS Open Resolvers"
description: ""
category: ["Internet", "research", "DNS", "visualization"]
tags: ["DNS", "open resolver", "DDoS", "visualization"]
---
{% include JB/setup %}

## The Ecology of DNS Open Resolvers

DNS amplification attack is a DDoS attack by abusing DNS open resolvers as
reflectors.
Because the attack can amplify attacker's traffic dozens of times by reflectors,
attackers can efficiently launch DDoS attack even though they have only
low bandwidth network.
Therefore, in this paper, we investigated DNS open resolvers abused by
DNS amplification attack from 3 aspects of wide active probing,
silent monitoring and deploying open resolvers.
As a result of our active probing, we found about 30 millions of DNS
servers on the Internet, and 25 millions of them are open resolvers.
Then, by silent monitoring and deploying open resolvers,
we found that A record requests are often used by probing DNS servers,
and ANY record requests are often used to launch DDoS attack.
Moreover, we reveal that source network of the attackers could be traced
by combining these results and BGP's routing information.

## A Measurement Study of Open Resolvers and DNS Server Version

DNS is one of the most important infrastructure of the Internet,
but it unfortunately suffers from malicious attacks,
such as DDoS and cache poisoning.
Study and investigation of currently-deployed DNS servers are needed
to implement effective and efficient countermeasure.
To cope with that, we sent probing requests to
the whole IPv4 address space and collected DNS-related information, i.e.,
DNS server type distribution, DNS server software version distribution
and FQDN distribution of DNS server.
The measurement result shows that we obtained the addresses of
about 30 million DNS servers, about 25 million open resolvers,
and about 7 million DNS servers that responded to software version query
request.
Furthermore, we reversely looked up the DNS servers' addresses
to investigate the distribution of domain names.
It revealed that there are many open resolvers in spammer-favored domains.
We also discuss the relationship between the DNS amplification attack,
a type of DDoS attack that abuses open resolvers,
DNSSEC, and its countermeasures.
DNSSEC significantly increases efficiency of the DNS amplification
attack since its records typically amount to tens of thousand bytes.

## Links

- [The Ecology of DNS Open Resolvers](https://github.com/ytakano/ytakanospapers/tree/master/ieice_201410_en)
- [A Measurement Study of Open Resolvers and DNS Server Version](https://github.com/ytakano/ytakanospapers/tree/master/ic_2013)

## Slide

<script async class="speakerdeck-embed" data-id="0077d6fc2059446d9fbf8d7c1ae2e2e6" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>

## Picture

[![openresolver](/assets/open_dns_resolver_heatmap_201307.png "Visualization of DNS Open Resolvers")](/assets/open_dns_resolver_heatmap_201307.png)

---
