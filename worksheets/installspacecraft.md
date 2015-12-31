# Install SpaceCRAFT

The SpaceCRAFT programs and python module, need to be downloaded and installed before they can be used.

## Download

Open a Terminal by clicking the icon on the taskbar, or by clicking `Menu > Accessories > Terminal' (TODO - check this) and enter the following commands one by one pressing Enter after each:

```
cd ~
git clone https://github.com/martinohanlon/SpaceCRAFT
```

##Install the python library

As well as the SpaceCRAFT programs, a python library is also included to allow you to create your own SpaceCRAFT programs.

Open a terminal and enter the following commands:

```
cd ~/SpaceCRAFT/spacecraft
sudo python setup.py install
sudo python3 setup.py install
```

TODO - picture of what you should see when its installed.

The SpaceCRAFT program and module documentation is here [https://github.com/martinohanlon/SpaceCRAFT/blob/master/README.rst](https://github.com/martinohanlon/SpaceCRAFT/blob/master/README.rst).

## Next steps
1. [Exploring the Astro Pi computer using Minecraft](worksheets/interactiveastropi.md)
2. [Capturing data](worksheets/capturingdata.md)
3. [Playing back the data in Minecraft](worksheets/playbackdata.md)
4. [Creating your own Minecraft display](worksheets/minecraftdisplay.md)
