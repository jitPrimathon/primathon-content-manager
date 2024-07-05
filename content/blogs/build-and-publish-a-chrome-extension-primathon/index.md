---
title: Build and Publish a Chrome Extension | Primathon
date: 2024-07-05T13:26:22.635Z
---


Chrome extensions are everywhere. They change the whole chrome browsing and development experiences like using adblocker to block ads on any website or dark mode everywhere or website CSS inspector. Ever wondered how to build such extensions? Well, it is very easy to get started on building an extension.

> We are going to build an extension that will save any web URL and store them in chrome storage.

### What is a chrome extension:

Extensions are small software programs that customize the browsing experience. They enable users to modify Chrome functionality and behavior to individual needs or preferences. An extension should complete a single task like saving the web links or show unread emails. It can contain multiple components and a long-range of functionalities.\
\
They are built on web technologies such as `HTML`, `JavaScript`, `CSS` and the chrome APIs.

Let’s get started on building an extension.

### Step 1: Adding manifest.json

Every extension has a JSON formatted manifest file called manifest.json, which acts as an entry point of extension.\
It provides important information like extension version, user permissions, external resources. So, it is a registration file for everything we add in the extension like using a remote server file or using chrome storage.

Create a directory and add the manifest.json file in the root of it.

```json

```

This is the basic configuration stating the name of extension, description, version, and manifest_version which will be 2 as described by chrome.

### Step 2: Add this extension in chrome

This basic manifest file can be added to chrome extensions in development mode by following 3 easy steps:

1. Go to [extension home](chrome://extensions/) in your chrome browser.
2. Enable *developer mode* by clicking the toggle switch on the top right corner.
3. Click the *load unpacked button* in the top header and select the extension directory.