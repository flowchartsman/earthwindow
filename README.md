# earthwindow
A project to create a self-contained viewing window of Earth from space.

## Concept
Soon [Urthecast](https://www.urthecast.com/) will be opening up its API to real-time (or near-real-time) images of the Earth from the International Space Station). This project aims to create software that will interface with this API and provide a persistent, streaming view of the planet on an HDMI-equipped TV or monitor.

## Implementation

### Hardware
The project should be able to be hosted on a [Raspberry Pi](https://www.raspberrypi.org/), [Beaglebone Black](http://beagleboard.org/BLACK) or other similar device. Licensing fees or API keys may apply, though data on usage is difficult to come by at the moment.

### Software
The OS will most likely be a flavor of Linux running X, though BSD has not been ruled out yet.

Backend software will be written in Go.
