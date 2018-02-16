---
title: Configure Proxy
description: Learn how to modify the proxy settings from within Sidekick
position: 0
publish: true
slug: proxy
---

# Configure Proxy

{{ site.ns-sk }} requires access to the internet to work correctly. If your Windows machine is behind a proxy server and you have not provided the correct settings to the {{ site.ns-cli }}, {{ site.sk }} will throw and error on start-up and become unresponsive. 

> When you are running behind a proxy, before you can launch and use {{ site.sk }}, you need to configure the proxy settings in the {{ site.ns-cli }}. For more information, see the [proxy set](https://github.com/NativeScript/nativescript-cli/blob/master/docs/man_pages/general/proxy-set.md) command. If you do not provide a username and password while setting the proxy, you will be prompted to enter them when you launch {{ site.sk }}.

## Procedure

1. Run the {{ site.ns-sk }} client and click on the settings icon in the top right corner.
1. In the **Settings** view, locate the **Proxy Settings** section.
1. Select the **Manual Settings** radio button.
1. In the **Proxy** text box, provide the IP address and port of your proxy.
1. (Optional) Enable **Strict SSL**. 
1. Click **Save**.

## Next Steps

Continue configuring {{ site.ns-sk }} by [choosing a preferred code editor]({% slug code-editor %}) or explore the [Getting Started Guide]({% slug gs-overview %}) to familiarize yourself further with the client.
