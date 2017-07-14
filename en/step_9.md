## Run the real-time SpaceCRAFT display program

Run Minecraft by clicking `Menu > Games > Minecraft Pi`.

Click `Start Game` and enter a world by either double-clicking a world you have already created or selecting `Create new`.

Leave Minecraft running, press `Escape` to go to the menu and release your mouse pointer.

Open a terminal by clicking the icon on the taskbar, or by clicking `Menu > Accessories > Terminal`, and enter the following commands one by one, pressing `Enter` after each command:

```
cd ~/SpaceCRAFT/spacecraft
python3 mcastrorealtime.py
```

The SpaceCRAFT display will be created in front of the player's position. If you go back to Minecraft and look up, you will see the ISS.

