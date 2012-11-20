GENERAL INFORMATION ABOUT spacereplace version 1.0.1:

This script makes it easy for you to quickly replace all spaces in file and directory names with underscores ('_'). Most p2p files (mp3, mpeg) have spaces in their file names and Linux doesn't like that very much. Let this script replace all spaces with underscores for you. This script can also commit changes to sub-directories.

This version of spacereplace is made by Richard van Kampen on july 25, 2005.
You are free to copy, modify and distribute this script. I would be happy if you
left a reference to my name intact.

If you have remarks or tips regarding this script, 
feel free to drop me a line at richard@vankampen.be. 

CHANGE LOG:

version 1.0.1:

- Name change: space is now called spacereplace.
- Massive speed improvement: V1.0.1 is appr. 10 times faster than v1.0.0. 
  V1.0.1 processes 1700 files in 55 sub-directories in about 2.5 seconds on my AthlonXP 2400.
- Fixed: spacereplace now handles special characters in file names without problems.
- spacereplace without options now returns help. This is to avoid unintentional space replaces.



INSTALLATION:

1- save spacereplace-1.0.1.tar.gz in your home directory
2- open a new console
3- type 'tar -xzf spacereplace-1.0.1.tar.gz'
4- type 'cd spacereplace-1.0.1'
5- type './install'
6- Type the root password when asked and press [ENTER].

spacereplace will be installed in /usr/local/lib, which should
be fine for most people.
When the installation is complete, type 'spacereplace {-r} [DIR]' in your console, or type 'spacereplace --help' to get help.

Example: 'spacereplace -r /home/richard/mp3' changes all spaces into underscores in /home/richard/mp3 and all sub-directories.