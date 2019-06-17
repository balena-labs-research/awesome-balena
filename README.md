# Awesome balena [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of helpful balena resources.

## Table of Content

* [Boilerplates &amp; Examples](#boilerplates--examples)
* [Software Development Kit](#software-development-kit)
* [Fullfledged Projects](#fullfledged-projects)
* [Blogposts](#blogposts)
  * [Projects And Posts](#community-projects-and-posts)
* [Balena Platform Components](#balena-platform-components)
* [Other projects by the balena team](#other-projects-by-the-balena-team)
* [Contributing](#contributing)
* [License](#license)

## Boilerplates & Examples

Boilerplate projects for understanding and getting started with different balena features.

* [Idling](https://github.com/balena-io-projects/balena-idling), likely the most minimal balena project, for the most barebones & quickest way to get started.
* [Simple Server Python](https://github.com/balena-io-projects/simple-server-python), a simple Hello World server with Python Flask.
* [Simple Server Node.js](https://github.com/balena-io-projects/simple-server-node), a simple express server with balena.
* [Rust Hello World](https://github.com/balena-io-projects/balena-rust-hello-world), example of how to deploy Rust code on a balena supported device.
* [C++ Hello World](https://github.com/balena-io-projects/balena-cpp-hello-world), example of how to deploy C++ code on a balena supported device.
* [Golang Hello World](https://github.com/balena-io-projects/balena-go-hello-world), starting project to deploy a Golang project on balena supported devices.
* [Timezone](https://github.com/balena-io-playground/balena-timezone), example to set the timezone on a balena device.
* [Balena WiFi Connect](https://github.com/balena-io/wifi-connect), an app skeleton/addon to allow WiFi configuration to be set via a captive portal, besides your normal application.
* [Balena Sense-hat Python Starter](https://github.com/balena-io-playground/balena-sense-hat-python-starter), a starter project with Python3 and Sense-HAT library ready to go.
* [Balena Sense-hat Node.js Starter](https://github.com/balena-io-playground/node-sense-hat), a starter project with Node.js and Sense-HAT library ready to go.

## Software Development Kit

Collection of Software Development Kits to interact with the balena platform programically:

* [Node.js SDK](https://github.com/balena-io/balena-sdk).
* [Python SDK](https://github.com/balena-io/balena-sdk-python).
* [Go SDK](https://github.com/gernest/resingo) (unofficial).

## Fullfledged Projects

Full projects built on top of balena:

* [Boombeastic](https://github.com/balena-io-projects/boombeastic), a Raspberry Pi based smart connected speaker based on Mopidy.
* [Balena Cam](https://github.com/balena-io-playground/balena-cam), share your balena device's camera feed with multiple peers.
* [resin-electronjs](https://github.com/balena-io/resin-electronjs), a electronJS-based balena application template which can be used for easy digital signage or dashboard setup.
* [balena-wpe](https://github.com/balena-io-projects/balena-wpe), running a fullscreen browser, WPEWebkit by the [Web Platform for Embedded project](https://github.com/WebPlatformForEmbedded), with hardware accelerated CSS, WebGL, and HTML5 video on the RaspberryPi 3.
* [Build a Raspberry Pi-based network camera using WebRTC](https://www.balena.io/blog/build-a-raspberry-pi-based-network-camera/).

## Blogposts

Blogposts that are great tutorial for balena or describe interesting projects to learn from:

* [Add a cheap ILI9341 LCD to your balena Raspberry Pi project](https://www.balena.io/blog/add-a-cheap-ili9341-lcd-to-your-resin-io-raspberry-pi-project/).
* [Build a Bitcoin traffic light with balenaCloud](https://www.balena.io/blog/build-a-bitcoin-traffic-light-with-balenacloud/).
* [Build festive lighting for the holidays with balena](https://www.balena.io/blog/build-festive-lighting-for-the-holidays-with-balena/).
* [Create a GPS tracking system with cell connectivity and minimal bandwidth](https://www.balena.io/blog/balena-fin-gps-tracker-project/).
* [Deploy network-wide ad-blocking with Pi-hole and a Raspberry Pi](https://www.balena.io/blog/deploy-network-wide-ad-blocking-with-pi-hole-and-a-raspberry-pi/).
* [Make a web frame with Raspberry Pi in 30 minutes](https://www.balena.io/blog/make-a-web-frame-with-raspberry-pi-in-30-minutes/).
* [Monitoring your balena devices with Datadog](https://www.balena.io/blog/monitoring-your-balena-devices-with-datadog/).
* [Screenly OSE and Raspberry Pi](https://www.balena.io/blog/deploy-free-digital-signage-software-screenly-ose/), get up and running with a display you can control remotely to display photos, videos, dashboards, web pages, and digital signage.
* [Deploy a fleet of environmental sensors with balena & InfluxDB](https://www.balena.io/blog/deploy-a-fleet-of-environmental-sensors-with-balena-influxdb/).
* Sensors and Data Logging with Embedded Linux - The Ultimate Guide: [Part 1](https://www.balena.io/blog/sensors-and-data-logging-with-embedded-linux-the-ultimate-guide-part-1/),[Part 2: Build A Sensor Dashboard](https://www.balena.io/blog/logging-data-with-balena-part-2-build-a-sensor-dashboard/), [Part 3: Multi-Device Sensor Dashboard](https://www.balena.io/blog/sensors-and-data-logging-with-embedded-linux-the-ultimate-guide-part-3-multi-device-sensor-dashboard/).
* [How to keep your device up and running during power outages](https://www.balena.io/blog/how-to-keep-your-device-up-and-running-during-power-outages/).
* [Running a GUI application with balenaCloud](https://www.balena.io/blog/running-a-gui-application-with-balenacloud/).
* [Running a full desktop in a container](https://www.balena.io/blog/running-a-desktop-manager-with-balena/).

### Projects And Posts

* [Balena and Eduroam](https://medium.com/@bucknall/balenaos-connecting-to-eduroam-26312e7859b5), connecting to Eduroam.
* [Balena Pi-Hole](https://github.com/klutchell/balena-pihole), raspberryPi 3 balenaCloud stack with Pi-hole, PADD, & Unbound.
* [Balena Sense](https://github.com/balena-io-playground/balena-sensehat-example), example of using the Pi, Sense-HAT, InfluxDB and Grafana.
* [Balena Temperatures](https://github.com/willswire/balena-temperatures), record temperatures with TEMPer USB devices.
* [Dog Temp Texter](https://github.com/sako0938/DogTempTexter), this system is designed to connect to a wireless network and send texts to a user about a temperature sensor. The user can setup alerts that will send additional messenges.
* [ETA Nixie Tube Clocks](https://surfncircuits.com/2018/12/17/easy-iot-fleet-deployment-of-eta-nixie-tube-clocks/), easy IoT Fleet Deployment of ETA Nixie Tube Clocks.
* [LEGO Macintosh Classic with e‑paper display](https://jann.is/lego-macintosh-classic/).
* [Sonar](https://github.com/databat-io/sonar), scan the surrounding for BLE devices and produce user friendly reports for said data.
* [Take Balena for a test-drive](http://blog.alexellis.io/resin-io-test-drive/).
* [Build an air quality monitor with InfluxDB, Grafana, and Docker on a Raspberry Pi](https://www.balena.io/blog/build-an-environment-and-air-quality-monitor-with-raspberry-pi/)

### Balena Fin
* [Build a TTN LoRa Gateway with balenaFin and balenaCloud](https://www.balena.io/blog/build-a-ttn-lora-gateway-with-balenafin-and-balenacloud/).

## Balena Platform Components

* [balena base images](https://github.com/balena-io-library/base-images), the source code of the balena systemd-enabled Docker base images.
* [balena-supervisor](https://github.com/balena-io/balena-supervisor), balena's agent on devices.
* [meta-balena](https://github.com/balena-os/meta-balena), a Yocto layer used to build balena operating system images.

## Other Projects by Balena

* [balenaEtcher](https://www.balena.io/etcher/), burn images to SD cards & USB drives, safe & easy.
* [balenaOS](https://www.balena.io/os/), a host OS tailored for containers, designed for reliability, proven in production.
* [balenaEngine](https://www.balena.io/engine/), an engine purpose-built for embedded and IoT use cases, based on Moby Project technology from Docker.
* [balenaFin](https://www.balena.io/fin/), the balenaFin is a professional carrier board for the Raspberry Pi Compute Module.
* [openBalena](https://www.balena.io/open/), open source software to manage connected IoT devices.
* [Awesome balenaFin](https://github.com/balena-io-playground/awesome-balena-fin), balenaFin specific list of awesomeness.

## Contributing

Created something cool our found something interesting online? Send us a pull request!

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Balena Inc.](https://balena.io) has waived all copyright and related or neighboring rights to this work.
