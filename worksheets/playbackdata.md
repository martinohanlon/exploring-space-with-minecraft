
# Playing back data captured by the AstroPi computer

Data captured to a file by SpaceCRAFT running on the ISS or [by your own Raspberry Pi computer](capturingdata.md) can be played back in Minecraft using the SpaceCRAFT playback `mcastroplayback.py` program.

## Run Minecraft

Run Minecraft by clicking `Menu > Games > Minecraft Pi`.

Enter a world by either double clicking a world you have already created or selecting `Create World' (TODO check this)

Leave Minecraft running and press Escape to go to the Menu and release your mouse pointer.

## Run the playback program

Open a terminal by clicking `Menu > Accessories > Terminal` and enter the following commands to start the data playback program:

```
cd ~/SpaceCRAFT/spacecraft
python3 mcastroplayback.py
```

TODO - picture of playback program running

## Commands

The SpaceCRAFT playback program has a command line interface and you operate it using text based commands just like when using the terminal.

At the `SpaceCRAFT $` command type `help` to see a list of all the commands.

TODO - picture of help command output.

TODO - text of help command output.

## Playing back the data in a file

If you haven't already use the [data capture program](capturingdata.md) to create a data file.

Use the `play` command and the file path of the data file to start the Minecraft display, e.g.

```
play ~/data.csv
```

TODO - picture of the playback program running and the display in Minecraft

## Stopping playback

To stop the playback use the `stop` command.

## Exiting the program

To exit the program use the `exit` command.

## Other commands

Try the other SpaceCRAFT playback commands to see what they do:
* `speed`
* `data`

## Worksheets
1. *[Installing SpaceCRAFT](installspacecraft.md)*
2. *[Exploring the Astro Pi computer using Minecraft](interactiveastropi.md)*
3. *[Displaying data from Space in Minecraft](displayingrealtimedata.md)*
4. *[Capturing data](capturingdata.md)*
5. *[Playing back data in Minecraft](playbackdata.md)*
6. [Creating your own Minecraft display](minecraftdisplay.md)
