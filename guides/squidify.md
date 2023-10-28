---
title: Squidify
description: Stream Anime, Video Game, Movie & TV Soundtracks on Squidify. Access from any device, compatible with Subsonic/Airsonic API. Enjoy your favorite music!
---
# Squidify
Squidify is a public music streaming service that offers a vast collection of Anime, Video Game, Movie & TV Soundtracks. You listen to your music collection from any browser or mobile device. Squidify is compatible with the Subsonic/Airsonic API, allowing you to use a wide range of third-party mobile apps to access your music.
<br>

## Clients

Squidify is based on Navidrome which has its own set of third-party Apps besides its own [Web UI](https://www.squidify.org/). It should be compatible with all Subsonic clients. The following clients are tested and confirmed to work properly:

:::tabs
== Android

- [Subtracks](https://github.com/austinried/subtracks#readme)
- [substreamer](https://substreamerapp.com/)
- [Ultrasonic](https://ultrasonic.gitlab.io/)
- [DSub](https://play.google.com/store/apps/details?id=github.daneren2005.dsub) <Badge type="info" text="Paid" />
- [Symfonium](https://symfonium.app/) <Badge type="info" text="Paid" />

== iOS

- [play:Sub](http://michaelsapps.dk/playsubapp/)
- [substreamer](https://substreamerapp.com/)
- [Amperfy](https://github.com/BLeeEZ/amperfy#readme)
- [iSub](https://isub.app)


== Desktop

- [Sonixd](https://github.com/jeffvli/sonixd) <Badge type="info" text="Windows" /><Badge type="info" text="Linux" /><Badge type="info" text="MacOS" />
- [Sublime Music](https://sublimemusic.app/) <Badge type="info" text="Linux" />
- [Supersonic](https://github.com/dweymouth/supersonic) <Badge type="info" text="Windows" /><Badge type="info" text="Linux" /><Badge type="info" text="MacOS" />
- [Submariner](https://submarinerapp.com/) <Badge type="info" text="MacOS" />
- **CLI**
    - [Jellycli](https://github.com/tryffel/jellycli#readme) <Badge type="info" text="Windows" /><Badge type="info" text="Linux" />
    - [STMP](https://github.com/wildeyedskies/stmp#readme) <Badge type="info" text="Linux" /><Badge type="info" text="MacOS" />

== Others

- **Connected Speakers**
  - [bonob](https://github.com/simojenki/bonob#readme) <Badge type="info" text="Sonos" />
  - [AskSonic](https://github.com/srichter/asksonic#readme) <Badge type="info" text="Alexa" />
- [Subsonic Kodi Plugin](https://github.com/warwickh/plugin.audio.subsonic#readme)
- [Navidrome Kodi Plugin](https://github.com/BobHasNoSoul/plugin.audio.navidrome#readme)
- [HTTPDirFS](https://github.com/fangfufu/httpdirfs#readme)
- [upmpdcli](https://www.lesbonscomptes.com/upmpdcli/index.html)
    - Expose Navidrome as a UPnP/DLNA media library. See the <Badge type="tip" text="discussion" link="https://github.com/navidrome/navidrome/discussions/2324" />

:::

>For more options, look at the [list of clients](https://airsonic.github.io/docs/apps/) maintained by the Airsonic project.

## Credentials

Connecting to Squidify is very easy, just login with the following credentials:

- Server Address: `https://www.squidify.org`
- Port (If needed): `443`
- Username: `Guest`
- Password: `Guest`
- Force Clear Text Password<sup>1</sup>: Disabled / Off

> 1. We recommend sending the Password as Token + Salt. Not all Clients have this option though.


:::tip Query
To request additional soundtracks or inquire about Squidify, join [**SquidBoard**](https://www.squid-board.org/).
:::



