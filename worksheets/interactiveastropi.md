# Exploring the Astro Pi computer

SpaceCRAFT includes a program which creates an interactive Astro Pi computer in Minecraft. This is a great way to explore your Raspberry Pi computer, its Sense HAT and what it can do.

![Minecraft Interactive Astro Pi](../images/astropimc.png)

A video of the Interactive Astro Pi in operation - [https://youtu.be/i4sAfVcE_9s](https://youtu.be/i4sAfVcE_9s).

## Run Minecraft

Run Minecraft by clicking `Menu > Games > Minecraft Pi`.

Enter a world by either double clicking a world you have already created or selecting `Create World' (TODO check this)

Leave Minecraft running and press Escape to go to the Menu and release your mouse pointer.

## Run the Interactive Astro Pi program

Open a Terminal by clicking the icon on the taskbar, or by clicking `Menu > Accessories > Terminal' (TODO - check this) and enter the following commands one by one pressing Enter after each:

```
cd ~/SpaceCRAFT/spacecraft
python3 interactiveastropi.py (TODO check this) 
```

The Interactive Astro Pi computer will be created directly above the player position, go back to Minecraft, look up and you should see the bottom of the Raspberry Pi. 

## Explore the Astro Pi computer and Sense HAT



by right clicking while holding a sword.

TODO - picture of the top of the Sense HAT

Challenge - can you find all of the sensors on the Sense HAT? 

### Sensors

Find all the sensors (temperature, pressure, accelerometer, magnetometer and gyroscope)

### LED Matrix

Make a pattern appear on your Sense HAT.

### Joystick

Hit the joystick to make the  the Astro Pi computer move around the Minecraft world.

## Next steps
1. [Capturing data](worksheets/capturingdata.md)
2. [Playing back the data in Minecraft](worksheets/playbackdata.md)
3. [Creating your own Minecraft display](worksheets/minecraftdisplay.md)