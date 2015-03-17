# Parts #

  * Large floating Picture frame (uses two pieces of glass to hold pictures)
  * Mirror tint for windows (and tools to apply it)
  * Four Maxim Max7221 chips
  * Four LED matrices compatible with the MAX7221 chip (common cathode)
  * Large perf-board to accommodate the width of the 4 LED matrices and Max chips.
  * 3/4 wood square rod (enough to build a rectangular space between the two pieces of glass and a inner perimeter of 40 inches)
  * Arduino Uno
  * Super glue
  * Lots of wire
  * Four resistors that are capable of controlling your LED matrix with the Max 7221 chip
  * One push button with appropriate resistor
  * One meter addressable LED strip


# Assembly #

  1. Solder the four matrices, resistors, and Max7221 chips together on the perf-board. (ZIP chips can be used if you think you might reuse the Max chips in the future)
  1. Apply the Mirror tint to the two pieces of glass
  1. Build a rectangular frame with a inner perimeter of one meter
  1. Glue the LED strip to the inside of the frame
  1. Cut a small notch in the frame so the wires can be reached from the outside of the frame
  1. Apply glue and sandwich the frame between the two pieces of glass but make sure the mirror tint is on the outside of the sandwich
  1. Build another frame around the perf-board and matrix to keep it level against the glass and support the mirror
  1. Because the matrix is sitting outside of the infinity mirror, the leds wont be bright enough to shine through both pieces of glass. To fix this, cut out a rectangle the size of the matrix display in the back mirror tint
  1. Glue the matrix and frame to the back of the infinity mirror
  1. Wire the button to the digital pin 2
  1. Wire the data pin from the led strip to pin 4
  1. Wire the clock pin from the led strip to pin 5
  1. Wire the data pin from the MAX7221 chips to pin 10
  1. Wire the clock pin from the MAX7221 chips to pin 9
  1. Wire the load pin from the MAX7221 chips to pin 8
  1. Wire the appropriate Vcc and GND