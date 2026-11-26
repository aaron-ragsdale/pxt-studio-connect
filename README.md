# pxt-studio-connect
custom block for makecode micro:bit to connect to a virtual interface 


# Studio Connect (Bluetooth UART)
Import https://github.com/aaron-ragsdale/pxt-studio-connect in MakeCode Extensions. Add connect to Studio on start, send number or text anywhere, and register one on Studio message handler to receive commands. The handler automatically answers PING with studio:PONG.

Dashboard: https://aaron-ragsdale.github.io/microbitStudio/

Protocol: newline-delimited name:value messages; incoming commands are newline-delimited strings. LED patterns use led: followed by 25 binary digits.

Bluetooth UART must be enabled and compatible pairing settings used. Standard micro:bit radio conflicts with Bluetooth.

Experimental: compilation and physical device testing are required.
