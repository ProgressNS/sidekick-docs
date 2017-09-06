---
title: Create a Certificate Signing Request
description: This document explains how you can create a certificate signing request by using NativeScript Sidekick.
position: 2
publish: true
slug: create-csr
---

# Create a Certificate Signing Request

Creating a certificate signing request (CSR) is a prerequisite for creating a certificate in the [iOS Dev Center](https://developer.apple.com/membercenter). If you do not have a tool to create a certificate signing request, you can still create it by using {{ site.sk }}.

## Prerequisites

* Verify that you have installed {{ site.ns-sk }}. For more information, see [Set Up Your System and Install Sidekick]({% slug installation %}).

## Procedure

1. Start {{ site.ns-sk }}.
2. In the main menu bar, click **Tools** &#8594; **Certificate Signing Request**. 
3. Specify name, email and country.
4. Click **Create CSR**.
5. Specify name and download location for the `CSR` file and confirm the download by clicking **Save**.

## Next Steps

Create a **[certificate for development]({% slug create-development-certificate %})** or **[a certificate for production]({% slug create-distribution-certificate %})** in the [iOS Dev Center](https://developer.apple.com/membercenter).