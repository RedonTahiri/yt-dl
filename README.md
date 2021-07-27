yt-dl.lua
=========

A simple commandline tool to download videos from youtube

Usage
-----

Usage: ./yt-dl.lua ID [audioformat [videoformat]]

where:
* ID is either the url of the video, or the id
* audioformat is the format of audio
* videoformat is the format of video

Format can be a number, 1 for first, 2 for second, -1 for last; + for best, and - for the worst. If 0 is used for a component, it won't be downloaded.
