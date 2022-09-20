---
title: "Introduction"
chapter: true
weight: 10
---


## Introduction

### Why use the Demo Extension?

The Demo Extension is ideal to quickly show your customer what it would be like to have their corporate website powered by Genesys Cloud.

The Demo Extension showcases Genesys Widgets, Predictive Engagement and lets you engage with PureCloudNow or your own Genesys Cloud organization.

### The extension offers 2 main features categories:

- Widgets v1 based channels: chat v1, cobrowse/screenshare, email, callback
- Widgets v2 chat with Predictive Engagement (Predictive Engagement)

This guide puts the emphasis on Widgets v2 chat and predictive, where the latest and more compelling use cases can be shown to potential customers.

Building a demo means that you can customize the browsing experience without any coding, by adding customized actions that execute when you click on live page elements. For instance, you can decide to send an Predictive Engagement event when clicking on an existing button, or any element you see on a page.
A demo configuration is a list of {condition, action} pairs that is associated to a set of pages, for a particular domain.
The extension saves the demo configuration in the Chrome local storage. This demo configuration can be exported to your disk to be archived or imported later or shared with another user. 

### Demo Extension Modes

The extension can be in three working states. The state applies per tab. These states are:

- **"OFF"**: both **Inspection** and **Injection** are ### red ###. The extension has no impact on the browsed site.

- **"Demo Edit"** mode: both **Inspection** and **Injection** are *green*. In this mode, you can add HotSpots (actions attached to selected elements) by using your mouse right-click and chosing the action to execute. Any {element, action} pair is highlighted with a green border line for you to identify what has been built.

- **"Demo Execution"** mode: **Injection** is *green* and **Inspection** is *red*. This mode does not have the highlighted elements that do trigger the click actions. The site looks completely normal, but the actions associated to the elements will trigger when you click on them. To help you remember where to click and in what order, the extension icon will show the action name when hovering on active elements. Also, a counter will increment on the extension icon to indicate that the action triggered when the element has been clicked.
