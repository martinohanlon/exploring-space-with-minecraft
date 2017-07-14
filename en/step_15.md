## Command line options

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

