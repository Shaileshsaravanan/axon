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

oh and restructured the folder structure of the project to make it easier to navigate and find parts. I need to export step files too, will prolly do it tmrw.

**Total time spent: 3-4ish hours**

# June 18, 2025

I've been gone for long cuz of exams and have a study holiday today so time to grind despite having chem tmrw welp. so im going to try to finish all the y-axis stuff cuz there's a lot honestly and i've only done the end caps. I also found an alternate for the duet board, the Fly‑E3‑Pro V3 but still researching on it cuz it seems too good to be true as it has support for 5 motors w/o any extension boards. I've already been thinking of my second project before completing my first 😭 but idk if i'll be able to make all of them so frustrating.

I forgot most of the fusion shortcuts and stuff cuz of the gap-
ahhhh im spending sm time trying to figure how im going to do what i want to do
i have a backlog on the z-axis stuff to be exported to stl and step files, i'll do that tmrw or later idk
its SO HARD to make curved parts like wtf or im js dumb probably just the second one
idk how im going to make this work im js building stuff based on what i think i need and how the prusa works and stuff ppl have made for it on printables 
someone genuinely needs to find a plugin to export into multiple formats and locations at once
i think im done w z-axis and y-axis for a while now hopefully (foreshadowing maybe?)

anyways here's the stuff i crafted tdy:

- [y-axis belt holder](https://a360.co/3SXdeyr)
![y-axis belt holder](images/journal/june-18/y-axis_belt_holder.png)

- [y-axis tensioner](https://a360.co/4ldDb9c)
![y-axis tensioner](images/journal/june-18/y-axis_tensioner.png)

- [y-axis motor mount](https://a360.co/3FHImza)
![y-axis motor mount](images/journal/june-18/y-axis_motor_mount.png)

- [y-axis rod holder](https://a360.co/3HMG16q)
![y-axis rod holder](images/journal/june-18/y-axis_rod_holder.png)

- [y-axis mount](https://a360.co/43Ntb0r)
![y-axis mount](images/journal/june-18/y-axis_mount.png)

- [z-axis motor mount](https://a360.co/3HNQtec)
![z-axis motor mount](images/journal/june-18/z-axis_motor_mount.png)

**Total time spent: honestly no idea like maybe 6-7 hours**

# June 19 + 20, 2025

i only have like three parts left to make and need to make a whole build 3d model which i have no idea how to, i'll have to figure that out, since im using aluminium for the frame i think thats it, i lowk want to make a blacked out build but red and black seems interesting might make the 3d printed stuff red and the rods black. 

ok i js realised i forgot a bearing holder for y-axis so i have 4 parts to make thank god i rechecked everything w reprap's stuff. reprap is a really nice website w a lot of info on 3d printing

oh shit i js realised i didn't make stuff for the custom extruder mount,
also day before i realised im supposed to have ALL MY 3D PARTS IN A SINGLE FILE AND NOT MULTIPLE FILES LIKE I AM DOING RN SO ITS HARDER FOR ME TO MAKE A COMPLETED BUILD 3D MODEL 😭

and yeah i think im going to use the fly board despite it needing me to flash it myself manually using usb instead of duet's web interface.

also making the extruder + motor brackets/mounts or wtv for the extruder and additional B0 axis stuff

anyways here's today's and ydays stuff dump:

- [structure build helper z-axis](https://a360.co/4la7NrY)
![structure build helper z-axis](images/journal/june-19_20/structure_build_helper_-_z_axis.png)

- [structure build helper y-axis](https://a360.co/45shFsC)
![structure build helper y-axis](images/journal/june-19_20/structure_build_helper_-_y_axis.png)

- [structure foot](https://a360.co/4licj82)
![structure foot](images/journal/june-19_20/structure_foot.png)

- [y-axis bearing holder](https://a360.co/4ncoa9a)
![y-axis bearing holder](images/journal/june-19_20/y-axis_bearing_holder.png)

**Total time spent: again dk maybe 9-10ish hours combined (both days)**

# June 21, 2025

just need to make my bom and final mockup
since i made everything separate filed its really hard to make a full mockup 

here's the full mockup:

- [full mockup](https://a360.co/4eeKeMx)
![full mockup](images/journal/june-21/full-mockup.png)

**Total time spent: no idea like an hour or two**

# July 1, 2025

found the btt octopus board, lowk way cheaper at 60$ than the duet or fly boards being both over 100$, I will need some tools like vernier calipers and stuff but welp budget of 350$ exceeded by like 2$ so we'll cross that bridge when it comes to it.

**Total time spent: js did parts research so like an hour and half maybe?**
