# homeassistant_tesla_charging

## Description
I use this HomeAssistant automation script to set Tesla charge amps based on net solar production. 
This allows me to get the most value for my solar production under San Diego Gas & Electric's net metering plan.

## Requirements
* HomeAssistant
* HACS
* Tesla Wall Connector integrated into HomeAssistant
* Solar integration with HomeAssistant
* Tesla Custom Integration with API https://github.com/alandtse/tesla

## Setup
0. Install requirements.
1. Copy the script into a new HomeAssistant automation.
2. Update script to use your vehicle name and integrations.
3. Enable the automation script.
4. When you observe the script setting the amperage and it is within your available solar production, tell the car to charge in the app.
5. <img width="334" alt="image" src="https://user-images.githubusercontent.com/1264217/166574103-e8b72c11-9f63-46b8-a500-d001a5e13dbf.png">

## To Do
1. Remove reliance on Tesla Wall Connector once able to use Tesla API to GET the current charge amps.
2. Add rules to start charging automatically.

## Credits
I based this on what I learned here: https://community.home-assistant.io/t/optimizing-use-of-unused-solar-power-to-charge-a-tesla/340818
