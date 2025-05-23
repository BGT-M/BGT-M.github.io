---
title: "FlowScope: Spotting Money Laundering Based on Graphs"
date: 2020-04-03
tags:
  - Graph
links: 
 - name: git repository
   url: "https://github.com/BGT-M/spartan2-tutorials/blob/master/FlowScope.ipynb"
---

<!--more-->

Given a graph of the money transfers between accounts of a bank, how can we detect money laundering? Money laundering refers to criminals using the bank’s services to move massive amounts of illegal money to untraceable destination accounts, in order to inject their illegal money into the legitimate financial system. Existing graph fraud detection approaches focus on dense subgraph detection, without considering the fact that money laundering involves high-volume flows of funds through chains of bank accounts, thereby decreasing their detection accuracy. Instead, we propose to model the transactions using a multipartite graph, and detect the complete flow of money from source to destination using a scalable algorithm, FlowScope. Theoretical analysis shows that FlowScope provides guarantees in terms of the amount of money that fraudsters can transfer without being detected. FlowScope outperforms state-of-the-art baselines in accurately detecting the accounts involved in money laundering, in both injected and real-world data settings.
