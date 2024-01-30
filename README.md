# Rpi Pico based GPS Clock for a Car
Nice and simple, I want to make a replacement clock for the VFD clock that sits in my car, but I want it to be a little smarter than the piece of junk that's already in there. 

This project will have 2 components. The software, which will be written in CircuitPython, and a PCB design to (eventually) get it in to the position of the car.

## Feature Goals
These are the features (and their current status) that I intend on implementing with the project.
- Display the GPS Time on a 7 segment display (complete)
- Adjust the GPS time to local time using a time zone offset (partial)
- Flashing time separator using LEDs (complete)
- Headlight signal input to adjust brightness if car headlights are switched on (to do)
- Ambient light sensor to adjust brigtness (to do)
- Buck converter to convert car voltage to voltage appropriate for Rpi Pico (to do)
