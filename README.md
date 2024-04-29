# PCB Business Card

This is my custom PCB business card. I wanted to learn more about PCB design so a decided to make a fully custom PCB that functions both as a microcontroller and a business card.

This is how it looks like:

![front face](img/front.jpg)

![back face](img/back.jpg)

I used EasyEDA to design the board. A lot of it was a learning experience so the design is quite messy and it doesn't follow the best practices but for now, it's good enough for me. This is the schematic and x-ray view of the board:

![schematic](img/schematic.png)

![pcb view](img/pcb-view.jpg)

# Plans

I plan on improving on this design. Here's a couple bullet points on what I plan on improving:

- Add an NFC antenna

- Use SMD components instead (Right now, I don't really have good access to many SMD components so the components I use are all through-hole)

- Add 5V battery to provide energy for the MCU

# Credits

This project was inspired by Xander Naumenko's [PCB business card](https://github.com/misprit7/PCB-Business-Card), Anthony Kouttron's [PCB business card](https://github.com/anthonykouttron/pcb-business-card-qr-nfc) and Badr Bouslikhin's [Enchanté card](https://github.com/badrbouslikhin/Enchante)

The circuit is a standalone Arduino Uno circuit with FTDI programmer support
