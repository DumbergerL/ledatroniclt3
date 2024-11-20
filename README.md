This custom component allows integrating LEDATronic LT3 Wifi devices into Homeassistant.

There is some german stuff in the code, please open a github issue if you need translations.


## Manual installation

1. Copy source of this repo `custom_components/ledatroniclt3/` to your homeassistant installation at `/homeassistant/custom_components/ledatroniclt3`.

2. Activate component manual in `homeassistant/configuration.yml`

```
sensor:
  - platform: ledatroniclt3
    host: "192.168.178.115"
```