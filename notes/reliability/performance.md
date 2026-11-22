---
title: Performance and capacity
description: "Keeping a product fast as its load grows: measuring latency, load testing, profiling and planning capacity ahead of demand."
why: "Latency climbs steeply as servers near full use, so a product can slow down long before anything fails. Load tests, profiles and capacity plans find the limit and its cause before customers do."
reviewed: 2026-11-22
sidebar:
  order: 3
tags: [performance, latency, load-testing, profiling, capacity-planning]
related: [reliability/observability, reliability/slos, architecture/system-design, architecture/caching, data/database-scaling, infrastructure/finops]
sources:
  - title: "The Tail at Scale"
    author: Jeffrey Dean and Luiz André Barroso
    url: "https://research.google/pubs/the-tail-at-scale/"
    agents: "https://www.barroso.org/publications/TheTailAtScale.pdf"
    type: paper
    year: 2013
    note: "A Communications of the ACM article by two Google Fellows on why rare slow responses from single servers become common when one request fans out to many servers. It describes techniques Google uses to tolerate this variability instead of removing every cause, such as hedged and tied requests."
  - title: "How NOT to Measure Latency"
    author: Gil Tene
    url: "https://www.youtube.com/watch?v=lJ8ydIuPFeU"
    type: talk
    year: 2015
    note: "A Strange Loop talk by the CTO of Azul Systems, a maker of Java runtimes, on common mistakes in measuring and reporting response times. It names coordinated omission, the load-testing flaw that leaves stalls out of the results, and presents HdrHistogram, his open source library for recording latency."
  - title: "Latency Sneaks Up On You"
    author: Marc Brooker
    url: "https://brooker.co.za/blog/2021/08/05/utilization.html"
    type: article
    year: 2021
    note: "A post by an AWS engineer that uses a simple queueing model to show how latency grows sharply as a server's utilization nears 100%. It explains why high-percentile latency drifts back up after efficiency work, and argues that it signals coming overload but measures efficiency poorly."
  - title: "Flame Graphs"
    author: Brendan Gregg
    url: "https://www.brendangregg.com/flamegraphs.html"
    type: guide
    year: 2011
    note: "The page of the performance engineer who created flame graphs, a picture of sampled stack traces that shows where a program spends its time. It explains how to read them, lists profilers that produce them, and links to variants for CPU, memory and off-CPU time."
  - title: "Capacity Planning"
    author: David Hixson and Kavita Guliani
    url: "https://www.usenix.org/system/files/login/articles/login_feb15_07_hixson.pdf"
    type: article
    year: 2015
    note: "A ;login: article by two Google SRE staff on capacity planning as shared work of engineering, product and finance. It covers modelling resources from a few demand drivers, separating steady growth from launches, and planning at least as far ahead as new capacity takes to arrive."
---
