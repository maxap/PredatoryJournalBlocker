# Predatory Journal Blocker (PJB)
Predatory Journal Blocker is a practical browser extension for Chromium based browsers such as Google Chrome, Opera, Yandex, Vivaldi or Firefox

This plugin utilizes the work done by revengeday/axelspringerblocker

## Advanced installation guide for Chromium based browsers 
You can easily create your own version of this extension.  
All you need is time and some understanding of browser extension development.  
-  Read the developer documentation from your browser manufacturer
-  Create a manifest document (mostly a .json document)  
Here is an example for Google Chrome:
```sh
{
   "background": {
      "scripts": [ "" ]
   },
   "default_locale": "",
   "icons": {},
   "manifest_version": 2,
   "name": "Predatory Journal Blocker (PJB)",
   "offline_enabled": false,
   "options_page": "",
   "permissions": [ "webRequest", "webRequestBlocking", "http://*/*", "https://*/*" ],
   "update_url": "https://clients2.google.com/service/update2/crx",
   "version": ""
}
```
-  Validate the files and have fun blocking some websites
