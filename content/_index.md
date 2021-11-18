+++
title = "Drogue IoT"
+++

# Overview

The Drogue IoT project aims to bring together data and users in an _Internet of Things_ world.

Drogue IoT consists of components that may be used standalone or together:

* **Drogue Cloud** is an efficient and scalable connectivity layer for forwarding telemetry data safely from devices to business applications, and commands back to devices. 
* **Drogue Device** is a framework for writing safe and efficient applications on microcontroller type of systems. 

# Cloud

![Drogue Cloud](overview.svg)

Drogue Cloud supports multiple open standard protocols for devices:

* HTTP
* MQTT
* CoAP

Through a multi-tenant model of applications and devices, Drogue Cloud lets you securely manage
devices and their credentials.

Drogue Cloud can run wherever *you* want to run it, and you can own the data yourself. However, you
can also choose to selectively use managed services for parts you don't want to manage yourself.

Don't take our word for it, got to [https://sandbox.drogue.cloud](https://sandbox.drogue.cloud) and
see for yourself!

Go to our [documentation](https://book.drogue.io/drogue-cloud/dev/index.html) to get started with Drogue Cloud, or join the community on [GitHub](https://github.com/drogue-iot/drogue-cloud).

# Device

In a world without memory management or operating system it is more important than ever to avoid memory corruption and undefined behavior. With Drogue Device, you can write safe, composable and connected embedded applications. 

* Built using [rust](https://www.rust-lang.org), an efficient, memory safe and thread safe programming language.
* Offers built-in drivers for internet connectivity, such as WiFi and LoRaWAN.

Go to our [documentation](https://book.drogue.io/drogue-device/dev/index.html) to get started with Drogue Cloud, or join the community on [GitHub](https://github.com/drogue-iot/drogue-device).

# Getting started

We try to make is as easy as possible to get you started:

* **[Public sandbox](https://sandbox.drogue.cloud)** – A public sandbox to let you try out the cloud side services without the need to install them manually. Just sign up with your GitHub account, and try it out.
* **[Buy a device](https://microbit.org/buy/?version=microbitV2)** – The micro:bit v2 is easy to get, and easy to use. It offers a few sensors and is supported by Rust and Drogue IoT out of the box. Just be sure to get a <u>**v2**</u>!
* **[Workshops](https://book.drogue.io/drogue-workshops/index.html)** – A set of workshops, that walk you through more complex scenarios step-by-step. Different workshops focus on different aspects and technologies.
* **[Meet the code](https://github.io/drogue-iot)** – Check out the code on our GitHub organization.
* **[Meet the people](https://matrix.to/#/#drogue-iot:matrix.org)** – Get in contact with us in our Matrix channel.

# Open source

Drogue IoT is *open source*, and all components are licensed under the Apache 2.0 license.  Development is done on [GitHub](https://github.com/drogue-iot).

This means, that you can participate in the development process. Everyone is welcome! Contributions come in various
ways, not only code.
