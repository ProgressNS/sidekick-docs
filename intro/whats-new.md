---
title: Release Notes
description: This article contains a list of all minor Sidekick releases for a specific major version.
position: 4
publish: true
slug: whats-new
---

# Release Notes

### v1.5.0 - 16 February 2018

> To run {{ site.ns-sk }}, you need to have {{ site.ns-cli }} version **3.4.2** or later installed on your machine.

* **Introducing industry specific app templates**<br/>
The **Patient Care** and **Health Survey** templates can be accessed from the **Industry** tab in the **Create App** view. Both templates leverage the Progress Health Cloud and use Kinvey for back-end.

* **New UI for Create App **<br/>
**Create App** is no longer a separate dialog and the user interface is updated to reflect the addition of the industry specific templates. For more information about creating apps, see [Create App From Template]({% slug create-app-from-template %}).

### v1.4.0 - 12 February 2018

* **Switch between available accounts**<br/>
Members of multiple shared accounts can use the newly introduce user interface to quickly switch between all available accounts. For more information, see [Switch Accounts]({% slug switch-account %}).

### v1.3.0 - 1 February 2018

* **Open apps in your favorite code editor directly from {{ site.sk }}**<br/>
You can use the newly added **Open in Editor** button to quickly open the code of your application in a predefined code editor. For more information, see [Configure Code Editor]({% slug code-editor %}).

### v1.2.0 - 23 January 2018

* **Enable webpack for Cloud and Local Builds in Release Configuration**<br/>
Enable the webpack option in release builds to bundle your code and improve the performance of your application. For more information about webpack and how to use it in {{ site.sk }}, see [Bundle Your Code with webpack]({% slug webpack %}).

### v1.1.0 - 21 December 2017

* **Modify Your Proxy Settings**<br/>
On Windows systems, you can configure the proxy settings of {{ site.sk }} and the {{ site.ns-cli }} directly from the client. For more information, see [Configure Proxy Settings]({% slug proxy %}). 

* **Initial Environment Verification**<br/> 
When you launch the {{ site.ns-sk }} client, it will check if you have Node.js and {{ site.ns-cli }} installed on your machine. If any of those dependencies are missing, {{ site.sk }} will offer to download and install them automatically. This verification is available only when you run {{ site.sk }} on Windows and macOS systems.

### v1.0.0 - 07 November 2017

* **{{ site.ns-sk }} is officially released!**<br /> 
With the official release, we are introducing subscriptions. You can choose between several types of subscriptions, each offering different benefits. For more information, see the [official {{ site.ns-sk }} purchase page](https://www.nativescript.org/nativescript-sidekick/purchase).
