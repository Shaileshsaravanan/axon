---
title: "Axon"
author: "Shailesh"
description: "4-axis custom 3D printer based on Prusa i3 architecture."
created_at: "2025-06-11"
---

# June 11, 2025

I'm quite not exactly a "pro" at CAD modeling only 3d printed project I've done so far is a rover with a friend, so well naturally I have started with making the simplest and basic parts needed for the printer from scratch using Fusion360 (and yt) and the frame will be made using 2040 V-slot aluminum similar to a Bear Upgrade.

Also I am either redesigning the parts from scratch or if im using smth that already exists I am still making it from scratch cuz I'm still learning CAD and I'm not exceptionally good at it. I will be using the [Prusa i3 MK3S+](https://www.printables.com/model/57217-i3-mk3s-printable-parts) as a reference for the parts and their dimensions. I am not going to use the Prusa i3 Mini Rambo and display stuff so naturally those stuff will not be included.

I am also planning to use Fullcontrol with Klipper firmware with a Raspberry Pi for the 4th axis control and support as Marlin doesn't natively support >3-axis control.

- [z-axis leadscrew cap](https://a360.co/3HE5PBH)
![z-axis leadscrew cap](images/journal/june-11/z-axis_leadscrew_cap.png)

- [z-axis end caps](https://a360.co/4dXiFXP)
![z-axis end caps](images/journal/june-11/z-axis_end_caps.png)

- [y-axis end caps](https://a360.co/45oOS8p)
![y-axis end caps](images/journal/june-11/y-axis_end_caps.png)

- [z-axis top](https://a360.co/43T0UEn)
![z-axis top](images/journal/june-11/z-axis_top.png)

A Prusa i3 uses a Mini Rambo control board, however since I have an additional axis and an extra stepper motor for the 4th axis, I will be using a Duet3D Mini 5+ board for the printer as it allows for more motors to be controlled, and a Duet 3 Mini 2+ expansion board for an additional 2 stepper motor drivers. The boards are quite expensive 😭 but welp needed for the 4-axis mod. I also plan on getting a Raspberry Pi with a Display and camera for octoprint but we'll see about that later, depending on my BOM.

**Total time spent: 5-6h**

# June 12, 2025

I have made some more parts today, I'm still not sure about the design of the z-axis top part, I might change it later. I'm working on the PSU mount and cable clips today. I had a few ideas on the mounting of the Duet3D Mini 5+ board and the Duet 3 Mini 2+ expansion board with a raspberry pi and a display, I might make a custom mount for them later.

These are the parts I made today:

- [psu upper mount](https://a360.co/4jLz3fi)
![psu upper mount](images/journal/june-12/psu_upper_mount.png)

- [psu lower mount](https://a360.co/3HT5qLH)
![psu lower mount](images/journal/june-12/psu_lower_mount.png)

- [cable horizontal clip](https://a360.co/4600grg)
![cable horizontal clip](images/journal/june-12/cable_horizontal_clip.png)

- [cable vertical clip](https://a360.co/4e1TbZw)
![cable vertical clip](images/journal/june-12/cable_vertical_clip.png)

oh and restructured the folder structure of the project to make it easier to navigate and find parts. I need to export step files too, will prolly do it tmr.

**Total time spent: 3-4ish hours**