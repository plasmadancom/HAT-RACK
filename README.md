<p align="center">
    <a href="https://www.kickstarter.com/projects/plasmadan/hat-rack-din-rail-mount-for-raspberry-pi-hats?utm_source=github&utm_medium=banner&utm_campaign=kickstarter" target="_blank" rel="nofollow">
        <img alt="KickStarter Banner" src="https://ksr-ugc.imgix.net/assets/026/487/839/6091c0ebeb610f404bd6deeebc0617e7_original.png?ixlib=rb-2.1.0&w=700&fit=max&v=1568587329&auto=format&frame=1&lossless=true&s=90c9609d6607b560a8d47b7d2db9f114">
    </a>
</p>

![HAT RACK](/img/hat-rack.gif)

Stackable HATs have become the de facto standard in the Raspberry Pi community, but stacking HATs together can make them difficult to get to, awkward to maintain and can lead to excessive heat built-up.

HAT RACK solves this by separating the stack into an easier to manage array. Each board is connected together in parallel which is perfect for I2C based HATs such as Raspberry Pi's [Sense HAT](https://pinout.xyz/pinout/sense_hat).

HAT RACK is the big brother to our [DINPi board](https://github.com/plasmadancom/DINPi), and is backwards compatible! HAT RACK allows multiple Raspberry Pi HATs/pHATs to be connected to a single Raspberry Pi. Ideal for home automation, IoT, or industrial control applications. The plug & play design allows you to create tidy, professional looking setups easily!

## Features
* Connect 3 HATs or 6 pHATs
* Plug & play Raspberry Pi or Pi Zero
* Daisy chain multiple boards
* DIN rail mountable
* External power in
* BCM pin numbering
* Gold flash plated contacts
* UL, CE and RoHS (lead free) compliant

![HAT RACK DIN Rail](/img/hat-rack-din-rail.gif)

A single Raspberry Pi can be mounted upside down. No need for ribbon cables, just plug & play! Available as a kit, simply solder whichever headers / sockets you require for your project. Or buy an assembled unit with all the parts pre-installed [here](https://plasmadan.com/hatrack).

## Incredibly Versatile

![HAT RACK Animated](/img/hat-rack-animated.gif)

HAT RACK can be configured in a whole bunch of ways. In theory there's no limit to how many boards you can have, provided you can supply enough power to them.

## External Powering

You can optionally externally power your boards. This may be necessary when using lots of HATs or pHATs as the Raspberry Pi may not be able to supply enough power to them. This will depend on the HATs being used. Low-power HATs (such as our [CTRL HAT](https://plasmadan.com/ctrlhat)) can be daisy chained several times before external powering becomes necessary.

## Device Compatibility

HAT RACK is fully compatible with all **40-way** Raspberry Pi models and clones.

| Device Model | Compatibility |
| --- | :---: |
| Raspberry Pi Model A/B | &#x274c; |
| Raspberry Pi Model B | &#x274c; |
| Raspberry Pi 1 Model A+/B/B+ | &#x2714;&#xFE0F; |
| Raspberry Pi 2 Model B | &#x2714;&#xFE0F; |
| Raspberry Pi 3 Model B/B+ | &#x2714;&#xFE0F; |
| Raspberry Pi 4 | &#x2714;&#xFE0F; |
| Raspberry Pi Zero | &#x2714;&#xFE0F; |
| Asus Tinker Board | &#x2714;&#xFE0F; |
| Orange Pi | &#x2714;&#xFE0F; |
| Odroid | &#x2714;&#xFE0F; |

### Pin Conflicts

Connecting multiple HATs from different manufacturers can introduce pin conflicts which prevent your boards from working correctly. This usually only happens with HATs which are not designed to stack.

The easiest way to solve it is to physically remove the conflicting pin for one of the HATs. It's a simple enough task to heat-up the solder and pull the pin out with a pair of pliers.

## Parts List
* 2×20 pin header - For mounting HATs/pHATs – x6
* 2×20 pin socket - For mounting Raspberry Pi upside down
* 2×20 pin 90 degree header
* 2×20 pin 90 degree socket
* 3.5mm pitch terminal block
* 100 µF Electrolytic capacitor
* DIN rail adaptor (Phoenix Contact 1201578 or generic) – x3

## 3D Model

We have released an interactive [3D model](https://grabcad.com/library/hat-rack-1) which you can use in your designs.

## Dimensions

<p align="center">
    <a href="https://raw.githubusercontent.com/plasmadancom/HAT-RACK/master/img/hat-rack-v1.1-dimensions.svg">
        <img alt="Mechanical Drawing" src="/img/hat-rack-v1.1-dimensions.svg">
    </a>
</p>

# Change Log

* V1.0
    * Final prototype, as shown on [KickStarter](https://www.kickstarter.com/projects/plasmadan/hat-rack-din-rail-mount-for-raspberry-pi-hats?utm_source=github&utm_medium=changelog&utm_campaign=kickstarter)!
* V1.1
    * Larger solder pads improve solderability
    * DIN rail mounting holes reduced from 4mm to 3.5mm for a more precise fit