JavaScriptContainer
===================

Container for JavaScript components to be used inside Eclipse

## Idea

Eclipse is great, but Java is different platform than Node.js.
While Eclipse Runtime has a lot of architectural solution and features, it is huge to develop quickly and understand.

There are Node.js based IDEs that run in a browser, like Scripted.

It is possible to have Eclipse component like Editors, that are implemented using WebView.
That is browser widget, that render web-based implementation.
Requirement is that every such used JS component has interface to be called from Java,
and some way for JavaScript to call Java code. See Apache PhoneGap.

## First step

First step would be light Eclipse component JSContainer, that just uses WebView.
For whole IDE to work all these component hierarchies should have shared property
base_address, that is address of web server. In this way, there can be easy switch
from locally running web-server to some LAN or cloud server.

## Questions

How to create light Eclipse RCP container for JavaScript, and HTML5+JavaScript?
 Are there ready-to-use libraries and frameworks?
