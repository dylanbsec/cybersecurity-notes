# PortSwigger Learning Log

This file tracks my progress through the PortSwigger Web Security Academy, including topics studied, labs completed and practical skills developed using Burp Suite.

---

## Entry 001 - Burp Suite Basics

**Date:** 30 June 2026  
**Focus:** Intercepting HTTP requests using Burp Suite

### What I Learned

I learned how to use Burp Suite's built-in browser and Proxy tool to intercept HTTP requests between the browser and a web application.

I practised:

- Opening Burp Suite's embedded browser
- Enabling and disabling Intercept
- Capturing HTTP requests
- Viewing request methods, paths and headers
- Forwarding intercepted requests to the server

### Reflection

This helped me understand the basic workflow of using Burp Suite as an interception proxy. I can now capture a request before it reaches the server and inspect the information being sent by the browser.

---

## Entry 002 - Path Traversal

**Date:** 8 July 2026  
**Focus:** Understanding path traversal vulnerabilities

### What I Learned

Path traversal, also known as directory traversal, is a vulnerability that can allow an attacker to access files outside of the directory intended by a web application.

A vulnerable application may take user-controlled input, such as a filename, and append it to a directory path on the server.

For example:

```text
/loadImage?filename=218.png
