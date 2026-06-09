# ORRERY · A Mechanism for Seeing Time

An interactive digital companion to a physical "orbital speed" orrery built for a Year 11 physics exhibition.

A central 50-tooth drive gear carries the Sun and meshes with four planet gears (Mercury, Venus, Earth, Mars). One full turn of the drive gear is **one Earth year**, and each planet gear's tooth count is derived from its real NASA sidereal period, so every planet spins at its true relative orbital frequency, accurate to under 1%.

Crank the Sun gear, drag it, or let it run, and watch the inner planets race at their real relative speeds.

**Live site:** https://cabaci-eth.github.io/orrery-exhibition/

The entire project is a single self-contained `index.html` (inline CSS + JS; fonts and KaTeX via CDN). No build step, no backend.

## Credits
Designed & built by **Miguel Wang · Lucas Chen · Edward Jiang**.

Orbital data: [NASA NSSDCA Planetary Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/).
