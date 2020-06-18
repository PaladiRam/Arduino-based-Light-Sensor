# Arduino based Light Sensor System
The project involves the designing of a light sensor using Light dependant resistor , this can be effectively used in many systems where the operations have to change with change in brightness , for example switching on of street lights at night , alarm bell that rings in the night when small intensity of light coming to it is cut off.

In this project we will be showing an implementation of the basic circuit required for the fore mentioned applications.

Introduction: An LDR is a resistor that changes its resistance based on the light falling on it. Using a LDR in a circuit with arduino uno board we control the lights that glow.

A detailed description of Hardware components used

Input and Output Each of the 14 digital pins on the Arduino Uno can be used as an input or output, using pinMode(), digitalWrite(), and digitalRead() functions. They operate at 5 volts. Each pin can provide or receive a maximum of 40 mA and has an internal pull-up resistor (disconnected by default) of 20-50 kOhms.

In addition, some pins have specialized functions:

Serial: pins 0 (RX) and 1 (TX). Used to receive (RX) and transmit (TX) TTL serial data. These pins are connected to the corresponding pins of the ATmega8U2 USB-to-TTL Serial chip.

External Interrupts: pins 2 and 3. These pins can be configured to trigger an interrupt on a low value, a rising or falling edge, or a change in value. See the attachInterrupt() function for details.

For the implementation involved please refer to the complete guide document. PWM: 3, 5, 6, 9, 10, and 11. Provide 8-bit PWM output with the analogWrite() function.

SPI: 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK). These pins support SPI communication using the SPI library.

LED: 13-There is a built-in LED connected to digital pin 13. When the pin is HIGH value, the LED is on, when the pin is LOW, it’s off. The Uno has 6 analog inputs, labeled A0 through A5, each of which provide 10 bits of resolution (i.e. 1024 different values). By default they measure from ground to 5 volts, though is it possible to change the upper end of their range using the AREF pin and the analogReference() function. Additionally, some pins have specialized functionality:

TWI: A4 or SDA pin and A5 or SCL pin. Support TWI communication using the Wire library.

There are a couple of other pins on the board:

AREF. Reference voltage for the analog inputs. Used with analogReference().

Reset. Bring this line LOW to reset the microcontroller. Typically used to add a reset button to shields which block the one on the board.

Arduino UNO details: Arduino UNO board: Power 5v and 3v3: Provide regulated 5 and 3.3v to power external components according to manufacturer specifications. Digital pins 0-13 serve as digital input/output pins. Pin 13 of the Arduino is connected to the built in LED. Pins 3,5,6,9,10,11 have

PWM capability. Here each pin can provide/sink up to 40 mA max. But the recommended current is 20 mA. Pulse Width Modulation (PWM) is a modulation technique used to encode a message into a pulsing signal. The PWM enabled pins produce a constant frequency of ~ 500 Hz, while the duty cycle changes according to theparameters set by the user. The duty cycle determines how long a signal stays high out of the total period.

For the implementation part please refer to complete guide document
