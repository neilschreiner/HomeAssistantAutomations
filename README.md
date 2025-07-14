Various automations for Home Assistant run on a Pi4 with HAOS and several standard integrations as well as HACS integrations. Examples are generic, feel free to use as inspiration for your own HA projects.

Description of each: 

<a href="https://github.com/neilschreiner/HomeAssistantAutomations/blob/main/lowSensorBattery.yaml">lowSensorBattery.yaml</a>
  - Monitors the battery level of several sensors then makes an annoucment on several media players (speakers) when one or several of the battery levels are low.

<a href="https://github.com/neilschreiner/HomeAssistantAutomations/blob/main/CloseTheShadesWhenItsHot.yaml">CloseTheShadesWhenItsHot.yaml</a>
  - The afternoon sun heats up my living room so this automation monitors the time, sun shine and temp to determine if the living room shades should close.
  - Uses the Open-Meteo integration to determine if the sun is out and the temp.

<a href="https://github.com/neilschreiner/HomeAssistantAutomations/blob/main/PackageAtTheFrontDoor.yaml">PackageAtTheFrontDoor.yaml</a>
  - If a camera detects a package then this makes an annoucment on several speakers around the house.

<a href="https://github.com/neilschreiner/HomeAssistantAutomations/blob/main/5MinsBeforeSunrise.yaml">5MinsBeforeSunrise.yaml</a>
  - Using Lat/Long settings in Home Assistant, turn off any outdoor lights 5 minutes before sunrise.
