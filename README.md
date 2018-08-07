# onion_detector

Scanner generates random onion site, tries to connect, and stores successfull connections in a log file.

Script will run if dependancies are met and tor connection is active.

The log file is located in the same folder as the script file.

A timed out message for the onion means it was not detected as up. Do not go below 1 for this setting.

When a onion site is detected, the sites code from hte get request will be printed and the onion site will be logged in the log file.

Happy onion scanning!
