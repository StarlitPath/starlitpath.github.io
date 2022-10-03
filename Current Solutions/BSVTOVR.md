---
title: Base Stations + Vive Trackers
parent: Current Solutions
description: Overall price: $700-$900 | Vive Trackers are often considered the standard for body tracking, while expensive, they provide the best tracking quality.
---

# Base Stations + Vive Trackers
Despite the fact HTC makes the trackers, **you can use them with any headset** given you add [compatible](#remarks) base stations to your setup. It's often considered the de facto standard for full-body tracking.

**Overall price:** $700-$900

### Requirements:
- **Two Base Stations**, either 1.0 (HTC Vive) or 2.0 (Vive Pro, Valve Index)
  - **Base Station 1.0**: Roughly $200, the field of view is considerably smaller than with 2.0 stations. As well, you can only ever get two of them.
  - **Base Station 2.0**: Roughly $400, They won't work with 1.0 Trackers, but they're a better investment if you intend on getting a larger playspace, as you can add up to four of them.
- Both generations come with wall mounting hardware, though what's included with 1.0 stations can be quite brittle.<br><br>
You can also put the Base Stations on a table or shelf, though, giving them an angle will increase your overall tracking volume considerably.

- **Three Vive or Tundra trackers**
  - Vive Trackers come in three separate generations:
    - **Vive Tracker 3.0**, the newest revision, a complete design change from the 2.0 Trackers, they have longer battery life, and they're lighter, but they also cost more, at around $130 each.
    - **Vive Tracker 2.0**, this is what everyone has. it's, a tracker, a puck if you will. They're about $100 each.  
    You can find them in 3-packs at a discount.
    - **Vive Tracker 1.0**, rather rare these days, but if you can score them for cheap on the used market, can be a great deal. (Expect around $300-400 for a set of three)
  - **Tundra trackers**, created by Tundra Labs, these are third-party trackers compatible with the Base Station tracking system. They are even smaller than 3.0 trackers, and have great battery life. Though they have less sensors on them, so occluding them from the stations is easier.  
  They don't often go on sale, so you need to keep an eye on all things Tundra Labs to know when the next release batch will happen if you're interested.

- **3x USB 2.0 ports or better**, you need to connect 3 USB dongles, one for each tracker. [As said in remarks](#remarks) sometimes you may need to dedicated a full USB host controller chipset to the dongles.

- **OpenVR-SpaceCalibrator** is needed to line up trackers to your VR headset tracking space. It's installer will also adjust the necessary SteamVR settings to allow the trackers SteamVR driver to be enabled.
  - Download it [here](https://github.com/pushrax/OpenVR-SpaceCalibrator/releases/latest), click the .exe file and run it.
  - Get support on [the official Discord](https://discord.com/invite/m7g2Wyj)

### Thoughts:
The price of the entire setup, when added on top of buying a Quest 2, does not make for a good value proposition.

If you haven't got a headset yet, you would likely get a cheaper better experience purchasing a PCVR headset kit that comes with the base stations already.

If you do decide to do so, OpenVR Space Calibrator is an impressive piece of software with active helpers on the Discord server. Recalibration is common however.

### Remarks
2.0, 3.0 and Tundra Trackers work fine with both generations of Base Stations. But **1.0 Trackers can only see 1.0 Base Stations.** They can't understand the pattern from the 2.0s.

**Base Stations are seen by trackers. Not the other way around.** They only send data to each other, not to trackers, and not to the computer. Bluetooth is only ever used for firmware updates.

**DO NOT INSTALL FIRMWARE UPDATES. You don't need them**, and there's a strong chance of you bricking the stations by doing it.

It's technically possible to use a single Base Station, but facing away from it will stop trackers from seeing it, and they will freeze in place.

Some computers may require dedicating a full USB chipset to the tracker dongles. This isn't usually the case, but it's important to keep in mind, especially for laptops.

**Reducing Interference**  
Trackers communicate with the USB dongles over a 2.4GHz band, the same used by Bluetooth and Wi-Fi 4 (802.11n) devices.  
If you, or your neighbors have a lot of Wi-Fi 4 devices around, you could run into interference issues, this will results in trackers randomly freezing as they lose connection and have to find the signal again.

To reduce risks of interference, either connect compatible Wi-Fi 5/6/6E devices to a 5GHz band, and/or connect the USB dongles to USB extension cords to move them away from your computer's electrical interference, and closer to where you play VR.