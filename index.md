<p align="center">
  <img src="images/carloop_mark.png" alt="Carloop Logo"/>
</p>

# What is Carloop?
Carloop is an open source development kit that lets you easily access a car's CAN bus.

<a href="images/Photo2_750.jpg" data-caption="Carloop" data-fancybox="what-is-carloop">
  <img src="images/Photo2_750.jpg" width="355"/>
</a>

Now that you have your Carloop, we understand you are anxious to connect it to your car and start developing some apps!

This page will walk you through how to get started and how to dig deeper into writing custom Carloop apps.

If you feel lost at any point, feel free to post in the Carloop community.

[Visit Carloop community >](https://community.carloop.io)

# Getting started with Carloop

To get started with Carloop, all you need is the following:

- [Carloop Basic](https://store.carloop.io/products/carloop-basic?utm_source=github&utm_campaign=docs)
- Computer with OSX/Windows/Linux to program and flash
- Micro-usb to USB cable

## The hardware pieces explained

### The Carloop board

The Carloop board connects to the OBD-II port in any car.

<a href="images/Carloop.jpg" data-caption="Carloop board" data-fancybox="hardware">
  <img src="images/Carloop.jpg" class="narrow-image">
</a>

### The microcontroller

The brain of Carloop can be the Particle Photon (Wi-Fi microcontroller), the Particle
Electron (3G cellular microcontroller) or the Red Bear Duo (Bluetooth +
Wi-Fi microcontroller).

<a href="images/microcontrollers.jpg" data-caption="Microcontrollers compatible with Carloop" data-fancybox="hardware">
  <img src="images/microcontrollers.jpg" class="narrow-image">
</a>

### Assembled Carloop

Plug in the microcontroller into the Carloop board. Make sure to put the USB port towards the right.

The Carloop Basic comes pre-assembled with a Particle Photon.

<a href="images/Carloop_assembled.jpg" data-caption="Carloop with a Photon" data-fancybox="hardware">
  <img src="images/Carloop_assembled.jpg" class="narrow-image">
</a>

## Get Ready to develop

You'll be using the tools from [Particle](https://www.particle.io) to
program the software in the Photon and Electron.

### Set up a Particle account

If you don't have a Particle account, take the time to
<a href="https://login.particle.io/signup" target="_blank">sign up for an account now</a>.

### Connect your device to the Internet

You'll need to connect your Particle Photon or Particle Electron to the
Internet so you can program it.

The easiest way to do that is to connect the device to USB and follow the
steps on the [Particle setup page](https://setup.particle.io).

### Get familiar with the Particle

You'll be writing code for Carloop in the [Particle Web IDE](https://build.particle.io).

It's a good idea to go through a first Particle project if you have not
programmed a Particle device before.  The [Particle
documentation](https://docs.particle.io) has step-by-step examples.

## Your first Carloop project

Here's a project to make the blue LED on the Photon or Electron blink when receiving
data through the OBD port.

### Step 1: Create New App
Go to [build.particle.io](https://build.particle.io) and click on Create New App, you'll see this:

<a href="images/create_new_particle_app.png" data-caption="Create a new app" data-fancybox="getting-started">
  <img src="images/create_new_particle_app.png">
</a>

### Step 2: Add Carloop Library
Add the Carloop library to your app by clicking on the Libraries button and search for the Carloop library. Once you find it, click on it.

<a href="images/library_create.png" data-caption="Search for the Carloop library" data-fancybox="getting-started">
  <img src="images/library_create.png">
</a>

### Step 3: Include in App
To include the Carloop library in your app, you have to manually click the INCLUDE IN APP button so the app you are building will now which library to use.

<a href="images/include_library.png" data-caption="Include the Carloop library" data-fancybox="getting-started">
  <img src="images/include_library.png">
</a>

### Step 4: You're done!
Now you are ready to start programming your own app! Follow Hello World on the next page to learn how to blink and LED!

<a href="images/library_included.png" data-caption="Start using the library in your code" data-fancybox="getting-started">
  <img src="images/library_included.png">
</a>


## Advanced development

Install the [Particle CLI (Command Line Interface)](https://www.particle.io/cli) to be able to program your Carloop locally instead of over the air.

## Pinout


