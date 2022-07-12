Skimmer Scanner: A Gas Pump Skimmer Detection App by SparkX
===========================================================

![A bluetooth based gas pump skimmer](https://cdn.sparkfun.com/assets/learn_tutorials/6/9/4/Skimmer-IC_labels.jpg)

[*The inside of a bluetooth gas pump skimmer*](https://learn.sparkfun.com/tutorials/gas-pump-skimmers)

The Skimmer Scanner is a free, open source app that detects common bluetooth based credit card skimmers predominantly found in gas pumps. The app scans for available bluetooth connections looking for a device with title **HC-05**. If found, the app will attempt to connect using the default password of 1234. Once connected, the letter 'P' will be sent. If a response of 'M' then there is a very high likelihood there is a skimmer in the bluetooth range of your phone (5 to 15 feet).

The app *does not* obtain or download data from a given skimmer nor does it report any information to local authorities.

Skimmer Scanner is free, open source, and currently available for Android available [here](https://play.google.com/store/apps/details?id=skimmerscammer.skimmerscammer). Please help us make it better! We are not mobile app developers and can use all the help we can get. We very much need an iOS version. Thank you!

Written by Nick Poole. Skimmer teardown and research by Nathan Seidle and Rob Reynolds at [SparkFun](http://www.sparkfun.com).

Repository Contents
-------------------

* **/src** - Source files

Documentation
--------------

* **[Gas Pump Skimmers Tutorial](https://learn.sparkfun.com/tutorials/gas-pump-skimmers)** - Read all about how these skimmers work.

Additional Information & Resources
----------------------------------
* **[Article on Bluetooth Skimmers by Signils (Google Cache)](https://webcache.googleusercontent.com/search?q=cache:cEuOrbw0wOgJ:https://www.signils.com/bluetooth-credit-card-skimmers/)** - More skimmer IDs (HC-05, HC-06, HC-08, FREE2MOVE)
* **[Article on a Skimmer Detector by Cameron Coward at hackster.io](https://www.hackster.io/news/protect-your-credit-card-by-building-a-skimmer-detector-with-a-raspberry-pi-f670f94ffcb2)** - Another known skimmer ID (HC-03)
* **[Article clarifying the difference between GPS Tracker & Credit Card Skimmer by Krebs on Security](https://krebsonsecurity.com/2019/02/new-breed-of-fuel-pump-skimmer-uses-sms-and-bluetooth/)** - Another ID (FCD_1608)

License Information
-------------------

This product is _**open source**_! 

Various bits of the code have different licenses applied. Anything SparkFun wrote is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
