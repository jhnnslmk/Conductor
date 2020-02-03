# Conductor
Timeline based on MIDI Sequencer for VL/VVVV  
Needs vvvv beta-preview > #4305 (because of changes to the internally used MIDI library)

## Features
* Enable/Disable individual tracks (instruments)
* Create selections for individual notes
* Split tracks and note selections to operate on played note events
* LTC (SMPTE) <-> MIDI Timing conversions
* Tempo-automation safe
* Loop-Region (handy for development)
* Make use of clips to mark parts of the arrangement

## Usage
* **Hold right mouse button** Scroll
* **Middle mouse button** Set playhead
* **Space** Play
* **N** Place loop start marker **M** Place loop end marker
* **L** Toggle loop
* **Ctrl+S** Save arrangement
* **Ctrl+L** Load arrangement

## Roadmap
* Improve UI for clips (overlapping clips are lazily solved by placing them in 4 alternating rows)
* Improve overall UI/UX
* Performance enhancements (zooming out is very bad on the cpu, scrolling while doing so even more)

## Known bugs
* Elementa UI widgets sometimes don't get initialized properly
