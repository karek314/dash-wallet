<b>This is fork of android dash-wallet. This version allow to retrieve lost spending pin in case it's numeric. In order to use - Go to Settings > Safety > Change Spending Pin

As old pin set 0000 for 4 charactery recovery or 000000 for 6 character recovery and so on, in case you want remove pin completely, PIN(new) field have to be left blank. Current pin and iteration will be displayed, if any combination match, old pin will be removed/changed and dialog will disappear. Please also remember to set device to never go sleep. I have also included precompiled apk.

Im not responsible for illegal usage of this software, use on your own risk. Software has been made for educational purposes.
</b>




Welcome to _Dash Wallet_, a standalone Dash payment app for your Android device!

This project contains several sub-projects:

 * __wallet__:
     The Android app itself. This is probably what you're searching for.
 * __market__:
     App description and promo material for the Google Play app store.
 * __integration-android__:
     A tiny library for integrating Dash payments into your own Android app
     (e.g. donations, in-app purchases).
 * __sample-integration-android__:
     A minimal example app to demonstrate integration of digital payments into
     your Android app.

You can build all sub-projects at once using Gradle:

`gradle clean build -x test`

Full Guide for building the APK:

`$ git clone https://github.com/HashEngineering/darkcoinj.git `

`$ cd darkcoinj`

`$ git checkout release-0.13`

`$ mvn clean install -DskipTests`

`$ cd ..`

`$ git clone https://github.com/HashEngineering/darkcoin-wallet.git `

`$ cd darkcoin-wallet`

`$ git checkout release-4`

`$ gradle clean build -x test`


