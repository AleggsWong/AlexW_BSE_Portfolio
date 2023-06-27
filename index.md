# Smart Mirror

The smart mirror is a customizable mirror run off the Raspberry Pi OS. Using Node.js, the mirror displays different modules that display different types of information, such as the weather or recent news updates. The modules are completely customizable and can be coded to display databases from Notion or Google sheets, for example.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alex W | Mountain View High School | Electrical Engineering | Incoming Senior


  
# Final Milestone
# Second Milestone
For this milestone, I've customized the display of the mirror. On download, the mirro comes with a couple of default modules (see milestone one). I added 3 new modules: 3-day weather updates, Spotify 'now playing', and a Notion database display. The modules were created through 3rd party code [here](https://github.com/MichMich/MagicMirror/wiki/3rd-party-modules). Each one has detailed and specific instructions on the integration process. 

### Components
1. 3rd party modules found on github
2. config.js: essentially the framework of the mirror; actually file that is run, accesses other files by calling their classes; contains the modules array where required module information is stored
3. modules folder: downloaded during Magic Mirror installation (see milestone 1); 3rd-party modules from github are downloaded here and can be called in config.js
4. JavaScript: coding language used
5. JSON: used to store and transport information
6. other dependency folders: generally untouched unless debugging; almost always the same across modules

### Progress/Customizing Display
As of the second milestone, I have:
1. added 3 3rd-party modules
2. 3-Day Weather Forecast: displays weather forecast for today, tomorrow, and day after
<br> → github link found [here](https://github.com/nigel-daniels/MMM-3Day-Forecast)
3. Spotify On-Play: displays current song playing (if any at all), along with relevant information about the song, such as the title and progress through the song
<br> → github link found [here](https://github.com/Fabrizz/MMM-OnSpotify)
4. Notion Database: displays information from a Notion database, which is highly customizable. In my case, it displays my To-Do's database by ascending date and shows the due date.
<br> → github link found [here](https://github.com/choffmann/MMM-Notion)

# First Milestone

I'm currently building the smart mirror, which is a mirror that can display real-time and customizable information. It has several default modules, such as compliments, real-time news updates, and the time. Through Github, I'm able to add a few modules of my own or even code them once I learn how. 

### Components
1. Raspberry Pi 400 Keyboard: used as the brains of the monitor; contains the operating system, power supply, and code to run the display; also used to type on the monitor
2. Monitor: connected to the keyboard; displays the mirror itself
3. Mouse: connected to the keyboard; used to navigate the monitor since the keyboard has no integrated mouse pad
4. Node.js: JavaScript runtime environment used to download code from Github and run it; display runs off of Node

### Progress/Setting Up Display
As of the first milestone, I have
1. Flashed the Pi imager onto an SD card using [Raspberry Pi's imager software](https://www.raspberrypi.com/software/)
2. Inserted the SD card into the Raspberry Pi 400 keyboard and connected the keyboard to the monitor and a powersource
<br> → I used USB C as a powersource for the keyboard and a micro-HDMI to HDMI cable to connect the keyboard to the monitor 
4. Downloaded Node.js using terminal and the instructions found on the [Magic Mirror website](docs.magicmirror.builders)
5. Navigated to the 'Magic Mirror' directory using the command 'cd Magic Mirror'
6. Run one final 'npm run start' command in the command prompt of the Raspberry Pi to yield the display.

### Challenges
The biggest challenge I faced was actually hooking the Pi up to the monitor. The first Pi I used was faulty and kept getting hot when I plugged it in. I found another Pi, but when I hooked it up to the monitor, the monitor didn't detect an input and fell asleep. I realized this was because the Pi wasn't reading the SD card, for whatever reason, but after testing several Pis, the keyboard finally worked. 

### Next Steps
My plan for the future is the create a wooden frame for the mirror and secure the monitor to the frame using nylon strips. To give the mirror a more aesthetic look, I'm going to attach LEDs to the frame around the monitor. In order to power the LEDs, I'll need to attach a power strip as well. 

# Starter Project
 <img src="rgbproject.jpg" width="450" height="300">

<iframe width="560" height="315" src="https://www.youtube.com/embed/XVKCBS4upeY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The project consists of an RGB LED, board, and three switches each corresponding to RGB (red, green, blue) values. Sliding the swtches up and down controls the intensity of each color on the LED, which allows the LED to display a gradient of colors. The three switches and LED shown are soldered on the back, and the longest pin of the LED is slotted into the hole with a - sign indicated. 

### Components 
1. Soldering board: holds the project; parts are soldered to the board to keep them in place and create a circuit
2. Common Cathode LED: 4-pin LED that takes in 3 positive inputs and 1 negative output - power flows through the 3 positive pins (flow into those pins is controlled by the slide switches) and out the negative output. As electricity runs through the bulb, it releases light, the color of which depends on the orientation of the switches.
3. Slider switches: switches that slide back and forth; 3 switches connected to the 3 input pins of the LED; sliding a switch up or down controls the amount of red, green, or blue light (RGB) light the LED emits.

### Progress
The LED and switches have been completely soldered to the board and can properly conduct a current, which allows the LED to emit light once connected to a power source. 

### Challenges

I ran into trouble soldering the LED because I didn't push the LED flush with the board before soldering, so it was stuck in a raised position. However, I learned that didn't matter because current could still flow to the LED.



# Code

# Bill of Materials

## Starter Project
1. RGB LED
2. Soldering board
3. 3 switches

## Smart Mirror


# Other Resources/Examples
