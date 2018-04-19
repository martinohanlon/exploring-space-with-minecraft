## Play back captured data 

Data that you capture with the Sense HAT can be displayed in Minecraft using the SpaceCRAFT playback `mcastroplayback.py` program.

--- task ---

Start Minecraft, enter a world, and press <kbd>Escape</kbd> to go to the menu.

--- /task ---

--- task ---

Open a terminal window and enter the following commands to start the data playback program:

```
cd ~/SpaceCRAFT/spacecraft
python3 mcastroplayback.py
```

--- /task ---

The SpaceCRAFT playback program has a text-based user interface. After it starts, it will wait for you to enter a command just like a terminal window.

--- task ---

Type `help` into the `SpaceCRAFT $` prompt to see a list of all the commands:

```
Welcome to SpaceCRAFT data playback.  Type help or ? to list commands.

SpaceCRAFT $ help

Documented commands (type help <topic>):
========================================
data  exit  help  play  speed  stop
```

![The playback program](images/playbackhelp.png)

--- /task ---

--- task ---

Use the `play` command to display the data you captured in the `data.csv` file.

```
play /home/pi/data.csv
```

![Playing back data in Minecraft](images/playbackrunning.png)

--- /task ---

The SpaceCRAFT display will appear in Minecraft and play back the data.

You can stop the playback at anytime by entering the `stop` command.

To exit the program, use the command `exit`.
