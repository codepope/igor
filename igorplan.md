# Igor

A manager for bot-brains.

## Main config

Runs mosquitto server
Runs web server
Reads brain jars to build menu
Wait for start
On brain selection
    Opens jar
    Finds start, stop, diag in config
    Runs the diag
    Reports if unable to complete
    Runs the start
    Report error if unable to start
    Listens to mosquitto server for alerts
    If no UI, displays stop button
    Else if UI, ... TBD ...
    If stop pressed, run stop script, go to clean up
    If stop received from mqtt, go to cleanup
    Display selection screen

## Brain jars

A directory containing

### Config - Configuration files

Brain.yaml - name, start, stop, diag


Bin/binaries
Scripts/Script files for interpreted brains



