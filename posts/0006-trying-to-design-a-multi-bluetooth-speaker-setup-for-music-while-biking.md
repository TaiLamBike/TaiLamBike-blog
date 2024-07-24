# 6: Trying to design a multi-Bluetooth speaker setup for music while biking

_Originally collected on July 6, 2024_

I have been trying to research how to play music via Bluetooth with only one audio input and 2 or
more (preferably the latter) Bluetooth speakers in a manner that is independent of Bluetooth speaker
OEM.

I didn't make that much progress, but basically here are my notes<!--more-->

Basically, Bluetooth speakers need to have Bluetooth protocol version 5.2 or later, which should be
capable of Auaracast.  Most new-ish phones will most likely this Bluetooth protocol, but the
speakers are another matter.  So, basically the latest speakers from 2023 and later tend to have
Auracast.

I've been considering how to play music while via Bluetooth in a way that lets multiple bikers with
speakers of different speakers to play the same music, in the case of playing an official ride
playlist.  (The audio source would hypothetically not matter, as it could be either a local music
collection or a cloud app, such as Spotify.)  Since I can't make any more progress now, I'll have to
shelf this effort for now.

These are my resources:

* Auracast in [Bluetooth 5.2](https://en.wikipedia.org/wiki/Bluetooth#Bluetooth_5.2)
* Reddit threads
    * [Thread](https://old.reddit.com/r/GooglePixel/comments/ugnmvu/dual_audio_for_bluetooth_for_pixel_6/) asking about the Pixel Buds 2
* Hypothetically possible, according to Android source [documentation](https://source.android.com/docs/core/audio/combined-audio-routing)
    * However, the closest feature seems to only be available to Samsung's spin of Android on its stock smartphone OS
        * This is a nonstandard system option on Samsung's version of the OEM Android OS, so this feature can't be contributed upstream to any other Android devices
    * This still only lets 1 smartphone control 2 Bluetooth speakers of different brands
        * 2 speakers seems to be the max
    * I'm seeking a solution for 3 or more that is independent of speaker and/or smartphone OEM

## Also for outdoor/indoor use
I also tried looking up Bluetooth transmitters, but this didn't really seem to lead anywhere.

* It seems that even Bluetooth transmitters still only transmit to 2 devices max?
    * NYT's Wirecutter Bluetooth transmitter [list](https://www.nytimes.com/wirecutter/reviews/best-bluetooth-transmitters/)
    * Home stereo version of the [list](https://www.nytimes.com/wirecutter/reviews/best-bluetooth-audio-receiver-for-your-home-stereo-or-speakers/)

## Miscellaneous
* 3D printed staple and flag tool from Deviant Ollum on [GitHub](https://github.com/deviantollam/StapleStomper)
    * This would be helpful, if we need to run an aux cable on grass
* An [example](https://www.theramppeople.co.uk/cable-protectors) of a place to purchase more traditional cable covers and protectors for temporary outdoor usage

