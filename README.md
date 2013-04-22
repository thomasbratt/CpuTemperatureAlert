CPU Temperature Alert
=====================

A Bash script to display an alert when the temperature of one or more CPU cores
exceeds a specified threshold.

Requires:
------------

* The `lm-sensors` package must be installed.

Installation
------------

To install as a Cron job that runs every minute:

    crontab -e
    * * * * * /<path>/wallpaper.sh

Troubleshooting
---------------

* Changes are logged to the `/tmp` folder.
* Requires Gnome based Window Manager to run. Runs fine with Ubuntu 12.10.
