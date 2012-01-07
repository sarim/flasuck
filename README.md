# Introduction:

flasuck sucks all buffered flash media stored in your computer's memory buffer. First buffer / load any flash media in web browser then run this script to suck all of them to your desired place, no need to re-download :D

# Requirement:

Works with latest version of Flash Player plugin, Be sure you have latest version of your browser and flash player plugin.

Works in both Mac OSX and Linux. **No Windows support**.

# Installation:

Download the script, make it executable by `chmod +x flasuck.py`, the run it.

System Wide Install, (one liner)

    sudo wget -O /usr/bin/flasuck https://github.com/sarim/flasuck/raw/master/flasuck ; sudo chmod +x /usr/bin/flasuck

now u can run it normally by calling flasuck from anywhere.

    $ flasuck --help

# Usage :

    flasuck [option] [DestDir]

Options and arguments :

    -h
    --help
**help** : Show this help screen and exit

**DestDir** : Write file into DestDir, must be a valid directory. Will select `pwd` when not provided


# Demo:

    $ flasuck 
    Darwin kernel detected :) 
    Scan Started
    copying to => /Users/sarimkhan/testtmp/1T0AZP_1.flv :) 
    copying to => /Users/sarimkhan/testtmp/A5XEF8_2.flv :) 

    Finished Copying 2 File(s)


*flasuck - Flash Media Sucker (c) 2012 by Sarim Khan*
