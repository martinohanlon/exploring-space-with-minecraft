# Exploring the Sense HAT in Minecraft

SpaceCRAFT includes a program which creates an interactive Sense HAT and Raspberry Pi computer in Minecraft. This is a great way to explore your Raspberry Pi computer, its Sense HAT and what it can do.

![Minecraft Interactive Astro Pi](../images/astropimc.png)

A video of the Interactive Sense HAT in operation - [https://youtu.be/i4sAfVcE_9s](https://youtu.be/i4sAfVcE_9s).

## Run Minecraft

Run Minecraft by clicking `Menu > Games > Minecraft Pi`.

Click `Start Game` and enter a world by either double clicking a world you have already created or selecting `Create new`.

Leave Minecraft running and press Escape to go to the Menu and release your mouse pointer.

## Run the Interactive Sense HAT program

Open a Terminal by clicking the icon on the taskbar, or by clicking `Menu > Accessories > Terminal` and enter the following commands one by one pressing Enter after each one:

```
cd ~/SpaceCRAFT/spacecraft
python3 mcinteractiveastropi.py
```

The Interactive Sense HAT will be created directly above the player position, go back to Minecraft, look up and you should see the bottom of the Raspberry Pi. 

## Explore the Sense HAT

After the Sense HAT has appeared in Minecraft, fly up (double tap SPACE to fly, SPACE makes the player go up, SHIFT to come down), and have a look around.

You can interact with the Astro Pi computing by hitting it (RIGHT clicking) with a sword. Every part of the Sense HAT computer is 'hitable' and when you do a message will be displayed in Minecraft telling you about what you hit.  

![Interative Sense HAT](../images/interactivepi.png)

Can you find all of the parts on the Sense HAT?

### Sensors

If you hit the sensors, a message will appear in Minecraft, telling you what sensor it is and what its current value is).

Scout around and see if you can find all of the sensors - temperature, humidity, pressure, accelerometer, magnetometer and gyroscope.

### LED Matrix

Using the Sense HAT in Minecraft you can make the LED matrix on your Sense HAT light up. When you hit the LED Matrix in Minecraft the colour of the blocks will change and when they do the LED will change to the same colour.

![Sense HAT LED Matrix](../images/astropimcled.png)

### Joystick

The joystick is also hittable and will move the Sense HAT computer around the Minecraft world. 

## What Next?
Now move on to [worksheet 2](worksheet2.md) to learn how to display data from the Sense HAT in Minecraft.
