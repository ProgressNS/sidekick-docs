---
title: Chapter 1 - Create and Configure Your App
description: 
position: 11
publish: true
slug: gs-create-app
---

# Chapter 1 - Create and Configure Your App

In this chapter you are going to learn how to create and configure a new {{ side.ns }} app in {{ site.sk }}.

## Table of contents

* [1.1: Create a new app](#create-a-new-app)
* [1.2: Modify the app settings](#modify-the-app-settings)
* [1.3: Include a plugin](#include-a-plugin)

## 1.1: Create a new app

When you launch {{ site.ns-sk }}, you are presented with a view that shows a list of all available applications. If you open the client for the first time, instead of a list of apps, you will see only the **Create** and **Open** buttons.

Now let us inspect the user interface. From the top toolbar, you can create a new app, open existing one, filter 

When you open {{ site.ns-sk }} for the first time, you will see the **Create** and **Open** buttons. In this tutorial we are going to create a new application. Click the **Create** button to bring up the **Create App** dialog. 

Do not worry if you get something wrong. Most of these settings can be modified later on from the App Settings section. While it is not possible to change the Project Type of an already created project, it is not impossible to turn a JavaScript Blank project into a Angular & TypeScript one, it will just take  time and effort.

Press the Create App button. This template has a lot of dependencies and you might need to wait a minute or two for its generation.

## 1.2: Modify the app settings

Now that the app is created, lets see how we can modify some of its settings.
// Consider extracting this information in User Guide, provide links and suggest changes to the customer. This way this will feel more like a tutorial.

When the app creation process is complete, you will be redirected to the General App Settings panel of your app. Here you can modify some of the settings you provided before creating the app as well as some additional ones - Description, Author and Application Version.

The Application Version is used to create a uniform version for both iOS and Android. Originally, when you have just created the app, this field is grayed out. To enable it, you should open the Android tab in App Settings, set the Application Version Code to 10000 and then click the Save button. This action is required due to the nature of the version code and how it is calculated based on the Android Application Version.


General Settings: Create a uniform versioning for your application.
iOS Settings: Device Families : iPhone and Supported Interface Orientations: select only Portrait.
Android Settings: Target SDK Version:


## 1.3: Include a plugin

The Plugins section is separated in 

In the Installed tab you can check all currently installed dependencies. From the Available tab, you can browse the npm registry for nativescript plugins. Lets find and install the nativescript-blablabla-plugin.
1. Enter nativescript-blablabla inside the search box.
2. Select the plugin.  
3. On the right hand side, click Install.

<div class="next-chapter-link-container">
  <a href="build">Continue to Chapter 2 - Build Your App</a>
</div>




