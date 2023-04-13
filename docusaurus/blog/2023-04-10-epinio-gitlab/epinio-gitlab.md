---
title: 'Epinio App Source Improvements'
description: Allowing the user more flexibility in how they create and export apps
authors: [sorin]
tags: [Epinio]
---


Based on user feedback, we've made 4 improvements to the Epinio UI which make it easier to create, update and export applications.

Epinio now supports Gitlab directly in the application deployment creation workflow. 
Users can create application deployments from Gitlab repositories:

![Step 1](./image4.png)

---

The application deployment creation UI now supports custom application variables (based on schema-ish metadata). 

![Step 2](./image2.png)

---

It's now possible to change the source of an existing application.

![Overview](./image3.png)

---

Users can export applications as a helm chart and corresponding container image(s). 

![Export](./image1.png)



