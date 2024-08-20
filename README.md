# podping-tiles

This is a single page website showing a constantly streaming view of podcasts which are updated.

Every time one of the podcasts on this page is updated, the hosting company announces that update by sending a "Podping". Podpings are sent out via the [Hive Blockchain](https://hive.io).

[Podping is explained here](https://podping.org)

This web page app displays the Podcast artwork for each show which updates. At the bottom you can find a link to the specific block on the Hive Blockchain which contains the message.




### Local copy of DHive installed
```
curl -L -o dhive.js https://unpkg.com/@hiveio/dhive@latest/dist/dhive.js
```