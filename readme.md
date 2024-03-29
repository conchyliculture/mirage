MIRAGE - 1.0
=============

This framework is released as an opensource project using the MIT License.

Mirage is a powerful and modular framework dedicated to the security analysis of wireless communications. It actually provides :

 * a lightweight and hackable Bluetooth Low Energy protocol stack
 * multiple highly customizable offensive modules (e.g. Man-in-the-Middle, sniffing, jamming, hijacking, cloning …)
 * mutiple modules dedicated to information gathering (e.g. ATT/GATT dumping, scanning …)
 * a chaining operator allowing to easily combine attack modules in order to build complex attack workflows
 * supports of multiple Bluetooth Low Energy devices, such as HCI devices, BTLEJack and Ubertooth sniffers
 * supports of tools for monitoring HCI communications, using ADB or Hcidump
 * an user-friendly development environment allowing to easily write new modules or customize existing ones

Useful links
------------

 * Documentation: http://homepages.laas.fr/rcayre/mirage-documentation/index.html
 * Documentation (sphinx source code): https://redmine.laas.fr/projects/mirage-documentation
 * Mirage can use a custom BTLEJack firmware for the BBC Micro:Bit, adding some specific features for manipulating advertisements: https://redmine.laas.fr/projects/btlejack-custom-firmware

The original BTLEJack firmware, written by Damien Cauquil, is available on github : 

 * BTLEJack: https://github.com/virtualabs/btlejack
 * BTLEJack firmware: https://github.com/virtualabs/btlejack-firmware
