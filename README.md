# Wyoming Satellite Scripts

Scripts to help install and manage [Wyoming remote voice satellites](https://github.com/rhasspy/wyoming-satellite).
* Install wyoming-satellite, wyoming-openwakewords, Seeed Studio 64bit speaker drivers and home assistant wakeword collection in one command
* Includes defining, enabling and starting systemd services.
* Provided menu functions that will allow you to:
  - Select your wake word or show your installed wake word
  - Refresh wakeword list from github source  
  - Edit and restart all the associated systemd services  
 * Initiate the menu with the ```m``` or ```menu``` command  


To run the full Install script, copy this command and run on your device  
```bash
bash -c "$(wget -qLO - https://github.com/dkedinger/wyoming-satellite-scripts/raw/release/scripts/install.sh)"
```

![menu](assets/menu.png)  

![menu](assets/select-wakeword.png)  
## Reference Links
* Forked from great work of [dreed47s project here] (https://github.com/dreed47/wyoming-satellite-scripts) with an edit to use [SeeedStudio Speaker Driver for 64bit ARM] (https://github.com/respeaker/seeed-voicecard)
* Works with [Home Assistant](https://www.home-assistant.io/integrations/wyoming)
* Local wake word detection using [Wyoming services](https://github.com/rhasspy/wyoming#wyoming-projects)
* [wyoming satellite git repo](https://github.com/rhasspy/wyoming-satellite)
* [wyoming openwakeword git repo](https://github.com/rhasspy/wyoming-openwakeword)
* [home assistant wakewords collection git repo](https://github.com/fwartner/home-assistant-wakewords-collection) 
* [blog post - Setup a Raspberry Pi Zero 2 W as a Wyoming Satellite](https://www.slacker-labs.com/setup-a-raspberry-pi-zero-2-w-as-a-wyoming-satellite/)
* [YouTube - Build your own Local Echo](https://www.youtube.com/watch?v=Bd9qlR0mPB0)

## IMPORTANT
These scripts assume your satellite is using a [Raspberry Pi Zero 2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/) and a [ReSpeaker 2Mic HAT](https://wiki.keyestudio.com/Ks0314_keyestudio_ReSpeaker_2-Mic_Pi_HAT_V1.0).  If you're using different hardware then you may need to modify these scripts to get them to work.


