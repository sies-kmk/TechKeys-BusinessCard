# TechKeys-BusinessCard
TechKeys BusinessCard Firmware by Grendel on GeekHack

info here:
https://geekhack.org/index.php?topic=53378.0


The LED's reflect the NUM, CAPS, and SCR lock LED's of a keyboard. If no lock LED is on, the card will start a little demo display after 5s. The NUM and SCR lock LED status is used to select different layers/functions:

NUM and SCR off: (l2r) Cancel timer, +10min, +1 min. Light show at countdown
NUM on: keys are mapped to (l2r) : Vol-, Mute, Vol+
SCR on: keys are mapped to (l2r): Prev. Track, Play/Pause, Next Track
NUM and SCR on: bootloader will be started after 5s

if the CAPS LED is on the keys will behave like the original firmware, regardless of the state of the other two LED's

Features:

to start the boot-loader, now the Num- and Scroll-lock LED's have to be on for 5s at the same time (any other combination will not start the BL)changed the PWM mechanism, also went from 6b to 8b PWM
Lock-on LED indicators are now run at 12.5% brightness
more catchy demo-mode
demo-mode can be toggled on/off by pressing all three switches at the same time (if off the system LED will be on very faintly if no lock LED is active)
reordered LED's & switches to match the LED sequence on keyboards: NUM, CAPS, SCR (left-to-right)

