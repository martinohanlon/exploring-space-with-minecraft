## Capturing data from the Sense HAT

During the [Principia](https://astro-pi.org/principia/) mission ESA astronaut [Tim Peake](http://timpeake.esa.int/) ran the SpaceCRAFT data capture program for a week. 

The SpaceCRAFT program created a [file of data](resources/SpaceCRAFT_20160209_104426.csv) from all the Sense HAT's sensors, and this was sent back to Earth, allowing you to see what conditions were like on the ISS.

You can use your Raspberry Pi and Sense HAT in the same way to capture data about your environment, whether that's in your home, classroom or anywhere else you can find to set it up.

### Run the data capture program

The SpaceCRAFT data capture program needs to be run from the command line and passed a number of parameters telling it how long to run for, how often to read data, and where to create the data file.

--- task ---

Open a terminal by clicking **Menu**, **Accessories**, **Terminal** and enter the following commands to run a short test, which will capture data to a file called `data.csv` for 60 seconds, every 1 second:

```
cd ~/SpaceCRAFT/spacecraft
python3 astropidatalogger.py ~/data.csv 60 1
```

![Run data capture](images/rundatalogger.jpg)

--- /task ---

While the program is running, an animation created by Hannah Belshaw will be shown on the Sense HAT LED matrix; the pattern changes each time data is read from the sensors and written to the file.

The program will run for 60 seconds.

--- collapse ---

---
title: Data capture options 
---

The data capture program requires you to pass a number of parameters which tell it how to run and where to save the data. If you run the program using the optional `-h` parameter: 

```
python3 astropidatalogger.py -h
```

It will display all of the available options:

```
usage: astropidatalogger.py [-h] [-v] filename timetorun interval

Sense HAT Data Logger

positional arguments:
	filename       The output filename
	timetorun      The time in seconds the logger should run for
	interval       The time in seconds between each write

optional arguments:
	-h, --help     show this help message and exit
	-v, --verbose  Output verbose debug statements

```

When you ran the data capture program, you passed three parameters:

- filename( - `~/data.csv`
2. timetorun - `60`
3. interval - `1`

These parameters have to be passed to the program, but can be changed to suit your needs, such as making it write to a different file, run longer or read data less often. For example, to run the program writing to a file called `hannahsdata.csv` for 30 minutes (1,800 seconds), reading data once a minute (60 seconds), you would use this command:

```
python3 astropidatalogger.py ~/hannahsdata.csv 1800 60
```

**Caution** - if you use the name of a file which already exists, it will be overwritten without warning and the old data file will be lost.

--- /collapse ---

## Examine the data

The data from the sensors is written to a [CSV (Comma Seperated Values) file](https://en.wikipedia.org/wiki/Comma-separated_values), which is a common way of storing data. 

This can be opened using a spreadsheet application, including Libre Office Calc which comes preinstalled on Raspbian.

--- task ---

Open the file using LibreOffice Calc and have a look at the data:

1. Open LibreOffice Calc by clicking **Menu**, **Office**, **LibreOffice Calc**
1. Click **File**, **Open**
1. Select **All Files**
1. Double-click `data.csv`
1. Click **OK** on the Text Import window

![Sense HAT data in LibreOffice Calc](images/datainspreadsheet.jpg)

The top row is the name of the field, and each row after this is one line of data.

--- /task ---

--- challenge ---

## Challenge: Create a chart using data from the ISS

You can download the SpaceCRAFT data which was captured on the ISS [here](resources/SpaceCRAFT_20160209_104426.csv). 

![Sense HAT CPU temperature data as a line graph](images/dataingraph.JPG) 

Load this data into LibreOffice Calc and use **Insert**, **Chart** to start the Chart Wizard.

--- /challenge ---