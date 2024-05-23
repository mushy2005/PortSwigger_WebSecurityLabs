# CTF Challenge - Reflected XSS into HTML context with nothing encoded
## Introduction
- The lab contains a simple reflected XSS vulnerability in the search functionality. To solve the lab, we need to perform a XSS attack that calls the `alert` function

## Steps
1. This is the website we're dealing with: <br>
![Website](./images/reflected-xss.png "Website") <br>
2. This is quite simple, as we only have to inject some JS code, which is the following: `<script>alert(1)</script>`. After injecting that, the lab is solved.

