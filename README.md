# Conductor
Timeline based on MIDI Sequencer for VL/VVVV

## Features
* Enable/Disable individual Tracks (instruments)
* Select individual notes in each Track and split
* Split Tracks and Note Selections to operate on played note events
* LTC (SMPTE) <-> MIDI Timing conversions
* Tempo-automation safe
* Loop-Region (handy for development)
* 

# Usage
* *Hold right mouse button* Scroll
* Middle mouse button: Set playhead
* Space: Play
* N: Place loop start marker M: Place loop end marker
* L: Toggle loop
* Ctrl+S: Save arrangement
* Ctrl+L Load arrangement

#Roadmap
* Improve UI for clips (overlapping clips are lazily solved by placing them in 4 alternating rows)
* Improve overall UI/UX
* Performance Enhancements (zooming out is very bad on the cpu, scrolling while doing so even more)

## Known bugs
* Elementa UI Widgets sometimes don't get initialized properly
