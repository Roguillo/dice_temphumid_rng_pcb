Repo for first PCB project

- consists of a small custom PCB featuring a temperature and humidity sensor, a 3-digit 7-segment display, and RGB LEDs in the form of die faces
- After a startup LED animation across both the RGB LEDs and the display segments, the display constantly alternates between showing temperature and showing humidity
- There is also a button that can be used for the following depending on press duration:
   - rolling dice (short): this will generate a random number from 2 to 12 to be displayed on the RGB LEDs for a second
   - generating a random number (medium): this will generate a random 3-digit number and show it on the segment display for a second, with a short pre- and post-display LED wave animation
   - toggling units (long): this will toggle between Celsius and Fahrenheit. Celsius is the default unit used at startup
