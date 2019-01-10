---
title: Update your apps to Unified Interface | Microsoft Docs
description: Step by step guide of how to update apps to Unified Interface
author: prsi-msft
manager: kvivek
ms.service: powerapps
ms.component: pa-admin
ms.topic: conceptual
ms.date: 1/10/2018
search.audienceType: 
  - admin
  - enduser
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---

# Update your apps to Unified Interface

With Unified Interface by Default, all your apps, including those designed for the legacy web client, run in Unified Interface all the time. Environments with legacy web client apps will show a notification on the Apps home page, prompting System Administrators to update those apps to Unified Interface, as shown below:

**You are using apps designed for the legacy web client. For the best user experience, update your apps to Unified Interface. [Learn more]()**
<insert Apps home page screenshot>

A similar notification will be visible to System Administrators whenever they use an app designed for the legacy web client, as shown below:

**This app is designed for the legacy web client which can cause unexpected errors and experience. For the best user experience, update your app to Unified Interface. [Learn more]()**
<insert App-specific screenshot>

Based on how the apps were installed on the environment, here's the recommended way to update them to Unified Interface:

## Apps created in your Sandbox environment
* Be sure to import the changes on your target environment via a managed solution only. See [Import, update, and export solutions](https://docs.microsoft.com/en-us/powerapps/maker/common-data-service/import-update-export-solutions) for guidance on installing an update to an existing managed solution.
* Modify the app properties by following the steps detailed in [Manage app properties](https://docs.microsoft.com/en-us/powerapps/maker/model-driven-apps/manage-app-properties), and set the **Client** type to **Unified Interface**
* Import the changes to your target environment via a managed solution update.

## Apps installed from AppSource
* Contact the app publisher and get a new version that updates the apps to Unified Interface

## Apps obtained from an ISV or any other 3rd party publisher
* Contact the ISV (Independent Software Vendor) or the 3rd party app publisher and get a new version that updates the apps to Unified Interface