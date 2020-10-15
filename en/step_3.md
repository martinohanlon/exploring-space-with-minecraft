## Exploring the Sense HAT in Minecraft

SpaceCRAFT includes a program that creates an interactive Astro Pi (made of a Sense HAT and a Raspberry Pi computer) in Minecraft. Using is a great way to explore what your Raspberry Pi computer and its Sense HAT can do.

![Minecraft Interactive Astro Pi](images/astropimc.png)

[Video of the Minecraft Interactive Astro Pi](https://youtu.be/2OJeBvv7m-I)

### Start Minecraft

--- task ---

Run Minecraft by clicking **Menu** > **Games** > **Minecraft Pi**.

--- /task ---

--- task ---

Click **Start Game*** and enter a world by either double-clicking a world you have already created or selecting **Create new**.

--- /task ---
 
--- task ---

Leave Minecraft running, but press <kbd>Esc<kbd> to go to the menu and release your mouse pointer.

--- /task ---

### Run the interactive Astro Pi program

--- task ---

Open a terminal by clicking the icon in the taskbar, or by clicking **Menu** > **Accessories** > **Terminal**, and enter the following commands:

```
cd ~/SpaceCRAFT/spacecraft
python3 mcinteractiveastropi.py
```

--- /task ---

This will create an interactive Astro Pi directly above the player's position. If you go back to Minecraft and look up, you should see the bottom of the Raspberry Pi. 

--- task ---

Explore the Sense HAT in Minecraft: fly up and have a look around. 

Double-tap <kbd>Space</kbd> to fly, press <kbd>Space</kbd> to make the player go up, and press <kbd>Shift</kbd> to make the player come down.

--- /task ---

--- task ---

Interact with the Sense HAT by hitting it (right-clicking) with a sword. When you hit it, a message will either be displayed in Minecraft telling you about the part that you've hit or it will make the Sense HAT light up.  

![Interactive Sense HAT](images/interactivepi.png)

--- /task ---
