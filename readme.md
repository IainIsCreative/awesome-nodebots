# Awesome Nodebots [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A list of resources, links, tools, tutorials and more to make nodebots — robots powered by web technology.

## Contents

- [Libraries and Plugins](#libraries-and-plugins)
  - [IO Compatibility Plugins](#io-compatibility-plugins)
  - [Robot Programming Plugins](#robot-programming-plugins)
- [Examples](#examples)
- [Articles](#articles)
- [Videos](#videos)
  - [Nodebot Demos](#nodebot-demos)
  - [Talks](#talks)
- [Tutorials](#tutorials)
  - [Getting Started](#getting-started)
  - [Interesting Nodebots](#interesting-nodebots)
  - [Advanced Nodebots](#advanced-nodebots)
- [Books](#books)


## Libraries and Plugins

Javascript libraries you can use to make your nodebots come to life.

- [Johnny-Five](http://johnny-five.io) — The premier Robotics and IoT platform for JavaScript.
- [Node Pixel](https://github.com/ajfisher/node-pixel) — A library for programming Adafruit NeoPixels using JavaScript.
- [OLED JS](https://github.com/noopkat/oled-js) — A Johnny-Five compatible library for using OLED Displays with JavaScript.

### IO Compatibility Plugins

Plugins that you may need depending on the board you're using for IO and Johnny-Five.

- [Galileo/Edison/Joule-IO](https://github.com/rwaldron/galileo-io) — Compatibility library for the Intel Galileo/Edison/Joule.
- [Raspi-IO](https://github.com/nebrius/raspi-io) — Compatibility library for the Raspberry Pi.
- [Particle/Core/Photon-IO](https://github.com/rwaldron/particle-io) — Compatibility library for the Spark Particle/Core/Photon IO.
- [BeagleBone-IO](https://github.com/julianduque/beaglebone-io) — Compatibility library for the BeagleBone Black.
- [Remote-IO](https://github.com/monteslu/remote-io) - Firmata Compatiblity IO Plugin for remote interaction with Johnny-Five.
- [Chip-IO](https://github.com/sandeepmistry/node-chip-io) — IO compatibility plugin for Johnny-Five when using the Next Thing Co. C.H.I.P.
- [Imp-IO](https://github.com/rwaldron/imp-io) — Johnny-Five IO compatibility plugin for the Electric Imp.
- [Bean-IO](https://github.com/monteslu/bean-io) — LightBlue Bean IO plugin that can be used with Johnny-Five.
- [Pinoccio-IO](https://github.com/soldair/pinoccio-io) — IO plugin for the Pinoccoio board with Johnny-Five compatibility.

### Robot Programming Plugins

Plugins you may want to use to program your robots.

- [Temporal](https://github.com/rwaldron/temporal) — Task sequencing for your robot.
- [React Hardware](https://github.com/iamdustan/react-hardware) — A React library for programming your robot with React Components.
- [J5 RC Receiver](https://github.com/rwaldron/j5-rc-receiver) — A plugin for Johnny-Five for using a Radio Control Receiver with your Robot.
- [J5-Songs](https://github.com/julianduque/j5-songs) — A collection of songs ready to play over a Piezo using Johnny-Five.

## Examples

Amazing nodebots to see and be inspired by.

- [Raspberry Pi KittyCam](https://github.com/girliemac/RPi-KittyCam) — an app using a Raspberry Pi with motion sensors and a camera by [Tomomi Imura](http://twitter.com/girlie_mac)
- [Smoker.js](https://github.com/neilff/smoker-js) — a BBQ thermometer that uses websockets to read temperature.
- [RobotArm](https://github.com/cheton/robotarm) — a JavaScript powered Robot Arm using Johnny-Five by [Cheton Wu](https://twitter.com/cheton)
- [Sumobot Jr.](https://github.com/makenai/sumobot-jr) — a budget Sumobot powered by Johnny-Five by [Pawel Szymczykowski](https://twitter.com/makenai)
- [ServoControl](https://github.com/pixelslip/ServoControl) — a small prototype using `DeviceMotion` on a device to control a Servo by [Pierre Boumal](https://twitter.com/pixelslip)
- [leapLamp](https://github.com/xseignard/leapLamp) - a Leapmotion controlled lamp using Johnny-Five and Node by [Xavier Seignard](https://twitter.com/xavier_seignard).
- [Johnny-Five Speech Recognition Lamp](https://github.com/IainIsCreative/johnny-five-speech-recognition-lamp) - a lamp that loops through colours and uses `SpeechRecognition` for control by [Iain](https://twitter.com/IainIsCreative).
- [RN-Arduino-Blink](https://github.com/christopherdro/RN-Arduino-Blink) — an example of using React Native and Johnny-Five for a simple blink function by [Christopher Dro](https://twitter.com/_cdro).
- [React & Johnny-Five Traffic Lights](https://github.com/IainIsCreative/react-johnny-five-traffic-lights) — a project using React and Johnny-Five for controlling a set of traffic lights by [Iain](https://twitter.com/IainIsCreative).
- [Intel Edison Weather Station](https://www.hackster.io/rajjan/edison-weather-station-10b611) by [Rajjan](https://github.com/rajjan).
- [OLEDJS Designer](https://github.com/hxlnt/oledjs-designer) — an application to draw image in the browser and show on an OLED display by [Rachel Simone Weil](https://twitter.com/partytimeHXLNT(). 

## Articles

Articles covering subjects involving Johnny-Five and JavaScript robotics.

- [React Hardware](http://iamdustan.com/2015/12/16/react-hardware/) — an article by [Dustan Kasten](https://twitter.com/iamdustan) covering his React Hardware Library.
- [Voice Controlling a Robot using Arduino, node.js, MQTT, WebSockets, Johnny-Five and HTML5 Speech Recognition!](https://utbrudd.bouvet.no/2015/01/11/voice-controlling-a-robot-using-arduino-node-js-mqtt-websockets-johnny-five-and-html5-speech-recognition/) — an article by [Mark West](https://twitter.com/markawest) covering a voice controlled SumoBot for Bouvet.
- [Raspi-IO](https://www.hackster.io/nebrius/raspi-io-3f2a0b) — a post by [Bryan Hughes](https://twitter.com/nebrius) showing what Raspi-IO is and how it's used with Johnny-Five.
- [Using Johnny-Five to power Neopixels](https://chrisruppel.com/blog/arduino-johnny-five-neopixel/) — an article covering the usage of `node-pixels` and using the library with Johnny-Five to power NeoPixels by [Chris Ruppel](https://twitter.com/rupl).

## Videos

Videos showing examples of nodebot prototypes and ideas as well videos for learning.

- [Exploring the Arduino with NodeJS and Johnny-Five](https://www.youtube.com/watch?v=8s2--hfsJDY) — [Patrick Catanzariti](https://twitter.com/thatpatrickguy) shows how to get started with using Arduino and Node.JS.

### Nodebot Demos

Demonstrations of prototype nodebots and ideas.

- [ServoControl](https://www.youtube.com/watch?v=oxHW6sVNzpk) — a demonstration of ServoControl by [Pierre Boumal](https://twitter.com/pixelslip)
- [Leapmotion controlled lamp with arduino and node.js](https://vimeo.com/68530396) - a robot lamp using Leapmotion for control by [Xavier Seignard](https://twitter.com/xavier_seignard).

### Talks

Talks about nodebots and Johnny-Five.

- [Johnny-Five by John Chapman](https://www.youtube.com/watch?v=R3kZwBWGLqg) — a talk by [John Chapman](https://twitter.com/JohnChapman) for South East Michigan JavaScript Users, 2014.
- [Johnny-Five JavaScript Robots](https://www.youtube.com/watch?v=jf-cEB3U2UQ) — [Rick Waldron's](https://twitter.com/rwaldron) talk about JavaScript Robotics from Nodeconf 2012.

## Tutorials

Tutorials you can read to learn how to make your own nodebots — from beginner, to advanced.

### Getting Started

- [Hardware Hacking With JavaScript](https://www.smashingmagazine.com/2016/02/hardware-hacking-with-javascript-internet-of-things/) by [James Miller](https://twitter.com/jimhunty) and [Mate Marschalko](https://twitter.com/MateMarschalko) for Smashing Magazine.
- [Getting started with Arduino, johnny-five and Websockets](http://blog.ricardofilipe.com/post/getting-started-arduino-johhny-five) by [Ricardo Magalhães](https://twitter.com/magalhini).
- [How to Create a Smart Device With Arduino and Node.js Using PubNub](https://code.tutsplus.com/tutorials/how-to-create-a-smart-device-with-arduino-and-nodejs-using-pubnub--cms-25508) by [Tomomi Imura](http://twitter.com/girlie_mac) for TutsPlus.
- [Getting Started with Johnny Five for IoT with Tomomi Imura (Part 1)](https://www.youtube.com/watch?v=sC72DCxQrcU) - A starter tutorial for using Johnny-Five and hardware by [Tomomi Imura](http://twitter.com/girlie_mac) for PubNub.
- [Getting Started with Johnny Five for IoT with Tomomi Imura (Part 2)](https://www.youtube.com/watch?v=S1jVmBnzwH8) - Part two of the starter tutorial in using Johnny-Five by [Tomomi Imura](http://twitter.com/girlie_mac) for PubNub.
- [Connecting Johnny-five (Arduino, Raspberry Pi etc) over WiFi to the PC using ESP8266](https://medium.com/@imkiran/connecting-johnny-five-arduino-raspberry-pi-etc-over-wifi-to-the-pc-using-esp8266-a10348fdb300) by [Sai Kiran](https://twitter.com/_imkiran).
- [Hardware for Front End Developers](http://blog.ricardofilipe.com/post/light-my-house) by [Ricardo Magalhães](https://twitter.com/magalhini).
- [Programming Raspberry-Pi Robots with JavaScript](https://www.packtpub.com/books/content/programming-raspberry-pi-robots-javascript) by [Anna Gerber](https://twitter.com/annagerber) for PacktPub.
- [Learning JavaScript and Arduino programming with Johnny-Five](https://utbrudd.bouvet.no/2014/12/30/learning-javascript-and-arduino-programming-with-johnny-five/) by [Mark West](https://twitter.com/markawest) for Bouvet.
- [JavaScript Powered Arduino with Johnny-Five](https://www.safaribooksonline.com/blog/2013/07/16/javascript-powered-arduino-with-johnny-five/) by [Derick Bailey](https://twitter.com/derickbailey) for Safari Books Online.
- [Nodebot Workshop](https://github.com/tableflip/nodebot-workshop) — a Nodeschool repository for learning how to use Johnny-Five, no microcontroller required.

### Interesting Nodebots

- [Read Analog Data Wirelessly with the Feather HUZZAH and Johnny-Five](http://www.samjulien.com/johnny-feather/) by [Sam Julien](https://twitter.com/samjulien).
- [RemoteBots Cutting the Cord with Remote IO](https://www.iceddev.com/blog/remotebots-cutting-the-cord-with-remote-io/) by [Luis Monte](https://twitter.com/monteslu) for Iced Dev.
- [Control your Arduino with a web app via Meteor and Johnny Five](https://github.com/studiorabota/meteor-johnny-five-tutorial) by [Studio Rabota](https://twitter.com/studiorabota).

### Advanced Nodebots

- [KittyCam - Building a Raspberry Pi Camera with Cat Face Detection in Node.js](http://www.girliemac.com/blog/2015/12/25/kittycam-raspberrypi-camera-cat-face-recog-nodejs/) by [Tomomi Imura](http://twitter.com/girlie_mac).
- [NW.js, Johnny-Five & Arduino: A Wicked Trio](http://tangiblejs.com/posts/nw-js-johnny-five-arduino-wicked-trio) by [John-Phillipe Côté](https://twitter.com/jpcote) for TangibleJS.

## Books

- [Make: JavaScript Robotics](https://www.makershed.com/products/make-javascript-robotics) — A great book for getting started with Nodebots and learning how to make awesome projects with Johnny-Five.
- [Learning JavaScript Robotics](https://www.packtpub.com/hardware-and-creative/learning-javascript-robotics?gclid=Cj0KEQjwp83KBRC2kev0tZzExLkBEiQAYxYXOiF5ar8k8SY4U80M4vGp184qCAkANVHcS5kE9__UKikaAspo8P8HAQ&gclsrc=aw.ds) — A detailed book on using Johnny-Five from components and boards to the web and online services.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Iain (@IainIsCreative)](http://twitter.com/IainIsCreative) has waived all copyright and
related or neighboring rights to this work.
