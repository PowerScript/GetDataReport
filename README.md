
## ABOUT
Script in PHP+JS for get information of target through a web application, use $_SERVER functions and JS functions for get information of our client.

# Plugin (WEBApps)
in some web applications need to collect information from the client to perform tasks with this plugin will be easier to work with the variables you need.

```
<?php
include(__DIR__."/GetdataReport.Plugin.php");
$data = new GetDataPlugin();
echo "<br>IP               ".$data->ip();
echo "<br>Operative System ".$data->os();
echo "<br>Browser          ".$data->browser();
echo "<br>Screen height    ".$data->height();
echo "<br>Screen width     ".$data->width();
echo "<br>Java enabled     ".$data->javaenabled();
echo "<br>Cookie enabled   ".$data->cookieenabled();
echo "<br>Language         ".$data->language();
echo "<br>Architecture     ".$data->architecture();
echo "<br>Device           ".$data->device();
echo "<br>Country          ".$data->geo('country');
echo "<br>Region           ".$data->geo('region');
echo "<br>Continent        ".$data->geo('continent');
echo "<br>City             ".$data->geo('city');
echo "<br>Logitude         ".$data->geo('logitude');
echo "<br>Latitude         ".$data->geo('latitude');
echo "<br>Currency         ".$data->geo('currency');
echo "<br>Provetor         ".$data->provetor();
echo "<br>Agent            ".$data->agent();
echo "<br>Referer          ".$data->referer();
echo "<br>Date             ".$data->getdate();
 ?>
```

