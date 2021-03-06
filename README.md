![Sonos Controller Header](http://blog.vmichalak.com/wp-content/uploads/2017/01/SONOS_controller_header.png)

# sonos-controller
Java API for controlling [SONOS](http://www.sonos.com/) players.

[![Travis Build Shield](https://img.shields.io/travis/vmichalak/sonos-controller.svg)](https://travis-ci.org/vmichalak/sonos-controller)

## Basic Usage

Discovery all Sonos Devices on your network.

```java
List<SonosDevice> devices = SonosDiscovery.discover();
```


Connect to a known Sonos and pause currently playing music.

```java
SonosDevice sonos = new SonosDevice("10.0.0.102");
sonos.pause();
```

## Android Developer 

Add this line to your gradle file.
```
compile group: 'org.apache.httpcomponents' , name: 'httpclient-android' , version: '4.3.5.1'
```

## To-Do

[Link to the Trello](https://trello.com/b/0r87xvWy/sonos-controller)

## Contributors

The current lead maintainer is [Valentin Michalak] (https://github.com/vmichalak) [(twitter)](https://twitter.com/valmichalak)
Feel free to participate !

## Special Thanks

Special Thanks to [rahims](https://github.com/rahims) for is work on Sonos API ! 

## Licence

Released under the [MIT license.](LICENCE)
