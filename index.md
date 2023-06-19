# Smart Mirror

The smart mirror is a customizable mirror run off the Raspberry Pi OS. Using Node.js, the mirror displays different modules that display different types of information, such as the weather or recent news updates. The modules are completely customizable and can be coded to display databases from Notion or Google sheets, for example.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alex W | Mountain View High School | Electrical Engineering | Incoming Senior


  
# Final Milestone
# Second Milestone
# First Milestone

I'm currently building the smart mirror, which is a mirror that can display real-time and customizable information. The project consists of a Raspberry Pi and a monitor that's hooked up to the Pi. The Raspberry Pi uses the Raspberry Pi Desktop OS. 
* The monitor serves as the mirror and runs off the Pi
* So far, I've been able to use the mirror's display, which is just a simple screen that has a couple of default modules.

### Process
1. Flash the Pi imager onto an SD card using Raspberry Pi's imager software
2. Insert it into the Raspberry Pi 400 keyboard and connected the keyboard to the monitor and a powersource
<br> → I used USB C as a powersource for the keyboard and a micro-HDMI to HDMI cable to connect the keyboard to the monitor 
4. Download Node.js using the instructions found on the [Magic Mirror website](docs.magicmirror.builders)
5. Navigate to the 'Magic Mirror' directory using the command 'cd Magic Mirror'
6. Run one final 'npm run start' command in the command prompt of the Raspberry Pi to yield the shown display.

### Challenges
The biggest challenge I faced was actually hooking the Pi up to the monitor. The first Pi I used was faulty and kept getting hot when I plugged it in. I found another Pi, but when I hooked it up to the monitor, the monitor didn't detect an input and fell asleep. I realized this was because the Pi wasn't reading the SD card, for whatever reason, but after testing several Pis, the keyboard finally worked. 

My plan for the future is the create a wooden frame for the mirror and then completely customize it using 3rd party modules

# Starter Project
 <img src="rgbproject.jpg" width="450" height="300">

<iframe width="560" height="315" src="https://www.youtube.com/embed/XVKCBS4upeY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The project consists of an RGB LED, board, and three switches each corresponding to RGB (red, green, blue) values. Sliding the swtches up and down controls the intensity of each color on the LED, which allows the LED to display a gradient of colors. The three switches and LED shown are soldered on the back, and the longest pin of the LED is slotted into the hole with a - sign indicated. I ran into trouble soldering the LED because I didn't push the LED flush with the board before soldering, so it was stuck in a raised position. However, I learned that didn't matter because current could still flow to the LED.


# Code

# Bill of Materials

## Starter Project
1. RGB LED
2. Soldering board
3. 3 switches

## Smart Mirror


# Other Resources/Examples
