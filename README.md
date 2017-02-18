# ra2-dom-xss-scanner
Automatically exported from code.google.com/p/ra2-dom-xss-scanner



Ra.2 - Blackbox DOM XSS Scanner

Introduction

Ra.2: A DOM-based XSS scanner, for the rest of us!

Ra.2 - Blackbox DOM-based XSS Scanner is our approach towards finding a solution to the problem of detecting DOM-based Cross-Site Scripting vulnerabilities in Web-Application automatically, effectively and fast. Ra.2 is basically a lighweight Mozilla Firefox Add-on that uses a very simple yet effective and unique approach to detect most DOM-based XSS vulnerabilities, if not all. Being a browser-add on it is a session-aware tool which can scan a web-application that requires authentication. Ra.2 uses custom collected list of XSS vectors which has been heavily modified to be compatible with its scanning technology. The add-on also implements basic browser intrumentation to simulate a human interaction to trigger some hard to detect DOM-based XSS conditions.

Features

False positive free by design: Vulnerable URLs are saved in DB, if and only if, our payload is executed successfully by the browser. Hence marked exploitable. If isn't false-positive, it's a bug! Report us :-)

Large collection of injection vectors, includes “modified” R’Snake’s vectors as well.

Supports transforming Unicode characters for testing content aware application.

Automatically handles JavaScript obfuscation/compression, as it relies on native interpreter.

Fast and light-weight.

Pretty easy learning curve. Point-n-Click.

Basic browser automation support: Simulates some of the browser events that require human interaction to trigger the XSS condition. Example:```html Click here

Unknown end tag for </a>

html ``` and similar scenarios.

Centralized reporting: Suitable for enterprise standard multi-user environment.

Ra.2 Architecture

Goodness of Automation + Goodness Blackbox Fuzzing = Win
