---
title: Configure Proxy Settings
description: Learn how to modify the proxy settings from within Sidekick
position: 0
publish: true
slug: proxy
---

# Configure Proxy

{{ site.ns-sk }} requires access to the internet to work correctly. If your Windows machine is behind a proxy server and you have not provided the correct settings to the {{ site.ns-cli }}, {{ site.sk }} will throw and error on start-up and become unresponsive. 

> When you are running behind a proxy, before you can launch and use {{ site.sk }}, you need to configure the proxy settings in the {{ site.ns-cli }}. For more information, see the [proxy set](https://github.com/NativeScript/nativescript-cli/blob/master/docs/man_pages/general/proxy-set.md) command. If you do not provide a username and password while setting the proxy, you will be prompted to enter them when you launch {{ site.sk }}.

## Procedure to Modify the Proxy Settings in Sidekick

1. Launch {{ site.ns-sk }}.
1. Click on the settings icon located in the top right corner of the client.
1. In the **Settings** view, under **Proxy Settings**, make the necessary modifications to the Proxy URL.
1. (Optional) Enable **Strict SSL**. 
1. Click **Save**.
