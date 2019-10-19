# Pi-hole Droid

![App Logo](www/assets/mipmap-hdpi/ic_launcher.png?raw=true)

Pi-hole Droid is an *unofficial* client that connects to your [Pi-hole](https://github.com/pi-hole/pi-hole) to show charts and statistics.

It requires the new *Pi-hole 3.0 FTL* (released on 2 May 2017). Please update your Pi-hole!

This is the repository of the Pi-hole Droid's opensource application available on [Google Play Store](https://play.google.com/store/apps/details?id=friimaind.piholedroid).

**What is Pi-hole?**

> Pi-hole is the multi-platform, network-wide ad blocker which blocks ads for all your devices without the need to install client-side software.

Pi-hole Droid makes use of [Pi-hole API](https://github.com/pi-hole/AdminLTE) to obtain all the data. The credentials is **locally stored** on your device through localStorage.

## Download

<a href="#/"><img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" height="60"></a>

*Please note:* Google Play Store is temporary unavailable, in the meantime you can **get the latest APK** directly from [here](https://github.com/friimaind/pi-hole-droid/releases/latest) or [F-Droid repository](https://f-droid.org/en/packages/friimaind.piholedroid/)

## Screenshots
![Homepage](screenshots/home.png?raw=true "Homepage") 
![Menu](screenshots/menu.png?raw=true "Menu") 

![Charts](screenshots/charts.png?raw=true "Charts")
![Settings](screenshots/settings.png?raw=true "Settings")

![Toggle On](screenshots/toggle_on.png?raw=true "Toggle On")
![Toggle Off](screenshots/toggle_off.png?raw=true "Toggle Off")

![Home Landscape](screenshots/home-landscape.png?raw=true "Home Landscape")

![Landscape](screenshots/landscape.png?raw=true "Landscape")

![Landscape2](screenshots/landscape-2.png?raw=true "Landscape2")

![Query Log](screenshots/query-log.png?raw=true "Query Log")

## Built With

* [Apache Cordova](https://cordova.apache.org/)
* [MDL Material Design Lite](https://getmdl.io)
* [jQuery](https://jquery.com)
* [Chartist JS](https://gionkunz.github.io/chartist-js)
* [DataTables](https://datatables.net)
* [Hammer.js](http://hammerjs.github.io)
* [BarcodeScanner](https://github.com/phonegap/phonegap-plugin-barcodescanner)

## Upcoming releases
I'm working on these tasks for the next releases:

* Improvements on UI (loading icons on table views, better UI on Query Log page primarily)
* Improvements on landscape view (better use of space)
* Query Log: highlight blocked queries
* Auto update toggle on Query Log's page
* Dark theme

Do you have a feature request? Please, [write an issue](https://github.com/friimaind/pi-hole-droid/issues).

## Oh no! I found a bug!

Please, [write an issue](https://github.com/friimaind/pi-hole-droid/issues).

## Authors

* **Massimiliano Monaro** - [blog.friimaind.it](https://blog.friimaind.it)

## Contributing

If you want to contribute to this project and make it better, your help is very welcome! :)

## App permissions

The app could scan the QR Code of your Pi-hole to retrieve the token. This function uses the camera of your smartphone so this is the reason why the app needs the **camera permission**.

## License

This project is licensed under the terms of the [GNU General Public License v2.0](LICENSE).
