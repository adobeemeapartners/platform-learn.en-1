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

Reuse or create the schema from 5.1
<img width="525" alt="Screenshot 2022-03-01 at 15 06 52" src="https://user-images.githubusercontent.com/61875393/156184758-acb05184-22fc-454d-bd65-a15261936e84.png">

## 5.4.2 Attribution AI - Create Dataset

Reuse or create the dataset from 5.1
<img width="531" alt="Screenshot 2022-03-01 at 15 08 16" src="https://user-images.githubusercontent.com/61875393/156184784-a6023441-a697-45a3-bf4f-3d8eee7d0a08.png">

## 5.4.3 Attribution AI - Ingest Data

* You can download a new dataset here: 

* Enable dataset for Profile:

* Drag and drop the file onto the dataset view `Add data`:
<img width="528" alt="Screenshot 2022-03-01 at 15 09 59" src="https://user-images.githubusercontent.com/61875393/156184803-7f2449a8-dcda-40db-bcec-b1c78be2a361.png">

## 5.4.4 Attribution AI - Configure the service (video)

* Watch the into video here: https://experienceleague.adobe.com/docs/experience-platform/intelligent-services/attribution-ai/user-guide.html?lang=en#dataset-completeness 

* Name your application: `LDAP attributionAI demo 20220301 02`

* Select your dataset:

* Select the Media channel field in your dataset: `channel._type`

* Define your conversion events: Purchase Includes commerce.order.purchaseID exists

* Define your touchpoints:
  - Email: Email Includes channel._type equals https://ns.adobe.com/xdm/channel-types/email
  - Social: Social Includes channel._type equals https://ns.adobe.com/xdm/channel-types/social
  - Display: Display Includes channel._type equals https://ns.adobe.com/xdm/channel-types/display
  - Search: Search Includes channel._type equals https://ns.adobe.com/xdm/channel-types/search

* Set options: Leave as is.

## 5.4.5 Attribution AI - Analyze the results (video)

* Watch the intro video here: https://experienceleague.adobe.com/docs/experience-platform/intelligent-services/attribution-ai/discover-insights.html?lang=en


Next Step: [Summary and benefits](./summary.md)

[Go Back to Module 5](./intelligent-services.md)

[Go Back to All Modules](./../../overview.md)
