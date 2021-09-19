# Universal-Solder-AM-Receiver-Dev-Board
A Development board for the Raspberry Pi and Universal Solder's AM Atomic Clock receiver (v3).

Universal Solder sell a very effective AM receiver module for atomic clocks (60kHz, 70kHz) as can be found here:

https://www.universal-solder.ca/product/canaduino-60khz-atomic-clock-receiver-module-wwvb-msf-jjy60/

https://www.universal-solder.ca/product/canaduino-60khz-atomic-clock-receiver-module-wwvb-msf-jjy60/

However at the time of writing they are still showing v2 of the board but shipping v3. The pinout has changed and the operation is slightly different, so here for your entertainment is a Pi HAT style development board that accepts v3 of the board for developing your own projects.

This is version 2 of the board:

![v2](https://github.com/GOTO-GOSUB/Universal-Solder-AM-Receiver-Dev-Board/blob/7418d5689d70d755efa77df07ea4ad0ef6a8c09e/Images/AM%20Receiver%20V2.png)

And this is version 3:

![v3](https://github.com/GOTO-GOSUB/Universal-Solder-AM-Receiver-Dev-Board/blob/7418d5689d70d755efa77df07ea4ad0ef6a8c09e/Images/V3%20bare%20board.jpg)

This repository contains a Fritzing project file and Gerbers if you should wish to make this development board for yourself. While I wait on my own PCB's to come back from the fabricator here is a render of the board:

![PCB examples](https://github.com/GOTO-GOSUB/Universal-Solder-AM-Receiver-Dev-Board/blob/7418d5689d70d755efa77df07ea4ad0ef6a8c09e/Images/AM%20Receiver%20V3%20Pi%20Zero%20HAT%20Style%20Dev%20Board%20Render.png)

Please note that the Antenna connections on the module's PCB have been brought out to the HAT's PCB with the intention of connecting the ferrite via a terminal block for ease of use, but this is optional.

Here is an example of the module in use on an alternative development board. Please note that the OLED intereferes with the reception (of MSF60, at least) so I cannot really recommend this particular application but hey, it's fun and better PCB routing might solve the problem. It is presented here for entertainment value.

![Time on OLDED](https://github.com/GOTO-GOSUB/Universal-Solder-AM-Receiver-Dev-Board/blob/7418d5689d70d755efa77df07ea4ad0ef6a8c09e/Images/V3%20board%20on%20Pi3%20with%20OLED.jpg)

If you need a hand in decoding MSF60 you can use the tool developed by Ben Clifford here:

https://github.com/benclifford/msf

The development board presented here was designed to use that software to decode the time.
