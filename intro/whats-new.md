---
title: Release Notes
description: 
position: 4
publish: true
slug: whats-new
---

# What's New in Sidekick 0.2.4

> To run {{ site.ns-sk }}, you need to have {{ site.ns-cli }} version 3.2.1 or later installed on your machine. 

* **Debug and LiveSync Working Together**<br/> You no longer need to disable the LiveSync to start a debugging session and you can sync your changes without stopping the debugger. 

* **Code Signing Assistance**<br/> If you have a **Free Apple Developer** account, you can use this functionality to create temporary certificates and  mobile provisions which can be used to deploy and test your app on an iOS device. For more information, see [Code Signing Assistance]({% slug code-signing-assistance %}).

* **Create a Certificate Signing Request**<br/> You can now create a Certificate Signing Request (CSR) in Sidekick. The CSR is a prerequisite for creating a certificate in the iOS Dev Center. For more information, see [Create a Certificate Signing Request]({% slug create-csr %}).

* **Updated App Settings**<br/> You can now set the Minimum and Target SDK versions from the Android tab of App Settings. For more information, see [Android Settings]({% slug android-properties %}).

* **Notable Resolved Issues**
	* When you debug apps deployed on an iOS device, the expressions in the Watch panel are not respected.
