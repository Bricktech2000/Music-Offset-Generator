Music Offset Generator
======================

A program to... generate a music offset

Overview
--------

This program is used to create an offset of the music played in each of the two audio channels (the right and left ears) and optionally modify their volumes (or gains). The purpose of this program can seem quite vague, but it simiply allows one to predict the next 4 or 8 beats of a song by listening carefully in their left ear. For example, when flying FPV drones over a specific song, it is way easier to know in advance that, for instance, a beat drop will occur, allowing the pilot to adapt their flying style accordingly. However, it is not limited to FPV drones: anything that requires music synchronization could benefit from this program if used properly.

Requirements
------------

* Any browser with HTML5 support

Setup
-----

No special setup is needed. Simply open up `index.html` in a web browser to use the software.

How to use it
-------------

1. Choose a music file to open
2. Enter the song's BPM value (can be calculated using a website such as [conversion-tool's BPM detector](https://www.conversion-tool.com/bpmdetector/))
3. Enter a music offset in `beats`, usually 4 or 8
4. Select the main ear (the one which will hear the music without any offset)
5. Enter the main and secondary ear volumes, usually `1.0 1.0` or `0.5 1.0`
6. Choose a delay for which the program will sleep before playing the music
7. Click on the `play` button to begin music playback
