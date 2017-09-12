---
title: LiveSyncing Your Changes
description: 
position: 2
publish: true
slug: livesync-changes
---

# LiveSyncing Your Changes

The LiveSync functionality lets you make changes to your app and see those changes applied in real time across all connected devices and emulators. LiveSync is enabled automatically when you initiate a **Run on Device** in **Debug** configuration. 

Based on the type of the modified files, the LiveSync will behave differently:

* When you LiveSync modifications made to an XML, HTML or CSS file, in order for the changes to take effect, the app will refresh automatically.
* When you LiveSync modifications made to a JavaScript or TypeScript file, in order for the changes to take effect, the app will restart automatically.
* When you LiveSync modifications made to the app resources or plugins, in order for the changes to take effect, the app will be rebuilt, redeployed and launched again automatically.

## Procedure

1. Launch Sidekick and open your app.
1. Select **Run** &#8594; **Run on Device**.
1. Under **Configuration**, select **Debug + LiveSync**. This feature is available for both Cloud and Local builds.
1. Click on the **Run on Device** button and wait for the app to be deployed on the device.
