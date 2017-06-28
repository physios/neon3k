# Neon3K
neon3k is a linux CLI tool written in python for [ozone neon3k mouse] (http://www.ozonegaming.com/product/neon-3k).

Read more about using ozone neon3k mouse under linux [here] (http://pavuk.7gods.org/neon3k/).

## Dependencies
python, phython-usb

For Debian/Ubuntu/Kubuntu/Linux mint:

```Shell
sudo apt-get install python2.7 python-usb
```

## How to run

To run this script you will need to make it executable

```Shell
chmod u+x neon3k
```

After making it executable simply run the following line to get options:

```Shell
./neon3k --help
```
Note that to change options you will need to run Neon3K under sudo, for example I want to change the color to blue so I will run this:

```Shell
sudo ./neon3k --color 1
```

## Target
To get same functionality as "driver" for windows operating system offers.

## TODO
* Profiles switching
* Saving settings to different profiles
