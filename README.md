# Blackmagic Timecode Tools

This is a collection of simple tools for generating or reading timecode with Blackmagic Design Decklink cards

## TimecodeReader

This is a simple tool that reads timecode from one or more decklinks, and outputs it to the console. 

## TimecodeWriter

This is a slightly modified version of the RP188VitcOutput sample from the Blackmagic SDK

## TimecodeLatencyChecker

This will output a blue video over one decklink, take an input on another and report the delay in the timecode. An internal offset is applied to account for the delay due to internal buffering on the card.

It has only been tested with 1080i50.

# VideoSmoothnessChecker

Not a timecode related tool, but a test which can be used to ensure that the frames being fed to a decklink are correct and not skipping or jumping. It expects an animation of the frame slowly filling from the top with white, see the included html file as an example of this.