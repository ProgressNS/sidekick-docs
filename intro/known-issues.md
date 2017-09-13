---
title: Known Issues
description: 
position: 5
publish: true
slug: known-issues
---

# Known Issues

* When you select, install, update or remove plugins from the **Plugins** tab in App Settings, you might experience an `Internal server error`.<br/>
**Workaround:** Install the plugins manually from a command-line terminal (Command Prompt on Windows, Terminal on macOS and Linux). 

* When you use `.keystore` or `.jks` certificates, the Release Cloud build for Android fails and the following error message appears: `Only 8, 16, 24, or 32 bits supported: 872`.<br/>
**Workaround:** Use `.p12` certificates instead. 

* On Windows, if the combined length of the base folder (in which you create the app) and the app folder name is greater than 60 symbols, you cannot build locally for Android. The process fails and the following error message appears: `Error: Failed to crunch file <Path To File>`.<br/>
**Workaround:** Ensure that the combined character length of the base folder name and the app name is less than 60 symbols. 

* You cannot install NativeScript Sidekick on a Windows 7 Professional system that does not have .NET Framework 4.5 installed.<br/>
**Workaround:** Install .NET Framework 4.5 and then install NativeScript Sidekick. 

* On an Android device, when you start a debugging session, the app becomes temporarily unresponsive.<br/>
**Workaround:** Wait for a couple of seconds and if the `App isn't responding` pop-up appears, select **Wait**. 

* On macOS and Linux, you cannot build your app if it is located on a partition that forbids file execution. The build fails immediately with the following error message: `SASS compiler failed with exit code 1.`. <br/>
**Workaround:** Allow file execution for the respective partition or move your project to a different partition. 

* On an Android device, when you start and instantly stop a debugging session multiple times in a row, the app may become unresponsive and close.<br/>
**Workaround:** None.  

* When you are using npm 5.0.0, 5.0.1 or 5.0.2, Sidekick cannot install one of its dependencies and you will not be able to build in the cloud.<br/>
**Workaround:** Install npm 5.0.3 or later.  

* When you debug, expanding the **Global Listeners** panel will show an error message in the Chrome DevTools console.<br/>
**Workaround:** None.

* When you debug, breakpoints placed in JavaScript files will be transferred to incorrect positions in the TypeScript files.<br/>
**Workaround:** Place breakpoints only in the TypeScript files.

* On macOS, the local iOS build cannot complete if no default development team is specified in the native Xcode project.<br/>
**Workaround:** Open Xcode and log in with your development account.

* On macOS, when you are a member of two or more development teams, the local iOS build cannot complete and the following error message appears: `Error: Unable to determine default development team. Available development teams are: YOUR_TEAM_ID, YOUR_TEAM_ID`.<br/>
**Workaround:** Manually select a team.
 1. In your app folder, navigate to `app/AppResources/iOS` and open the `build.xcconfig` file.
 2. (Optional) If the `build.xcconfig` file does not exist, create it manually.
 3. Specify a team id by entering `DEVELOPMENT_TEAM = YOUR_TEAM_ID`. You can obtain `YOUR_TEAM_ID` from the error message or from the [Apple Developer portal](https://developer.apple.com/account/#/membership). 

* On Android devices, when you build and LiveSync your app in the NativeScript CLI and then attempt to build and deploy it on a connected device in NativeScript Sidekick, you might experience issues. The app might not update correctly and retain its state from the last build in the NativeScript CLI.<br/>
**Workaround:** Delete the `/data/local/<app-id>` folder from the affected device. You can accomplish this by running the following commands - first the `adb shell` command and after that the `rm -rf data/local/tml/<app-id>` command.

* On macOS, local iOS builds against XCode 8.3 throw `ENOENT: no such file or directory` error.<br/>
**Workaround:** None.
