# OfflineWebsite
Helpful functions for enabling caching websites with Service Worker. 

# How to use

Simply copy paste the function(s) you wish to use and call it.


# Include service worker in your JS file

```
if ("serviceWorker" in navigator) {
    navigator.serviceWorker.register("/sw.js")
    console.log("Service Worker allowed");
}
```
