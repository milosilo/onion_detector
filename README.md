# onion_detector

Scanner generates random onion site, tries to connect, and stores successfull connections in a log file.

There are two scripts:
  1. Original random onion scranner
  2. file based onion scanner with starter file.

Script will run if dependancies are met and tor connection is active.

The log file is located in the same folder as the script file.

A timed out message for the onion means it was not detected as up. Do not go below 1 for this setting.

When a onion site is detected, the sites code from hte get request will be printed and the onion site will be logged in the log file.

Try running the scanner twice on your target list.  There is a fun feature where it works better the second time.

Happy onion scanning!
