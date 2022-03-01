---
title: Attribution AI - Optimize marketing and advertising spend
description: Attribution AI - Optimize marketing and advertising spend
kt: 5342
audience: Data Engineer, Data Architect
doc-type: tutorial
activity: develop
exl-id: 
---
# 5.4 Attribution AI - Optimize marketing and advertising spend

With Attribution AI, marketers can measure and optimize marketing and advertising spend by understanding the impact of every individual customer interaction across each phase of the customers’ journeys.

## 5.4.1 Attribution AI - Create Schema

* Create a new schema using the Experience Events class:

* Add `End User ID Details` field group to your Experience Event class schema:

* Add `Consumer Experience Events` field group to your schema:

* Make sure your `mcid.id` field is recognized as primary identity:

* Name your schema: `LDAP - Demo System - Customer Experience Event AttributionAI` and enable it for profile

## 5.4.2 Attribution AI - Create Dataset

* Use the `Create dataset from schema` workflow:
* Select your new schema from 5.4.1:
* Name your new dataset: `LDAP - Demo System - Customer Experience Event AttributionAI Dataset`:

## 5.4.3 Attribution AI - Ingest Data

* You can download a new dataset here: 

* Drag and drop the file onto the dataset view `Add data`:

## 5.4.4 Attribution AI - Configure the service (video)

* Watch the into video here: https://experienceleague.adobe.com/docs/experience-platform/intelligent-services/attribution-ai/user-guide.html?lang=en#dataset-completeness 

* Name your application: `LDAP attributionAI demo 20220301 02`

* Select your dataset:

* Select the Media channel field in your dataset:

* Define your conversion events:

* Define your touchpoints:
- Email
- Social
- Display

* Set options: Leave as is.

## 5.4.5 Attribution AI - Analyze the results (video)

* Watch the intro video here: https://experienceleague.adobe.com/docs/experience-platform/intelligent-services/attribution-ai/discover-insights.html?lang=en


Next Step: [Summary and benefits](./summary.md)

[Go Back to Module 5](./intelligent-services.md)

[Go Back to All Modules](./../../overview.md)
