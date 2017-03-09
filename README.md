# mtb-points-of-interest

This is a set of locations that may be of use to bikepackers or those on ITTs, mainly those found at selfsupporteduk.net. The initial set is based around those ITT routes but isn't exclusive to them.

## Files

* README.md - this file
* regions.md - describes the regions or areas that are used to organise the locations.
* categories.md - describes the categories that each location belongs to.
* points_of_interest.GPX - the list of points in XML format.

## Installing

The easiest way for Garmin units is to use their POILoader program which is available for both Windows and Mac.

* Download the latest version of the POI file from GitHub.
* Unzip it.
* Connect your device to your computer
* Open POI Loader.
* Point POI Loader at the unzipped file.
* Follow the instructions.
* Remove your device from your computer.
* Restart your device and check that the POIs are shown.

There are two ways to contribute: adding locations yourself or dropping me a line with errata etc.

## Generating POIs

It is easiest to use a program like Garmin Basecamp to generate these.

## Git/GitHub Workflow

If you don't know how to work with GitHub then have a read of the tutorials, you will need to register with GitHub (free) and have either a GUI program that runs Git for you or be able to use Git at the command line.

The basic sequence is:

* In GitHub create a branch with a sensible name based on the region you are editing, "wales-fred-1" for example, has to be unique so add your initials or name.
* On your machine run "git pull" to get the latest version from GitHub which will include your new branch.
* Change to the new branch: "git checkout wales-1"
* Do your changes.
* Commit your changes. You will need to provide a one line description (less than 50 characters), followed by a blank line then a fuller description.
* Push the changes to GitHub, you will need your email address and password for this.
* In GitHub issue a "pull request"

At this point I'll check the changes and if they are OK then they will be merged on to the master branch.

