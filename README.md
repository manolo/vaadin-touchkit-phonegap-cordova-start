# Vaadin Cordova (Phonegap) Application

> A Parking Demo application for [Vaadin Framework](http://vaadin.com) + [Touchkit](http://vaadin.com/touchkit) + [Cordova](http://cordova.apache.org/)

## Usage

### Desktop

In your browser, open the file:

    /www/index.html

Or [install the Parking app](https://build.phonegap.com/apps/1061699/share) in your mobile.

[![QR](https://chart.googleapis.com/chart?chs=150x150&cht=qr&chl=http://build.phonegap.com/apps/1061699/install/)](https://build.phonegap.com/apps/1061699/share)

### PhoneGap Build

Login into the [Adobe Phonegap Build](https://build.phonegap.com) site and
create a new app with the following repository:

    https://github.com/manolo/vaadin-cordova-start.git

### Updating the Application

#### 1. Update the logo of the app

    $ cp your_app_icon.png  www/icon.png

#### 2. Update www/index.html

Change the page title:

        <title>Parking</title>

Change the url of your app:

        window.vaadinAppUrl = 'http://hupa.app.fi/parking'

#### 3. Update www/config.xml
   
Change the Id of your app and your version:

        id        = "com.vaadin.demo.parking"
        version   = "1.0.0"

Change The name and description:

        <name>Parking</name>
        <description>Vaadin Parking Demo.</description>

Update the phonegap-version in case:

        <preference name="phonegap-version" value="x.x.x" />

### Commit your changes

    $ git commit -am "Version x.x.x"

### Build your App in Adobe Phonegap Build

    Push on `Update code` button, then on the `Rebuild all` one

