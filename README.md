Various automations for Home Assistant run on a Pi4 with HAOS and several standard integrations as well as HACS integrations. Examples are generic, feel free to use as inspiration for your own HA projects.

lowSensorBattery.yaml
  - Monitors the battery level of several sensors then makes an annoucment on several media players (speakers) when one or several of the battery levels are low.

CloseTheShadesWhenItsHot.yaml
  - The afternoon sun heats up my living room so this automation monitors the time, sun shine and temp to determine if the living room shades should close.
  - Uses the Open-Meteo integration to determine if the sun is out and the temp.

PackageAtTheFrontDoor.yaml
  - If a camera detects a package then this makes an annoucment on several speakers around the house.
