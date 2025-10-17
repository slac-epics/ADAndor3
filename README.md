ADAndor3
========
An 
[EPICS](http://www.aps.anl.gov/epics/) 
[areaDetector](https://github.com/areaDetector/areaDetector/blob/master/README.md) 
driver for sCMOS detectors from 
[Andor Technology](http://www.andor.com)
using Version 3 of the Andor Software Development Kit (SDK).

Known issue with Andor3 SDK:
Several files are left around when the SDK or programs using exit.
If those files are not removed and a different username tries to use the SDK
it causes a segmentation fault and the program crashes.
Remove these files manually to resolve the problem before switching users.
* /tmp/atdevregcam.log
* /tmp/atdevcore.log
* /tmp/andor_pat_temp_CIS2051RO.xml
* /dev/shm/sem.cameraPresentLock

Additional information:
* [Documentation](https://areaDetector.github.io/areaDetector/ADAndor3/ADAndorDoc.html).
* [Release notes and links to source and binary releases](RELEASE.md).
