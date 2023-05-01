# PLANT-MONITOR
This project details the development of an IoT system designed to monitor the health of a house plant and transmit data - temperature, humidity level, and soil moisture level - to an MQTT server. This data will help an owner determine their plant's needs and help them keep their plant in good health.

This project is the final submission for CASA0014 (Connected Environments) in the MSc in Connected Environments at UCL's Bartlett Centre for Advanced Spatial Analysis.

## Project Directory
- [Features](#features)
- [Built With](#built-with)
- [My Plant](#my-plant)
- [License](#license)

## Features
- Temperature detection
- Humidity detection
- Soil moisture level detection
- Publish of data to MQTT

## Built With
- Standard Feather Huzzah ESP8266
- Custom CASA Huzzah ESP8266
- DHT22 Temperature/Humidity Sensor
- 10k Resistor x2
- 1k Resistor x2
- 220 Resistor x2
- Transistor
- 30cm Length of Wire x2
- 6cm Hardware Nail x2
- Soldering Machine
- Raspberry Pi (with SD card, SD card reader + case for aesthetics)
- USB Cable
- Potted Plant

## My Plant
**Begonia Maculata**

Also known as the Polka dot Begonia, or Spotted Begonia, this plant can be identified by its large angel wing-shaped leaves patterned with
polka dots on top and a deep purple-red on the bottom side.

<img src="https://user-images.githubusercontent.com/33913141/235490534-1ac8a492-f45f-4fe0-ba9d-630bc8cc0d6c.jpg" style="width:350px"/>

**Care Instructions**
- A mixture of peat and another substrate forms a good growing mixture
- Needs bright, indirect sunlight - must be kept out of direct afternoon sun
- Water regularly, let top soil dry out between watering, let excess water drain from pot - must keep soil somewhat moist
- Humidity needs to be around 70% during the daytime and 90% at night
- Thrives in temperatures between 18°C and 30°C and can tolerate temperatures slightly below 18°C
- Benefits from being fertilised regularly 2 or 3 times a month

**Things to Keep in Mind**
- Different plants may require different kinds of care

## License
This project is licensed under the MIT License.

<!--

# Things That Made This Project Easier for Me
**Using Atom IDE + Github Desktop Git Client**

Both Atom and GitHub Desktop were developed by Github, and seem to link together very seamlessly. Although this is my first time using Atom, a git client,
and pushing my work to Github in a few years, I believe the way these softwares work together made the learning process a lot easier for me

**Writing Code Out Manually**

Although this code has been pulled from a project of the same name by Prof. Duncan Smith, opting to rewrite all of the code by hand helped me to better understand
how it works

**Commenting Everything**

I don't have an extensive background in IoT or computer science in general, so opting to add comments to everything possible has been a huge help
in allowing me to understand the code better.

# What I Am Struggling With
- I am having difficulty understanding MQTT and the code related to connecting to the wifi, MQTT server, etc.
- Everything after step 10 - setting up RPI as a gateway
- What is the arduino secrets file?

# Things I Want to Improve for This Project
- Add in a light sensor to detect how much light the plant is getting
- Where is the best placement for the moisture sensor?
- Mark which nail is positive/negative

# What I Want to Improve for My Next Project
- Better and more consistent documentation for each step
- Build the read.me throughout the project
- Take more pictures
- Read ahead so I can spend more time on things I'm struggling with

# Current To Do List
- Install Influx DB on RPI
- Collect and store soil data
- Visualize data on Grafana
- View soil data
- Add pictures to readme.md
- Add more comments to code after understanding what the code does
- Add step-by-step process to the readme.md (include steps and test from workshops)
- Reorganize project into a UCL Github repository

 -->
