# Hubiquitus Android
Hubiquitus client API for Android. Should be used with a hNode.
Currently allows to do pubsub with an xmpp server. More information on [hubiquitus](www.hubiquitus.com)

## Third party libraries
This project currently relies on
* Socket.io-java-client : Socket io. Using this [fork](https://github.com/Gottox/socket.io-java-client)
* PhoneGap : PhoneGap for android. See [here](http://phonegap.com/) for more informations

## How to use it

### As an Android project
Coming soon (with first stable release)

### As a PhoneGap Plugin
Coming soon (with first stable release)

## How to test it

#### 1) clone git project

    git clone git://github.com/hubiquitus/hubiquitus-android.git
    
#### 2) Import examples
For android: 

You will find hAPI-android-v0.5.0.jar in the hAPI-android/target.
You can import the file jar directly to your project.

For android PhoneGap:
* Copy the directory hapiPhoneGapPlusin to your project. Add the link source to the directory.
* Copy the directory examples/PhoneGapTest/assets/www/js/HClientPhoneGap to yourproject/assets/www/


#### 3) config AndroidManifest.xml
Add "android:name="org.hubiquitus.hapi.util.MyApplication" in "Application".

## Licensing
Copyright (c) Novedia Group 2012.

This file is part of Hubiquitus.

Hubiquitus is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Hubiquitus is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Hubiquitus.  If not, see <http://www.gnu.org/licenses/>.

