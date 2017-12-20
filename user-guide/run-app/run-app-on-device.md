---
title: Deploying Your App on a Device
description: 
position: 1
publish: true
slug: deploy-on-device
---

# Deploying Your App on a Device

To test your app during development, you can build and deploy them on connected devices. After you have launched a native iOS or Android device emulator, while the emulator is running, {{ site.sk }} recognizes and treats it as a connected device. When you run your app on a connected device, you can inspect the device log to troubleshoot your app.

With {{ site.ns-sk }}, you can deploy your app on multiple connected devices simultaneously.

## Prerequisites

* Verify that you have the latest official version of [iTunes](https://www.apple.com/itunes/download/).
* Verify that you have connected at least one physical device to your system or you have a running Android emulator or iOS simulator.
* To build and deploy an app on an iOS device, you need a valid certificate and mobile provision. If you have a Free Apple Developer account, you can use the [Code Signing Assistance]({% slug code-signing-assistance %}) to automatically generate temporary certificate and mobile provision. For more information about iOS code signing, see the [iOS Developer Program article]({% slug ios-developer-program %}).
* To build an app in Release configuration and deploy it on an Android device, you need a valid Google Play self-signed code signing identity.

## Procedure

1. Launch {{ site.ns-sk }} and open your app.
1. From the top toolbar, select **Run** &#8594; **Run on Device**.
1. Select one or more devices.
1. Select a **Build Type**.
1. Select a **Configuration**.
1. (Optional) Enable **Clean Build**. When you enable this option, any previously cached data will be ignored and your app will undergo a complete rebuild. This might be helpful if you experience sporadic build failures or other unexpected behavior. Clean Build is available only for Cloud builds.
1. (Optional) Enable **Start Debugger**. When you enable this option, a to begin a debug session as soon as the app is deployed on the device. Start Debugger is available only in Debug Configuration.
1. (Optional) If any issues are present, resolve them before you continue.
1. Click on **Run on Device**.
1. Once the build process is complete, the app will be automatically deployed on the device. 



