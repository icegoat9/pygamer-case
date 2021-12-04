# pygamer-case

The [Adafruit PyGamer](https://www.adafruit.com/product/4242) is a small $45 gaming handheld for DIY development in CircuitPython, MakeCode Arcade or Arduino, sold as a PCB without enclosure.

I bought one, and while there's an option for a lasercut case, I didn't love how the bolts/nults stick out of the back, and I like the look of the exposed PCB front, so I'm experimenting with a few 3D printed or machined case options to hold it and the optional battery and speaker. I posted an image on twitter and a few people asked me if I would share the STL, so this is a tiny repo just for that (see STL in file list above).

![animation of pygamer in case](pygamer-backcase1.gif)

The current case works, but because this was a quick one-evening design after measuring the PCB by hand, the fit around the top connectors leaves some open space. I'm printing a second version soon (Dec 2021) and will update this if it fits better.

## Fabrication

I made it out of SLS (selective laser sintered) Nylon, which has nice resolution and a somewhat chalky texture that feels nice in the hand, though you could add a bead blasted / 'media tumbled' finish if you like it a bit smoother. It should be ~$20-$30 at typical 3D print shops.

This first version is assembled with M3x4mm nylon screws carefully tapped directly into the slightly-undersized holes in the 3D print, which is not advised if you want to be able to open and close it many times (but I realized I was missing an M3 tap). Next time I'll tap it with an actual steel tap or use spring tabs. Using [brass heat-set inserts](https://www.adafruit.com/product/4256) is a more robust way to use threaded fasteners with plastic parts, but because the holes in the PCB are so close to the edge I wasn't sure I'd have enough plastic to support those.

## Related

I've written a [simple poker solitaire puzzle game](https://twitter.com/icegoat9/status/1459791190153334786) for the PyGamer as an excuse to play around with CircuitPython for the first time. The code's a bit of a mess but once I clean it up I'll open source it in case it's useful to anyone else new to CircuitPython and the PyGamer...
