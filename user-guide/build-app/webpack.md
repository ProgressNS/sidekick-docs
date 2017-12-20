---
title: Bundle Your Code with Webpack
description: 
position: 3
publish: true
slug: webpack
---

# Bundle Your Code with Webpack

Webpack is a module bundler for modern JavaScript applications. When webpack processes your application, it recursively builds a dependency graph that includes every module your application needs, then packages all of those modules into a small number of bundles. This is significantly reducing the code size of your application, especially if you are using Angular. Bundling also plays an important role in mobile app optimization. For example, fewer file system operations will be made when the app is launched because all the code is loaded from a single bundle file and this will improve the app starting time significantly. 

Webpack is also highly configurable and extensible - you can customize every step of the bundling process and add support for all sorts of asset generation and manipulation procedures, for example - code minification.

## Install and Configure Webpack

Since every project is unique and can have quite complex requirements for bundling we tried to make webpack configuration as simple as possible. After installation, the plugin will configure the bundling dependencies, and add a basic configuration that should work for most projects. Developers can (and should) extend that to fit their specific project needs. 

To enable the webpack option for your application, you need to install the latest version of the [nativescript-dev-webpack](https://github.com/NativeScript/nativescript-dev-webpack) plugin as a devDependency. To install the plugin, open a Terminal or Command Prompt in the root folder of your app and run the following command:
```
$ npm install --save-dev nativescript-dev-webpack@latest
```
The plugin adds a few dependencies to the project. Do not forget to install them:
```
$ npm install
```

After you install the plugin and its dependencies, you can enable webpack for [Local]({% slug local-build %}) and [Cloud]({% slug cloud-build %}) builds in **Release** configuration.

> To use webpack in apps created with {{ site.ns-cli }} 3.3.0 or older and {{ site.sk }} 1.0.0 or older you might be required to make additional modifications.

## See Also

* [Webpack Getting Started](https://webpack.js.org/guides/getting-started/)
* [Using Webpack to Bundle Your Code in the NativeScript CLI](https://docs.nativescript.org/angular/best-practices/bundling-with-webpack)