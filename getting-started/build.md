---
title: Chapter 2 - Build Your App
description: 
position: 12
publish: true
slug: gs-build
---

# Chapter 2 - Build Your App

In this chapter you are going to learn how you can use {{ site.sk }} to build your app for Android and iOS.

## Table of contents

* [2.1: Build for Android](#23-build-for-android)
* [2.2: Build for iOS](#24-build-for-ios)

## 2.1: Build for Android

> To build locally for Android, you need to have configured your system for local builds.

> To build for Android in Release configuration, you need a valid Google Play certificate. How to obtain one is explained here.

To build your app for Android you need to:

1. Open your app in Sidekick.
2. From the top bar select **Run** -> **Build**.
3. In the newly opened **Build** view, select the Android icon.
4. Choose Build Type. (Cloud or Local)
5. Choose Configuration. (Debug)
6. Click Build and wait for the process to complete.
7. (Optional) If the build fails, an error message will be shown in the Output tab.
8. A successful build will produce a QR code and a local path to the APK file. The QR code can be scanned with most Barcode Scanners. Scanning the QR code will download the app directly to your device from where you have to install it manually.
9. Press **Done** to return to the Build view.

## 2.2: Build for iOS

> To build locally for iOS, you need to have a properly configured macOS system.

> To build for iOS, you need to have a valid iOS certificate and provisioning profile. How to create an iOS certificate is explained here. How to create a provisioning profile is explained here. To build in debug mode you can use the Auto Generate tool that we offer.

1. Open your app in Sidekick.
2. From the top bar select **Run** -> **Build**.
3. In the newly opened **Build** view, select the iOS icon.
4. Hover on the iOS icon and click on the **cogwheel** to open the **Manage iOS Provisioning and Certificates** dialog.
5. (Optional) If you do not have valid provisioning profile and certificate, you should click on **Auto Generate** and check the instructions in the [iOS Code Signing Assistance article]().
6. In the **Manage iOS Provisioning and Certificates** dialog, click Select Provision and select a valid mobile provision file. Then click on Select Certificate and select a valid certificate file.
7. Choose Build Type.
8. Choose Configuration.
9. Click **Build** and wait for the process to complete.
10. (Optional) If the build fails, an error message will be shown in the Output tab.
11. A successful build will produce local path to the IPA file. You have to manually install it on the device.
12. Press **Done** to return to the Build view.

<div class="next-chapter-link-container">
  <a href="run-on-device">Continue to Chapter 3 - Run Your App on a Device</a>
</div>