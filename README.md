# TESTING Application

> TESTING APP PLEASE DON'T USE! PLEASE USE FOLLOWING: https://github.com/phonegap/phonegap-start
> TEST APP BITTE NICHT BENUTZEN. BITTE FOLGENDES NUTZEN: https://github.com/phonegap/phonegap-start
> PUBLISHING IOS https://www.wenz.io/ApplicationLoader
> GEN https://build.phonegap.com/apps/
> IMG http://pgicons.abiro.com/
> TEST https://app.testobject.com/#/

## Usage

### PhoneGap Build

Create a new app with the following repository:

    https://github.com/refda/briefklickios.git

## Contributors

### Updating the Application

The application is based on the [Apache Cordova Hello World][cordova-app] app.

#### 1. Update the Source

    cp cordova-app-hello-world/www www/

__Do not replace `www/config.xml`.__

__Do not replace `www/img/logo.png`.__

#### 2. Update index.html

Replace `<h1>Apache Cordova</h1>` with `<h1>PhoneGap</h1>`.

#### 3. Update PhoneGap Version

    <preference name="phonegap-version" value="x.x.x" />

#### 4. Commit

    $ git commit -am "Version x.x.x"

#### 5. Tag

    $ git tag x.x.x

[phonegap-cli-url]: http://github.com/phonegap/phonegap-cli
[cordova-app]: http://github.com/apache/cordova-app-hello-world
[bithound-img]: https://www.bithound.io/github/phonegap/phonegap-start/badges/score.svg
[bithound-url]: https://www.bithound.io/github/phonegap/phonegap-start

