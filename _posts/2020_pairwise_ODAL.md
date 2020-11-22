---
layout: post
title: An efficient distributed algorithm with application to COVID-19 data from heterogeneous clinical sites
comments: true
---

Objectives: Integrating electronic health records (EHR) data from several clinical sites offers great opportunities to improve estimation with a more general population compared to analyses based on a single clinical site. However, sharing patient-level data across sites is practically challenging due to concerns about maintaining patient privacy. The objective of this study is to develop a novel distributed algorithm to integrate heterogeneous EHR data from multiple clinical sites without sharing patient-level data.

Materials and Methods: The proposed distributed algorithm for binary regression can effectively account for between-site heterogeneity and is communication-efficient. Our method is built on a pairwise likelihood function in the extended Mantel-Haenszel regression, which is known to be statistically highly efficient. We construct a surrogate pairwise likelihood function through approximating the target pairwise likelihood by its surrogate. We show that the proposed surrogate pairwise likelihood leads to a consistent and asymptotically normal estimator by effective communication without sharing individual patient-level data. We study the empirical performance of the proposed method through a systematic simulation study and an application with data of 14,215 COVID-19 patients from 230 clinical sites at UnitedHealth Group Clinical Research Database.

Results: The proposed method was shown to perform close to the gold standard approach under extensive simulation settings. When the event rate is <5%, the relative bias of the proposed estimator is 30% smaller than that of the meta-analysis estimator. The proposed method retained high accuracy across different sample sizes and event rates compared with meta-analysis. In the
data evaluation, the proposed estimate has a relative bias <9% when the event rate is <1%, whereas the meta-analysis estimate has a relative bias at least 10% higher than that of the proposed method.

Conclusions: Our simulation study and data application demonstrate that the proposed distributed algorithm provides an estimator that is robust to heterogeneity in event rates when effectively integrating data from multiple clinical sites. Our algorithm is therefore an effective alternative to both meta-analysis and existing distributed algorithms for modeling heterogeneous multi-site binary outcomes.

medRxiv link: https://www.medrxiv.org/content/10.1101/2020.11.17.20220681v1.full

![title](/img/figure1.png)
