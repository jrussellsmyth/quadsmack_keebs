# TestDrive - Explore Popular Keyboard Layouts

The **TestDrive** project is designed to provide open-source designs and resources for building ergonomic keyboards with various popular physical layouts at an affordable cost. It allows users to experiment with different keyboard layouts before committing to a final purchase.

## Key Features:
- **Affordable Prototyping:** Our designs focus on minimizing costs, making it easy to build and test various layouts without a significant investment.
- **Modular Design:** Each design is created with ease of assembly and part reusability in mind. This means you can easily swap out key switches and microcontrollers (MCUs) between different keyboard builds. One pair of development boards and one set of keys can be used to try all of the layouts available for that board!
- **Minimal Off-the-Shelf Parts:** The keyboard designs prefer build over buy, only requiring the absoute minimum of purchased parts, making it simple and cost-effective to build multiple layouts. No need for expensive or proprietary components.
- **Hot-Swap Free:** You can move components like switches and MCUs between boards without the need for additional commercial hot-swap sockets, thanks to the design providing these capabilities natively.

## Why TestDrive?
When I first discovered the world of Ergonomic Split Keyboards, I was facinated and a bit overwhelmed by the vast array of layouts available. I wanted to try a few to see what would work best for me, but did not want to spend hundreds on all the boards out there, so I decided to build some. As I iterated on these, I found/adapted some techniques to keep the costs down and reduce part count.

**TestDrive** allows you to “try before you buy,” offering the ability to test out different layouts and configurations to find what works best for your ejsrgonomic needs and typing preferences. Whether you're new to custom keyboards or an enthusiast, TestDrive makes it easier than ever to explore the world of ergonomic layouts.

Over time, we will add more boards. This repository will be organized by the development board needed to support a set of boards, for instance, the first set of TestDrive boards are based on the **Seeed Studio XAIO RP2040**, so these will all be found in the `XaioRP2040` folder.

## Test Drive Boards

Assembly instructions can be found [here](/TestDrive/Docs/Assembling.md)

### Seeed Studio XAIO RP2040
Boards based on the [Seed Studio  XAIO RP2040 Development board](https://wiki.seeedstudio.com/XIAO-RP2040/) can be found in the [XaioRP2040]() folder.
* **Corne36** Classic 3x5_3 Corne key layout. Based on [foostan/crkbd](https://github.com/foostan/crkbd)
   * [Case](/TestDrive/XaioRP2040/Case/Corne36)
   * [Firmware](/TestDrive/XaioRP2040/Firmware/quadsmack_testdrive_xiao2040_corne36_vial.uf2)
* **Fifi** Split 3x5_3 Keyboard with more agressive column stagger. Layout based on [raychengy/fifi_split_keeb](https://github.com/raychengy/fifi_split_keeb)
   * [Case](/TestDrive/XaioRP2040/Case/Fifi)
   * [Firmware](/TestDrive/XaioRP2040/Firmware/quadsmack_testdrive_xiao2040_fifi_vial.uf2)
* **KLOR Sagewerk** Klor Sagewerk keyboard layout. Aggressive Stagger + Splay. Based on [GEIGEIGEIST/KLOR](https://github.com/GEIGEIGEIST/KLOR)
   * [Case](/TestDrive/XaioRP2040/Case/KlorSagewerk)
   * [Firmware](/TestDrive/XaioRP2040/Firmware/quadsmack_testdrive_xiao2040_klor_sagewerk_vial.uf2)
* **KLOR Konrad** Klor "Konrad" keyboard layout. Agressive Stagger, Splay, and 2 extra pinky keys on each side. Based on [GEIGEIGEIST/KLOR](https://github.com/GEIGEIGEIST/KLOR)
   * [Case](/TestDrive/XaioRP2040/Case/KlorKonrad)
   * [Firmware](/TestDrive/XaioRP2040/Firmware/quadsmack_testdrive_xiao2040_klor_konrad_vial.uf2)


## Assembly Tools
A few tools that can make assembling a TestDrive board simpler can be found in the [Tools](/TestDrive/Tools) folder

* [__DiodeClamp.stl__](/TestDrive/Tools/DiodeClamp.stl): - This is a plate to snap into the keywell after placing the diode. This holds the diode while you wrap the lead and makes the wrapping easier.
* [__WirePusher.stl__](/TestDrive/Tools/WirePusher.stl): - A small tool to push the diode wire back through the board when wrapping
* [__DiodeBender.stl__](/TestDrive/Tools/DiodeBender.stl): A jig to pre-bend 5 diodes at a time to simplify installation.
* [__WireWrapFixture.stl__](/TestDrive/Tools/WireWrapFixture.stl): A tool to help twist the diode leg for the row connection. Add one M2x8 screw.
   