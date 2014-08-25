# Vaadin Cordova (Phonegap) Application

> A Demo application for Vaadin Framework + Cordova

## Usage

### Desktop

In your browser, open the file:

    /www/index.html

### PhoneGap Build

Create a new app with the following repository:

    https://github.com/manolo/vaadin-cordova-start.git

### Updating the Application

#### 1. Update the logo of your app

    It is placed at www/icon.png

#### 2. Update www/index.html

   Change the tittle for the page `<title>Parking</title>`
   Set the url of your app `window.vaadinAppUrl = 'http://hupa.app.fi/parking'`

#### 3. Update www/config.xml
   
    Change the Id of your app and your version:
        `id        = "com.vaadin.demo.parking"`
        `version   = "1.0.0"`

    Change The name and description:
        `<name>Parking</name>`
        `<description>Vaadin Parking Demo.</description>`

    Update the phonegap-version in case:
        `<preference name="phonegap-version" value="x.x.x" />`

### Commit your changes

    `$ git commit -am "Version x.x.x"`

### Build your App in Phonegap Build

