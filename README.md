![!](plasma-logo.png)

[![Build Status](https://travis-ci.com/pimoroni/plasma.svg?branch=master)](https://travis-ci.com/pimoroni/plasma)
[![Coverage Status](https://coveralls.io/repos/github/pimoroni/plasma/badge.svg?branch=master)](https://coveralls.io/github/pimoroni/plasma?branch=master)
[![PyPi Package](https://img.shields.io/pypi/v/plasmalights.svg)](https://pypi.python.org/pypi/plasmalights)
[![Python Versions](https://img.shields.io/pypi/pyversions/plasmalights.svg)](https://pypi.python.org/pypi/plasmalights)

https://shop.pimoroni.com/products/plasma

Eight super-bright RGB LED indicators, ideal for adding visual notifications to your Raspberry Pi on their own or on a pHAT stacking header.

## Installing

### Full install (recommended):

We've created an easy installation script that will install all pre-requisites and get your Plasma Arcade Button Lights
up and running with minimal efforts. To run it, fire up Terminal which you'll find in Menu -> Accessories -> Terminal
on your Raspberry Pi desktop, as illustrated below:

![Finding the terminal](http://get.pimoroni.com/resources/github-repo-terminal.png)

In the new terminal window type the command exactly as it appears below (check for typos) and follow the on-screen instructions:

```bash
curl https://get.pimoroni.com/plasma | bash
```

Alternatively, on Raspbian, you can download the `pimoroni-dashboard` and install your product by browsing to the relevant entry:

```bash
sudo apt-get install pimoroni
```
(you will find the Dashboard under 'Accessories' too, in the Pi menu - or just run `pimoroni-dashboard` at the command line)

If you choose to download examples you'll find them in `/home/pi/Pimoroni/plasma/`.

### Manual install:

#### Library install for Python 3:

on Raspbian:

```bash
sudo apt-get install python3-plasmalights
```

other environments: 

```bash
sudo pip3 install plasmalights
```

#### Library install for Python 2:

on Raspbian:

```bash
sudo apt-get install python-plasmalights
```

other environments: 

```bash
sudo pip2 install plasmalights
```

### Development:

If you want to contribute, or like living on the edge of your seat by having the latest code, you should clone this repository, `cd` to the library directory, and run:

```bash
sudo python3 setup.py install
```
(or `sudo python setup.py install` whichever your primary Python environment may be)

## Documentation & Support

* Guides and tutorials - https://learn.pimoroni.com/plasma
* Function reference - http://docs.pimoroni.com/plasma/
* Get help - http://forums.pimoroni.com/c/support
