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

<img width="527" alt="Screenshot 2022-03-01 at 15 14 19" src="https://user-images.githubusercontent.com/61875393/156186060-44298b91-7718-462d-9126-e5b9c9a05f9c.png">

* Select your dataset:

<img width="528" alt="Screenshot 2022-03-01 at 15 15 38" src="https://user-images.githubusercontent.com/61875393/156186083-1c6dd279-384f-4af0-9f51-711b29878af2.png">

* Select the Media channel field in your dataset: `channel._type`

<img width="527" alt="Screenshot 2022-03-01 at 15 15 56" src="https://user-images.githubusercontent.com/61875393/156186107-096b4a60-406e-41fc-972a-cead4a3070c9.png">

* Define your conversion events: Purchase Includes commerce.order.purchaseID exists

<img width="526" alt="Screenshot 2022-03-01 at 15 16 12" src="https://user-images.githubusercontent.com/61875393/156186192-9a54c6a9-f367-4b06-9cd7-7b77ec8c725d.png">


* Define your touchpoints:
  - Email: Email Includes channel._type equals https://ns.adobe.com/xdm/channel-types/email
  - Social: Social Includes channel._type equals https://ns.adobe.com/xdm/channel-types/social
  - Display: Display Includes channel._type equals https://ns.adobe.com/xdm/channel-types/display
  - Search: Search Includes channel._type equals https://ns.adobe.com/xdm/channel-types/search

<img width="529" alt="Screenshot 2022-03-01 at 15 17 34" src="https://user-images.githubusercontent.com/61875393/156186222-259e91bd-12fb-4c55-a0f2-148d07398cf0.png">


* Set options: Leave as is.

<img width="530" alt="Screenshot 2022-03-01 at 15 18 35" src="https://user-images.githubusercontent.com/61875393/156186245-98b53044-e0b6-4679-975f-4042764e8503.png">


## 5.4.5 Attribution AI - Analyze the results (video)

* Watch the intro video here: https://experienceleague.adobe.com/docs/experience-platform/intelligent-services/attribution-ai/discover-insights.html?lang=en

<img width="528" alt="Screenshot 2022-03-01 at 15 22 36" src="https://user-images.githubusercontent.com/61875393/156186436-2205da80-3937-4b64-90ec-8b3a335f2874.png">


Next Step: [Summary and benefits](./summary.md)

[Go Back to Module 5](./intelligent-services.md)

[Go Back to All Modules](./../../overview.md)
