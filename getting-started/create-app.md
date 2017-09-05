---
title: Chapter 1 - Create and Configure Your App
description: 
position: 11
publish: true
slug: gs-create-app
---

# Chapter 1 - Create and Configure Apps

In this chapter you are going to learn how to create and configure a new {{ side.ns }} app in {{ site.sk }}.

## Table of contents

* [1.1: Create a new app](#create-a-new-app)
* [1.2: Modify the app settings](#modify-the-app-settings)
* [1.3: Include a plugin](#include-a-plugin)

## 1.1: Create a new app

When you open Sidekick for the first time, you will see the **Create** and **Open** buttons. The Create button is used to create a new application and the Open button is used to load an already existing {{ side.ns }} project in {{ site.sk }}. 

In this tutorial we are going to create a new application. Select the Create button and lets begin.

When you click the Create button, the Create App dialog will appear.

* Select App Name
* Select Project Folder
* Select App ID or leave the default one.
* Select Project Type - There are three types of projects - JavaScript, TypeScript, Angular & TypeScript and each type offers 4 templates (Blank, Drawer Navigation, Tab Navigation and Master-Detail).

On the right-side you can see how the initial app will look on your iOS or Android device.

For this tutorial, you should choose the NativeScript + Angular & TypeScript project type and the Master-Detail. This is the most complete template and offers the most enriched experience.

Press the Create App button. This template contains a lot of dependencies so you might be required to wait a minute or two for its generation.

## 1.2: Modify the app settings

// Consider extracting this information in User Guide, provide links and suggest changes to the customer. This way this will feel more like a tutorial.

When the app creation process is complete, you will be redirected to the General App Settings panel of your app. Here you can modify some of the settings you provided before creating the app as well as some additional ones - Description, Author and Application Version.

The Application Version is used to create a uniform version for both iOS and Android. Originally, when you have just created the app, this field is grayed out. To enable it, you should open the Android tab in App Settings, set the Application Version Code to 10000 and then click the Save button. This action is required due to the nature of the version code and how it is calculated based on the Android Application Version.

In the iOS section you can...

In the Android section you can...

In the Assets section you can...

## 1.3: Include a plugin

The Plugins section is separated in 

In the Installed tab you can check all currently installed dependencies. From the Available tab, you can browse the npm registry for nativescript plugins. Lets find and install the nativescript-blablabla-plugin.
1. Enter nativescript-blablabla inside the search box.
2. Select the plugin.  
3. On the right hand side, click Install.




