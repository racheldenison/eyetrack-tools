eyetrack-tools
==============

Tools for interfacing between EyeLink 1000 and Psychtoolbox (Matlab)

This is a simple toolbox for interfacing between the EyeLink1000 eye tracker and Psychtoolbox.

rd_eyeLink.m contains many EyeLink PTB commands you might need when doing online or offline eyetracking during an experiment. The eyetracker code is encapsulated in this function, so you don't have to clutter up your experiment code with EyeLink commands.

rd_eyeTrackTester.m is a demo of how to use rd_eyeLink.m to communicate with the EyeLink and do online eyetracking. This script can also be used to test rd_eyeLink.m.

Rachel Denison

April 2014
