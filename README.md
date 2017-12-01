# FreshRSS - "Dilbert Daily Strip" extension

This FreshRSS extension allows you to directly enjoy the Dilberts daily strip within your FreshRSS installation.

To use it, upload the ```xExtension-Dilbert``` directory to the FreshRSS `./extensions` directory on your server and enable it on the extension panel in FreshRSS.

## The Dilbert feed itself

This extension supports both feed addresses:

- the old one at http://feeds.feedburner.com/DilbertDailyStrip
- and the new one at http://feed.dilbert.com/dilbert/daily_strip 

But this extension will ONLY work on new added feed items as it manipulates them while inserting into the  

## Fair use

Please note that they deactivated the images in their RSS feed years ago, I suspect mainly to get more visitors to their website.
So please play fair and visit them on a daily base instead of using this extension ;-) as we all want to keep their feed alive!

## Requirements

This FreshRSS extension uses the PHP extension "xml" and their classes DOMDocument and DOMXpath.

If it doesn't work for you, make sure that you have the PHP xml module installed and loaded. 
You can read more about it at http://php.net/manual/en/dom.setup.php


## Installation

The first step is to put the extension into your FreshRSS extension directory:
```
cd /var/www/FreshRSS/extensions/
wget https://github.com/kevinpapst/freshrss-dilbert/archive/master.zip
unzip master.zip
mv freshrss-youtube-master/xExtension-Dilbert .
rm -rf freshrss-dilbert-master/
```

Then switch to your browser https://localhost/FreshRSS/p/i/?c=extension and activate it.

## About FreshRSS
[FreshRSS](https://freshrss.org/) is a great self-hosted RSS Reader written in PHP, which is can also be found here at [GitHub](https://github.com/FreshRSS/FreshRSS).

More extensions can be found at [FreshRSS/Extensions](https://github.com/FreshRSS/Extensions).

## Changelog

0.1: First release
