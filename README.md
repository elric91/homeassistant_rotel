# Deprecated
This repository is deprecated, but development continues @ https://github.com/matthijs-oosterhoff/homeassistant_rotel



> # Rotel component for Home Assistant
> Custom components for Home Assistant

> A media_player platform that can be used through HASS to :
> - turn on and off the amplifier
> - adjust volume
> - change source
> - check status

> To install, copy rotel.py in your hass configuration folder, under 'custom\_components/media\_player'
> i.e. /home/user/.homeassistant/custom\_components/media\_player/rotel.py

> Example minimal config (in configuration.yaml, dummy IP to be updated) :
> ```
> media_player:
>   - platform: roteltcp
>     host: 192.168.1.12
> ```

