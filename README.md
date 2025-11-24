HomeAssistant Blueprints
===
Here are some [Home Assistant](https://www.home-assistant.io/) blueprints. 

# Install
Go to your Home Assistant configuration folder, under `/blueprints/automation`
```sh
git clone https://github.com/Fgdou/homeassistant-blueprints
```

# Lights Requirements
The lights.yaml script uses multiple hard set values you need to have created before :

|Name|Description|
|---|---|
|`input_boolean.sleep`|Dim the lights when sleeping|
|`sensor.luminance_illuminance`|Make decision based on the daylight value|
|`input_boolean.lights_off`|Always dim the lights|
