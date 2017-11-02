---
title: Analytics
layout: single
permalink: /modules/analytics/
author_profile: false
date: 2014-10-31 21:15:18.000000000 +00:00
type: pages
published: true
status: publish
categories: []
tags:
    - bootstrap
    - lot quality assurance sampling
    - probit
header:
  overlay_image: /assets/images/northstar.png
  caption: "Northstar map design by ©Mapbox"
sidebar:
  nav: "menu"  
---
{% include toc icon="gears" title="Contents" %}

We harness the advantages of classical but non-mainstream analytical techniques such as ***lot quality assurance sampling (LQAS)***, ***PROBIT function analysis*** and ***Bayesian analysis*** and computational techniques such as bootstrapping and resampling. All these techniques offer significant cost savings because they require or use small sample sizes.

We also specialise in ***geospatial sampling*** and ***geospatial analysis***.


## Lot quality assurance sampling
The challenges and costs for implementing multi-stage cluster-sample surveys such as the Demographic and Health Survey (DHS) and Multi-Indicator Cluster Survey (MICS) prohibit frequent outcome monitoring of various programmes. More frequent local area-level assessments of outcomes enable organisations to use results-based information to monitor, evaluate and then improve their programmes while also satisfying donor reporting requirements. Organisations need local level information to effectively steer and guide their programmes. Lot Quality Assurance Sampling or LQAS is an analysis approach that offers a solution to these requirements. LQAS can be used to classify geographical areas based on whether a specified coverage target has been reached. The key advantage of LQAS is its small sample size requirement for classification that are typically smaller than those required to perform other estimation analyses. Another is that LQAS provides critical information at the local level where organisations can take corrective action to improve their programmes.

Given the advantages offered by LQAS, Valid International has used it for cost-effective and rapid evaluation of outcomes for CMAM programmes at local and national scale and for beneficiary satisfaction surveys as part of a wider evaluation of the emergency response to the Typhoon Haiyan in the Philippines.
<br/><br/>


### Applying LQAS to assess beneficiary satisfaction with Typhoon Haiyan emergency response
![image-left](/assets/images/philippinesIAHEfinalReport-small.png){: .align-left}
As part of an overarching evaluation of the Typhoon Haiyan emergency response, Valid International conducted a beneficiary satisfaction survey to gather feedback from the perspective of marginalised people and communities from a sample of villages purposively selected based on their location and level of vulnerability. The survey focused on six components of humanitarian aid outlined in the strategic response namely food, shelter, livelihoods, water and sanitation, health and government services. In order to be able to report results representative of each village, an LQAS approach was performed. The survey was completed within 5 days by 8 enumerators.

For this survey, a two-standards, three-tier classification scheme was adapted. This classification scheme minimises gross classification errors. Two sets of two-standards was used for this survey. The first pair of standards is 50% and 80% which creates three classes labelled as low (≤ 50%), moderate (between 50% and 80%) and high (> 80%). This set of standards was used for indicators that go from low to high with high classification considered as good. Examples of this indicator are coverage indicators, satisfaction and recovery indicators. The other pair of standards is 20% and 50% which creates three classes labelled as low (≤ 20%), moderate (between 20% and 50%), and high (> 50%). This was used for indicators that go from high to low with high classification considered as bad. Overview of the results of the survey are shown in the interactive map below.

<iframe width="100%" height="600" frameborder="0" scrolling="no" seamless src="https://www.validmeasures.org/maps/philippinesHaiyanNeed.html"></iframe>

## PROBIT function for estimation of acute malnutrition prevalence
The PROBIT function, also known as the inverse cumulative distribution function or the quantile function, converts parameters of the distribution of an indicator such as the mean and standard deviation of a normally distributed variable into cumulative percentiles. The normal PROBIT function, with estimates of the mean and standard deviation of indicator values, can estimate the proportion falling below a given threshold.

![full](/assets/images/probitMUAC.png){: .full}

To assess acute undernutrition for example, data on mid-upper arm circumference (MUAC) measurements with a mean MUAC of 256 mm and a standard deviation of 28 mm, the output of the normal PROBIT function for a threshold of 210 mm is 0.050206247 meaning that 5.02% of the population surveyed are predicted to fall below the 210 mm threshold (assuming that MUAC is a normally distributed variable). Confidence intervals are calculated using standard techniques and submitting these to the PROBIT function. The main advantage of the PROBIT approach is that the required sample size is usually smaller than that required to directly observe the prevalence at a given threshold using a classical proportion estimator.

The PROBIT function is the basis of Valid International's development of rapid assessment methods for assessing health and nutrition indicators for various demographics including those for children (age 6-59 months) and older people (above 60 years).

In Sudan, UNICEF together with the Federal Ministry of Health and with support from Valid International implement a nutrition surveillance system that conduct quarterly nutrition surveys in Darfur State using rapid assessment methods that utilise the PROBIT function. This surveillance system has been in place since 2013.

![image-left](/assets/images/manualRAMOPsmall.png){: .align-left}
Rapid Assessment Method for Older People or RAM-OP is a rapid assessment method for measuring the nutritional status and needs, and other related factors that affect older people in humanitarian situations. It includes a questionnaire, a sampling method, and software for data analysis. It is a thorough, quick, simple, low-cost tool that allows humanitarian and development workers to obtain valuable information on older people's specific needs, including their nutritional status, through a household survey. RAM-OP was co-developed by HelpAge, Brixton Health and Valid International.

<br/>
<br/>
