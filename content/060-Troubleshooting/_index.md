---
title: "Troubleshooting"
chapter: true
weight: 60
---

![Title](/images/Troubl.PNG)


### Overcome CSP issues
Some websites include CSP (Content Security Policy) directives that block the loading of external components, like the Demo Extension.
This translate into Chrome console with error messages like:
"Refused to connect to 'https://api.mypurecloud.com/api/v2/webchat/guest/conversations' because it violates the following Content Security Policy directive:..." 

To workaround this issue, you can install the ["Always Disable Content-Security-Policy" Extension from Chrome store](https://chrome.google.com/webstore/detail/always-disable-content-se/ffelghdomoehpceihalcnbmnodohkibj).

Once installed, enable that extension by clicking on the ![Icon](/images/file_1632789316819_2021-09-28_10-34-44.png) It will turn red when enabled. When enabled, the Genesys Demo Extension should no longer be affected by CSP directives.

>Caution: Enabling this extension lowers the security level that website owners enforce. Our recommendation is to enable the "CSP remover" extension only during your demo.
