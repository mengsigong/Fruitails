![fruitails logo](/_assets/logo_thumnail.png)
![game instruction screen](/_github/instruction_screen.png)

# Fruitails
**Fruitails** is a split screen catch game with an interactive mat controller. Players control the movement of two characters, with their feet, at the same time. There are four buttons on the mat for arrow keys. LED lights are synced with all keypress to indicate that the mat is responsive.

## Instructions - How To Build

### 1. Build your own Mat controller!

#### Materials:
* Aluminum foil tape
* Conductive thread
* Needle

1. Divide mat into four equal quadrants.

2. Use Aluminum foil tape to map out the shape of the arrows on the top of the mat.

3. Using conductive thread, sew underneath the mat following the pattern of the blue lines below. Ensure that the thread is connected to the foil tape on the top.

4. Leave strands of conductive thread at the ends to later connect with the Makey Makey.
![game instruction screen](/_github/conductive_thread.png)
![game instruction screen](/_github/mat_back.png)

### 2. Connect your Mat controller to the Makey Makey!

#### Materials:
* Classic Makey Makey board
* Breadboard
* LED lights
* Alligator clips
* Wires

1. Plug in the Classic Makey Makey board with the USB cord to your computer.

2. Download and install the Arduino IDE with the Makey Makey Firmware using the following online resource (http://www.makeymakey.com/remap/).

3. In settings.h tab, modify the inputs for the click button pad, space button pad, right arrow pad and left arrow pad to ‘a’, ‘s’, ‘k’, and ‘l’.
