---
layout: post
title: First lessons in soldering
categories: [ham_radio, DIY]
tags: [soldering, clock, QCX]
---

![clock in vice](/assets/clock_pictures/clock_in_vice.jpg)

I'm hoping to build an HF radio soon ([QRP Labs' QCX](https://qrp-labs.com/qcx.html)). The only problem is that when I first checked out the project, I had never really soldered before. The HF radio project is substantial (as evidenced by its [141-page manual](https://qrp-labs.com/images/qcx/assembly3_LT.pdf) and [a video walkthrough](https://www.youtube.com/watch?v=_Y89tMETDsQ) showing how to build the kit), so I decided I should work on test project to start with.

I looked around on Amazon for a while and eventually settled on the [KKmoon DIY Digital LED Clock Kit](https://www.amazon.com/gp/product/B01CFK8VYO/ref=od_aui_detailpages01?ie=UTF8&psc=1). The project seemed like a good fit because:

* .. it involved soldering a variety of components on a Printed Circuit Board (PCB)
* .. was involved enough to give me some good practice,
* .. but not so involved that it would be an impossible first project,
* .. and the end result seemed useful and fun.

The instructions that come with the clock were severely abbreviated and hard-to-follow. Amazingly though, one person who bought the kit practiced building it and then wrote up a fantastic set of instructions for his class. The instructions not only show you how to build the clock step-by-step, but also point out gotchas, and provide some background on the clock's design. A PDF version of those instructions can be found [here](/assets/docs/clock_instructions.pdf). (Huge thanks to the author of these instructions!)

Before starting the project, I took some time to look at tutorials on soldering. [Here's one](https://www.youtube.com/watch?v=BLfXXRfRIzY) that I found to be helpful. Some of my important take-aways from the video and my experience with the project were:

* Be sure to clean, then tin your soldering iron before starting to work on a component. You can clean the iron with a sponge, but [cleaning flux](https://www.amazon.com/Hakko-599B-02-Wire-type-soldering-cleaner/dp/B07GSJ98QN/ref=sr_1_6?ie=UTF8&qid=1541750170&sr=8-6&keywords=cleaning+flux) may be a little easier on the iron (will spare it from the shock of the temperature change that can come with using the sponge).
* Use the soldering iron to heat the heating pad on the PCB, then apply the solder to the PCB. (Do _not_ apply the solder directly to the soldering iron).
* Soldering follows a certain rhythm - 1) place soldering iron on heating pad, hold for a second 2) now place solder on a different spot on the heating pad so it can absorb the indirect heat 3) once the solder melts, give it a moment to _flow_ onto the component 4) pull away the solder, but let the iron linger for another second or two (this gives the solder time to continue heating and, after a moment, be absorbed by the PCB hole by way of the capillary effect) and finally 5) lift the soldering iron (I did so with a quick lift so that the iron left the solder cleanly instead of pulling some solder up with it).

In order to build the project, I invested in a few tools. Here are some of the items I bought:

* [Aven circuit board holder](https://www.amazon.com/dp/B00Q2TTQEE/?coliid=I97BY5MORH5KV&colid=O9XPD0JK97JC&psc=0&ref_=lv_ov_lig_dp_it) - this turned out to be invaluable while building the clock. Would definitely recommend checking it out. Being able to quickly flip the board over to the other side turned out to be a real time saver.

* [X-Tronic Soldering iron](https://www.amazon.com/gp/product/B01DGZFSNE/ref=od_aui_detailpages01?ie=UTF8&psc=1) - a bit pricey, but it heats up in seconds, gives a nice read out of the temperature, and also includes a nice stand and solder cleaner. The soldering tip is maybe a little big, though I was able to make it work. I think I'll look around to see if I can find a replacement that is a bit smaller.

* [63 / 37 Tin Lead Rosin Core](https://www.amazon.com/gp/product/B075WBDYZZ/ref=od_aui_detailpages01?ie=UTF8&psc=1) - this was perfect; it was the right size, melted easily, flowed nicely. Really like this solder. It's really inexpensive, too ($7). Would recommend this, hands down.

* [Micro Cutter](https://www.amazon.com/gp/product/B00FZPDG1K/ref=oh_aui_detailpage_o03_s01?ie=UTF8&psc=1) - These are really basic, but I used them throughout the project to trim the excess wire after soldering. For as cheap as they are ($4) they did a fantastic chop. Nice grip, really clean cuts w/out needing too much pressure.

Things that I wish I had:

* A better magnifier / light (or maybe I should get a jeweler's loupe like [this one](https://www.amazon.com/dp/B01H8808H6/?coliid=I2UKPFVGGOK09O&colid=O9XPD0JK97JC&psc=0&ref_=lv_ov_lig_dp_it)?). If anyone has a recommendations or tips, I'll definitely take them!

Here are some pictures I took while building the kit:

![clock components](/assets/clock_pictures/components.jpeg)

_First, I taped all of the components to a sheet of paper. Organization helps!_

![clock board](/assets/clock_pictures/board.jpeg)

_Almost done at this point!_

![clock board](/assets/clock_pictures/clock_front.jpeg)

![clock board](/assets/clock_pictures/clock_back.jpeg)

_.. and the finished product!_

When I finished building the clock I was surprised at everything it could do; it included an alarm and could show the temperature (in degrees Celsius), date, and day of the week. I was also really impressed by how the clock looked. The case was clean and clear, giving a cool view of the PCB and all of the components used.

All in all, I found the clock project a bit challenging, but would definitely recommend it to anyone interested in diving into soldering and looking for good practice (perhaps before tackling a more serious project). Hope that helps! Happy soldering!
