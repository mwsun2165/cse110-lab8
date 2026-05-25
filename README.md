# Lab8-Starter

Names: Michael Sun

Link to site: [https://mwsun2165.github.io/cse110-lab8/](https://mwsun2165.github.io/cse110-lab8/)

1. How are graceful degradation and service workers related?

Service workers help a web app keep working when ideal conditions (fast network connection) aren't available. Instead of making an app fully dependent on the internet, a service worker can intercept network requests and serve cached files/other data from the browser to allow the page to still load offline or under slow internet conditions. This fits graceful degradation because the app begins with full online functionality but still provides a useable experience when network access fails.

PWA Screenshot: ![pwa.png](pwa.png)