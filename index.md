# Blinky 101

Blinky101 is a collection of projects that helps you get up to speed with various microcontroller platforms. The goal is to provide step by step tutorials and guides to help you start developing using open source tools.

When you want to start developing with a new microcontroller you need to get it working as soon as possible. That way you know that your hardware is sound and you can fully focus on learning all the microcontrollers ins and outs.

The Blinky101 project is focussed on just one thing: getting a LED to blink, which is the *Hello World* program of microcontrollers. Once you have a blinky running, you can expand the program to do more advanced stuff.

## Guides by microcontroller platform

Below you find a list of supported platforms. Each platform has a set of guides that gets you started with setting up the debugger and creating your own firmware.

* **[lpc11uxx Series](https://blinky101.github.io/blinky_lpc11uxx/)**: Entry-level 32-bit cortex-m0 microcontrollers, 50MHz, built-in USB.
    
    Tutorials:
    * [Part 0: Getting Started](./blinky_lpc11uxx/getting_started)
    * [Part 1: Bare-metal Blinky](./blinky_lpc11uxx/tutorial_part1)
    * [Part 2: Basic Blinky](./blinky_lpc11uxx/tutorial_part2)
    * [Part 3: CPM Blinky](./blinky_lpc11uxx/tutorial_part3)
    
* **[lpc43xx Series](https://blinky101.github.io/blinky_lpc43xx/)**: Dual-core cortex-M4 + cortex-M0 microcontroller, 204MHz, USB 2.0 High-Speed.
    
    Tutorials:
    * [Part 0: Getting Started](./blinky_lpc43xx/getting_started)
    * [Part 1: Bare-metal Blinky](./blinky_lpc43xx/tutorial_part1)
    * [Part 2: Basic Blinky](./blinky_lpc43xx/tutorial_part2)
    * [Part 3: CPM Blinky](./blinky_lpc43xx/tutorial_part3)


## Supported debuggers

This is a list of debuggers: they are used to connect to your target board. The microcontroller guides above will have instructions on how to use them with each specific platform.

* Black Magic Probe
    
    This is our preferred debugger: the [Black Magic Probe](https://github.com/blacksphere/blackmagic/wiki) is fully open-source, easy to setup and requires no special software.
    
* OpenOCD

    Most projects can also be debugged/flashed via [OpenOCD](http://openocd.org) (e.g. in combination with the [JTAG LockPick tiny 2](http://www.distortec.com/jtag-lock-pick-tiny-2/)).


## Help us add more content

The goal of Blinky101 is to crowd-source knowledge about as many platforms as possible and make it available for everybody.
Do you have knowledge about a microcontroller that is not listed yet, or want to contribute other content that might be relevant?
[Check our github](https://github.com/blinky101) and consider sending a pull request or open an inssue.

